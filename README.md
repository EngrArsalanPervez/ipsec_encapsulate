# How To?

```bash
./build/ipsec-secgw -c 0xf -n 4 --socket-mem 1024,0 --vdev "crypto_openssl" -- -p 0x3 -P -u 0x2 --config="(0,0,0),(1,0,1)" -d HCLOS -f ./IPE_HCLOS.cfg --transfer-mode poll -t 1

./build/ipsec-secgw -c 0xf -n 4 --socket-mem 1024,0 --vdev "crypto_openssl" -- -p 0x3 -P -u 0x2 --config="(0,0,0),(1,0,1)" -d LCLOS -f ./IPE_LCLOS20.cfg --transfer-mode poll -t 1
```
