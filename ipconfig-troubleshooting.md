# Ping and Traceroute Lab

## 🧰 Commands Used
```bash
ping google.com
tracert google.com         # Windows
------------------------------------------------------------------
📊 Output (Examples)
🟢 Ping

	Pinging google.com [142.250.217.206] with 32 bytes of data:
	Reply from 142.250.217.206: bytes=32 time=22ms TTL=116
	Reply from 142.250.217.206: bytes=32 time=24ms TTL=116

🌐 Traceroute (tracert)

	Tracing route to google.com [142.250.217.206]
  	1     1 ms     2 ms     2 ms  192.168.1.1
  	2    10 ms     9 ms    10 ms  10.21.0.1
  	3    20 ms    22 ms    21 ms  some-provider.com
