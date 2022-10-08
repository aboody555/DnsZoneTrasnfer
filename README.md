# DnsZoneTrasnfer
simple bash script attempt to transfer all the information from DNS server.

A zone transfer is a database replication between DNS servers in witch the zone file copied from a master DNS to slave server. the zone file contains a list of all the dns names for that zone.
Zone transfer should only be allowed to authorized slave DNS servers but many administartors misconfigure DNS servers and make anyone asking for a copy of the DNS server zone will recive one. 

This script attempt zone transfer for any domain. All what you have to do is simply write the domain name and the script will get you all the DNS servers related to that domain and try to do zone transfer on it.

# How to use 
```
https://github.com/aboody555/DnsZoneTrasnfer.git

```
```
cd DnsZoneTrasnfer/
```
```
chmod +x dnsZoneTransfer
```
```
./dnsZoneTransfer
```

