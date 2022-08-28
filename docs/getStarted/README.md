# Get started

## Sign in to the service
![](./ss.2022-08-10.13.56.36.png)
## Get DeviceID
## Install & setup

### 1. get connect clinet
Log in on your Raspberry pi, get **connect client** with 

```bash:
git clone https://github.com/UedaTakeyuki/connectcli.git
```

or download lates releases from [releases](https://github.com/UedaTakeyuki/connectcli/releases/) and expand it.

### 2. run setup.sh script
Go into "connectcli" folder created by **git clone** or "connectcli.xx.yy.zz" folder downloaded and expanded from [releases](https://github.com/UedaTakeyuki/connectcli/releases/) and expand it.

```bash:
cd connectcli
```

Then run ``setup.sh `` script

```bash
./setup.sh
```

This script downloads the appropriate version of the application **connect client** and makes an appropriate .service file of the unit definition of Linux service. 
