# Partition

```bash
df -h
```

# Current directory

```bash
pwd
```

# About

```bash
whoami
```

# Long list

```bash
ls
ls -la
```

# OS Information

```bash
cat /etc/os-release
```

# IP Configuration

```bash
network:
    version: 2
    renderer: networkd
    ethernets:
        ens33:
            addresses:
              - 192.168.0.215/24
            gateway4: 192.168.0.1
            nameservers:
              addresses: [8.8.8.8, 8.8.4.4]
```

# OR

```bash
network:
  version: 2
  renderer: networkd
  ethernets:
    ens33:
      dhcp4: no
      addresses:
        - 192.168.0.204/24
      routes:
        - to: default
          via: 192.168.0.1
      nameservers:
          addresses: [8.8.8.8, 8.8.4.4]
```
```bash
/var/log 
cat /etc/passwd
sudo visudo
```