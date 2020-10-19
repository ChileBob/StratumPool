# StratumPool & StratumSolo : Ycash Solo-Mining Stratum Servers

These are a very simple stratum servers for connecting GPU miners to a Ycash full node.

- StratumPool : Allows miners to specify their own transparent ycash address.
- StratumSolo : Connecting clients mine to the local node wallet ONLY

Both operate as solo-pools', so a miner gets paid ONLY IF they find the solution to a block.

Payments are made within the coinbase transaction, which means :-
- Rewards must mature before they can be spend (100 blocks)
- The first transaction MUST be to a shielded address (s2y)

There's no dev fee, just dont expect any support !! If you'd like to buy beers :-

- YCASH : ys1c8cvazsz5gfp2zhdmzxcarfh4gp6jezdcxnywfcpyuau0l0f9uj99tzvrr6sjw5rfhpsw06lc6n
- ZCASH : https://www.z2z.to/ChileBob

## Requirements :-

- Ycash Full Node (Ubuntu/Debian Linux)
- YECwallet Full Node
- GPU Hardware (ie: Nvidia, AMD)
- GPU Mining Software for Equihash 192,7 (ie: miniZ v1.6w)

## Tested Miners :-

- GMiner (v2.28)
- lolMiner (v0.8.4)
- miniZ (v1.6w)

## Features :-

- allows *many* miners to connect
- pays rewards in the coinbase transaction
- this is strictly for SOLO-MINING

## Usage :-

stratumpool --port=3333 --password=notsecret

* `--port (port number for miner connections, default 3333)`
* `--password (optional password miners need to connect)`

stratumsolo (no config needed)

* default port 3334

## Installation  :-

* sudo apt-get update
* sudo apt-get upgrade
* sudo apt-get install perl build-essential cpan
* sudo cpan
* install CPAN
* reload
* exit

* sudo cpan install POSIX IO::Handle IO::Socket IO::Select JSON	JSON::RPC::Client HTTP::Request JSON::Create Digest::SHA Data::Dumper
