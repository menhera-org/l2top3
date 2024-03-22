# l2top3
Scripts for L2TPv3 static tunnels, for GNU/Linux.

## Installation

```bash
wget https://github.com/menhera-org/l2top3/raw/main/l2top3
sudo sh ./l2top3 install
```

## Configuration

To create a tunnel interface named l2tp1:

/etc/l2top3.d/l2tp1.conf:

```
IP_VERSION=4
TUNNEL_ID=1
REMOTE=remote.hostname.example
```
