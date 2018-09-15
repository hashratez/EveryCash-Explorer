# EveryCash Blockchain Explorer
Block explorer for EveryCash CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon EveryCashd. It should be accessible from the Internet. Run EveryCashd with open port as follows:
```bash
./EveryCashd --enable-cors="*" --enable_blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=18112
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.

#### Public Explorer
If this will be hosted on a public webserver sometimes there are issues with resloving local IP & Apache, to avoid issue use the following change using your pubic IP

config.js
```
var api = 'http://PUBICIPADDRESS:18112';
```
In config.phps:
```
'api' => 'http://PUBICIPADDRESS:18112',
```

Credit to Sanjay Saluth for the debugging.

### Forked from: 
Devs:
    @devopsralf

Here is his Donate: [TRTL] TRTLv2RCPuD7AaaVpQkRPF59MMLx5WW3qFxwJz4Doy7dHhNA6UuQjEpLL3rpUQS4RXdQn8fb4P1XC3K62GeJjGgG8DP9LNaTrNL

### Note

A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
