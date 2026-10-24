# ufw-logging-lab
Some work with ufw logs.

## Goal
Checking the log for entries about the blocked connection.

## Environment
- Host: Windows 10, VirtualBox 7.2.22
- VM1: Ubuntu 26.04, name: mainvm, IP 192.168.56.101
- VM2: Ubuntu 26.04, name: subvm, IP 192.168.56.102
- Network: Host-Only

## Set up for work
Check up ufw current status
![checkup](screenshots/ufwstatusverbose.png)
```
sudo ufw status verbose
```
Then deleting allowing rule from previous lab work
![ruledel](screenshots/deleterule.png)
```
sudo ufw delete allow 8000/tcp
```
Then enabling ufw logging and checking up for status again
![loggingcheckup](screenshots/ufwstatusafterlogen.png)
```
sudo ufw logging on
sudo ufw status verbose
```
## Log entries
## Results 
## Problems and conclusions 
