# How to Install Metasploit in termux without any hassle.
### Try my method it'll 100% works...
##### (1) Clear all data from termux.
##### (2) Start Termux.
##### (3) Run these commands step by step...
```bash
apt update && apt upgrade -y
```
```bash
apt install ruby curl git wget -y
```
```bash
gem install bundler:1.17.3
```
```bash
wget https://raw.githubusercontent.com/LexFrom1984/Metasploit-Framework/main/metasploit_5.0.56_android5_all.deb
```
```bash
chmod +x metasploit_5.0.56_android5_all.deb
```
```bash
dpkg -i metasploit_5.0.56_android5_all.deb
```
##### (4) it's not error, run...
```bash
apt install -f
```
#### So, Dependency & Metasploit are Installed successfully...

##### You can start or stop Postgresql Database using this command...
#####[start]
```bash
pg_ctl -D /data/data/com.termux/files/usr/var/lib/postgresql -l logfile start
```
#####[stop]
```bash
pg_ctl -D /data/data/com.termux/files/usr/var/lib/postgresql -l logfile stop
```
## If You're copying my content, Please give me credits...
