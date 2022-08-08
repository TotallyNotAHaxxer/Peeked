# Usage 

simply just git clone this url and run the script `go run main.go` or `go build main.go ; ./main`

# Console I/O help

When you enter the console you will be prompted to a simle wait for input like this

```
Peeked> 
```

**to set a host to scan run the following**

```
Peeked> set host www.scanme.org
```

**to set a verbosity on or off do the following**

```
Peeked> set verb true
```

**to scan an address**

```
Peeked> script scan
```

# Output example with verbosity

```
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:1221: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:1308: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:940: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:667: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:1101: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:1489: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:2335: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:2126: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:2334: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:735: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:2127: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:860: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:859: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:1388: connect: connection refused
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:139: connect: permission denied
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:445: connect: permission denied
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:135: connect: permission denied
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:138: connect: permission denied
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:136: connect: permission denied
dial tcp [2600:3c01::f03c:91ff:fe18:bb2f]:137: connect: permission denied
All open ports - 
	[2] 	 80
	[2] 	 22
Total ports scanned ->  64330
```

# Output WITHOUT verbosity

```
Port - 80 
             | tcp 	| 80   	| http
             | udp 	| 80   	| http
             | tcp 	| 80   	| www
             | udp 	| 80   	| www
             | tcp 	| 80   	| www-http
             | udp 	| 80   	| www-http
             | sctp 	| 80   	| http

```

