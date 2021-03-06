# Java

* [Installation](http://www.webupd8.org/2014/03/how-to-install-oracle-java-8-in-debian.html)

# MySQL

* [Installation](https://wiki.ubuntuusers.de/MySQL/)

# Root User

* <http://www.liquidweb.com/kb/how-to-add-a-user-and-grant-root-privileges-on-ubuntu-14-04/>

# Show all ports

* `sudo lsof -nP -i`

# SSH Key

* <https://help.ubuntu.com/community/SSH/OpenSSH/Keys>
* Show ssh fingerprint
  * `ssh-keygen -lf [PATH]`
  * `ssh-keygen -E md5 -lf [PATH]`

# Environment Variables

* <https://help.ubuntu.com/community/EnvironmentVariables>

# Flatten Directory

* `find [DIRECTORY] -mindepth 2 -type f -exec mv -i '{}' [DIRECTORY] ';'` (works in OSX)

## Show Disk Usage

```bash
df -h --total
```

## Disk Partition

https://help.ubuntu.com/community/InstallingANewHardDrive

```bash
sudo lsblk -o NAME,FSTYPE,SIZE,MOUNTPOINT,LABEL
```
