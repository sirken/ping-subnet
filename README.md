# Ping Subnet

Python script for Linux to quickly ping a subnet and display the status of hosts.

![Ping example](images/example.png)

## Installation

Install fping for your Linux distro (Debain example)
```bash
sudo apt install fping
```

Edit the script and change the desired subnet
```python
network = ipaddress.ip_network('192.168.1.0/24')
```

## Usage

```bash
python3 ping-subnet.py
```
