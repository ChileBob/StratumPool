# StratumPool : Solo-mining stratum server

This is a very simple stratum server for connecting GPU miners to a Ycash full node.

## Requirements :-

- Ubuntu/Debian Linux

## Features :-

- allows *many* miners to connect
- pays rewards in the coinbase transaction
- this is strictly for SOLO-MINING

# Usage :-

stratumpool --port 3333 --password notsecret

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
