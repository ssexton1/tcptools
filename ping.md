# Ping

### ping www.amazon.com

```
ping -c 5 www.amazon.com

PING d3ag4hukkh62yn.cloudfront.net (18.172.169.208): 56 data bytes
64 bytes from 18.172.169.208: icmp_seq=0 ttl=247 time=9.167 ms
64 bytes from 18.172.169.208: icmp_seq=1 ttl=247 time=149.228 ms
64 bytes from 18.172.169.208: icmp_seq=2 ttl=247 time=5.445 ms
64 bytes from 18.172.169.208: icmp_seq=3 ttl=247 time=37.914 ms
64 bytes from 18.172.169.208: icmp_seq=4 ttl=247 time=81.995 ms

--- d3ag4hukkh62yn.cloudfront.net ping statistics ---
5 packets transmitted, 5 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 5.445/56.750/149.228/53.741 ms
```

### ping www.google.com

```
ping -c 5 www.google.com

PING www.google.com (142.250.217.68): 56 data bytes
64 bytes from 142.250.217.68: icmp_seq=0 ttl=116 time=9.709 ms
64 bytes from 142.250.217.68: icmp_seq=1 ttl=116 time=6.890 ms
64 bytes from 142.250.217.68: icmp_seq=2 ttl=116 time=3.326 ms
64 bytes from 142.250.217.68: icmp_seq=3 ttl=116 time=6.710 ms
64 bytes from 142.250.217.68: icmp_seq=4 ttl=116 time=4.007 ms

--- www.google.com ping statistics ---
5 packets transmitted, 5 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 3.326/6.128/9.709/2.284 ms
```

### ping www.microsoft.com

```
ping -c 5 www.microsoft.com

PING e13678.dscb.akamaiedge.net (104.73.1.162): 56 data bytes
64 bytes from 104.73.1.162: icmp_seq=0 ttl=57 time=8.673 ms
64 bytes from 104.73.1.162: icmp_seq=1 ttl=57 time=4.195 ms
64 bytes from 104.73.1.162: icmp_seq=2 ttl=57 time=6.066 ms
64 bytes from 104.73.1.162: icmp_seq=3 ttl=57 time=4.722 ms
64 bytes from 104.73.1.162: icmp_seq=4 ttl=57 time=5.299 ms

--- e13678.dscb.akamaiedge.net ping statistics ---
5 packets transmitted, 5 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 4.195/5.791/8.673/1.569 ms
```
