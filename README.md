
```
apt update && apt upgrade -y --fix-missing && update-grub && sleep 2 && apt -y install xxd && apt install -y bzip2 && apt install -y wget && apt install -y curl && reboot
```
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/ataaxd/v1/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```
