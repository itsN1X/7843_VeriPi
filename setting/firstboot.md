Tis the pre-config execuion during `initd`.

### Donations: `VG2PkiCa6AVTX8CuxNB7CeXcm1s8h2V8hC`

#### log:

```
-bash: ./cpuminer: No such file or directory
pi@raspberrypi:~ $ ls
create_Verium_Wallet.sh  verium  vrmcheck.sh
pi@raspberrypi:~ $ ./create_Verium_Wallet.sh
Verium server starting
Verium Guide 1/6: Generating Wallet. Wait 2 min
Verium: Unable to bind to 0.0.0.0:36988 on this computer. Verium is probably already running.
Verium: Failed to listen on any port. Use -listen=0 if you want this.
Verium Guide 2/6: Get daemon  info using ~/verium/wallet/src/veriumd getinfo
{
   "version" : "v1.1.0.0",
   "protocolversion" : 80001,
   "walletversion" : 60000,
   "balance" : 0.00000000,
   "newmint" : 0.00000000,
   "totalsupply" : 1471838.33877467,
   "blocks" : 173823,
   "timeoffset" : 0,
   "connections" : 4,
   "proxy" : "",
   "ip" : "103.66.79.138",
   "difficulty" : 0.01992524,
   "blocksperhour" : 0,
   "testnet" : false,
   "keypoololdest" : 1520946261,
   "keypoolsize" : 101,
   "paytxfee" : 0.20000000,
   "mininput" : 0.00000000,
   "errors" : ""
}
Verium Guide 3/6: Your wallets address is:
[
   "VG2PkiCa6AVTX8CuxNB7CeXcm1s8h2V8hC"
]
Copy it for your miners to use

Verium Guide 4/6: Directly download the Blockchain for speed up...
{
   "success" : true,
   "comment" : "Bootstrap successful; veriumd has been stopped, please restart."
}
Verium Guide 5/6: Blockchain update complete, restarting wallet, wait 2 min
Verium server starting
Verium Guide 6/6: Welcome to
     __        Autostart Configuration:
 _  /  \  _    sudo nano /etc/rc.local
/| (    ) |\  
( (  \  /  ) )  Web-Monitor Configuration:
\ \  \/  / /   nano /var/www/html/minerHosts
 \ \    / /
  \ \  / /     Donations (VRC or VRM):
   \ -- /      VBzaNDExHyFpnNvYc5QH5e4ipBZqxxPnKJ
    \  /    
     --        Wallet Creation: ~/create_Verium_Wallet.sh
 V E R I U M   Wallet (CLI) & Monitor Image by joe_rondx

pi@raspberrypi:~ $

```

---

## (C) 2018 N1X.
<https://N1X.site/>
