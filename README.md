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
