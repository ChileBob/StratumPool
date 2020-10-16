# StratumPool : Ycash Solo-Mining Stratum Server

This is a very simple stratum server for connecting GPU miners to a Ycash full node.

There's no dev fee, this code is MIT Licence so use it however you like - just dont expect any support ;-)

If you'd like to buy beers :-

- YCASH : ys1c8cvazsz5gfp2zhdmzxcarfh4gp6jezdcxnywfcpyuau0l0f9uj99tzvrr6sjw5rfhpsw06lc6n
- ZCASH : https://www.z2z.to/ChileBob

## Requirements :-

- Ubuntu/Debian Linux
- Ycash Full Node
- GPU Hardware (ie: Nvidia)
- GPU Mining Software for Equihash 192,7 (ie: miniZ v1.6w)

## Features :-

- allows *many* miners to connect
- pays rewards in the coinbase transaction
- this is strictly for SOLO-MINING

## Usage :-

stratumpool --port=3333 --password=notsecret

* `--port (port number for miner connections)`
* `--password (optional password miners need to connect)`

## Installation  :-

* sudo apt-get update
* sudo apt-get upgrade
* sudo apt-get install perl build-essential cpan
* sudo cpan
* install CPAN
* reload
* exit

* sudo cpan install POSIX IO::Handle IO::Socket IO::Select JSON	JSON::RPC::Client HTTP::Request JSON::Create Digest::SHA Data::Dumper
