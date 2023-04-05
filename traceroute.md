# Tracer Route

### traceroute www.amazon.com

```
traceroute -I www.amazon.com

traceroute to e15316.dsca.akamaiedge.net (23.194.102.185), 64 hops max, 72 byte packets
 1  irb--2523.uwir-ads-1.infra.washington.edu (10.18.0.2)  47.593 ms  3.992 ms  5.824 ms
 2  irb--50.uwcr-atg-1.infra.washington.edu (10.132.5.73)  10.795 ms  4.023 ms  3.309 ms
 3  ae4--1009.uwcr-atg-1.infra.washington.edu (10.132.5.75)  10.770 ms  2.261 ms  5.416 ms
 4  wi_nat_int.uwcf-atg-2.infra.washington.edu (10.132.255.21)  15.252 ms  3.556 ms  225.021 ms
 5  et-8-0-0--4080.uwcr-atg-1.infra.washington.edu (10.132.255.22)  35.240 ms  3.436 ms  3.697 ms
 6  ae20--4010.icar-sttl1-3.infra.pnw-gigapop.net (209.124.188.134)  14.643 ms  4.155 ms  6.178 ms
 7  hundredge-0-0-0-24.817.core1.seat.net.internet2.edu (198.71.47.5)  12.138 ms  7.237 ms  3.912 ms
 8  fourhundredge-0-0-0-49.4079.agg2.seat.net.internet2.edu (163.253.1.167)  11.273 ms  5.573 ms  3.889 ms
 9  162.252.69.123 (162.252.69.123)  11.111 ms  4.520 ms  4.245 ms
10  ae13.digfort-sea2.netarch.akamai.com (23.203.145.161)  13.089 ms  20.963 ms  10.327 ms
11  a23-194-102-185.deploy.static.akamaitechnologies.com (23.194.102.185)  10.871 ms  2.283 ms  2.139 ms
```

### traceroute www.google.com

```
traceroute -I www.google.com

traceroute to www.google.com (142.250.217.68), 64 hops max, 72 byte packets
 1  irb--2523.uwir-ads-1.infra.washington.edu (10.18.0.2)  38.334 ms  3.329 ms  5.219 ms
 2  irb--50.uwcr-atg-1.infra.washington.edu (10.132.5.73)  8.460 ms  3.848 ms  5.387 ms
 3  ae4--1009.uwcr-atg-1.infra.washington.edu (10.132.5.75)  10.107 ms  4.351 ms  3.475 ms
 4  wi_nat_int.uwcf-atg-2.infra.washington.edu (10.132.255.21)  11.300 ms  2.628 ms  3.695 ms
 5  et-8-0-0--4080.uwcr-atg-1.infra.washington.edu (10.132.255.22)  11.454 ms  2.538 ms  3.118 ms
 6  ae20--4011.icar-sttl1-3.infra.pnw-gigapop.net (209.124.190.134)  12.024 ms  3.605 ms  5.253 ms
 7  74.125.51.244 (74.125.51.244)  10.007 ms  14.175 ms  2.927 ms
 8  142.251.70.101 (142.251.70.101)  11.609 ms  4.592 ms  3.135 ms
 9  142.251.55.199 (142.251.55.199)  9.609 ms  4.032 ms  5.368 ms
10  sea09s29-in-f4.1e100.net (142.250.217.68)  12.129 ms  4.408 ms  3.299 ms
```

### traceroute www.microsoft.com

```
traceroute -I www.microsoft.com

traceroute to e13678.dscb.akamaiedge.net (23.36.249.251), 64 hops max, 72 byte packets
 1  irb--2523.uwir-ads-1.infra.washington.edu (10.18.0.2)  15.839 ms  2.668 ms  3.253 ms
 2  irb--50.uwcr-atg-1.infra.washington.edu (10.132.5.73)  9.992 ms  2.124 ms  3.376 ms
 3  ae4--1009.uwcr-atg-1.infra.washington.edu (10.132.5.75)  8.337 ms  1.806 ms  2.618 ms
 4  wi_nat_int.uwcf-atg-2.infra.washington.edu (10.132.255.21)  10.408 ms  2.062 ms  2.015 ms
 5  et-8-0-0--4080.uwcr-atg-1.infra.washington.edu (10.132.255.22)  13.710 ms  2.716 ms  2.105 ms
 6  ae20--4010.icar-sttl1-3.infra.pnw-gigapop.net (209.124.188.134)  11.164 ms  5.522 ms  3.696 ms
 7  hundredge-0-0-0-24.817.core1.seat.net.internet2.edu (198.71.47.5)  11.027 ms  4.965 ms  4.694 ms
 8  fourhundredge-0-0-0-48.4079.agg2.seat.net.internet2.edu (163.253.1.165)  16.282 ms  5.261 ms  4.328 ms
 9  162.252.69.123 (162.252.69.123)  9.996 ms  2.345 ms  2.964 ms
10  ae3.sabey-sea3.netarch.akamai.com (23.203.145.215)  9.655 ms  4.516 ms  8.553 ms
11  a23-36-249-251.deploy.static.akamaitechnologies.com (23.36.249.251)  9.691 ms  3.104 ms  3.051 ms
```
