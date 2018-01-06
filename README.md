# sshd - Docker-Tools-Container

Docker Ubuntu 16.04 image containing sshd, ping, netstat, ifconfig, tcpdump, traceroute, sudo

To run:
docker run -d --publish=2222:22 moonbeamzebra/sshd

ssh -p 2222 myu@127.0.0.1  
password: myu1
