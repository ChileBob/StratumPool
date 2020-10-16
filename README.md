MIT License

Copyright (c) 2019 ChileBob

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


# Ystratum : Solo-mining stratum server for GPU-mining

This is a very simple stratum server for connecting GPU miners to a Ycash full node.

## Requirements :-

- Ubuntu/Debian Linux

## Things it DOES do :-

- allows *many* miners to connect and mine to their own payment address
- pays all rewards within the coinbase transaction
- this is strictly for SOLO-MINING, or 'POOLED-SOLO-MINING'

## Things it DOESNT do :-

- does not hold miners rewards, payouts occur immediatly a block is mined.
- no ongoing support

# Usage :-

ystratum --port 3333 --password notsecret

* `--port (port number for miner connections)`
* `--password (optional password miners need to connect)`

# Installation  :-

* sudo apt-get update
* sudo apt-get upgrade

* sudo apt-get install perl build-essential cpan
* sudo cpan
* install CPAN
* reload
* exit

* sudo cpan install POSIX IO::Handle IO::Socket IO::Select JSON	JSON::RPC::Client HTTP::Request JSON::Create Digest::SHA Data::Dumper
