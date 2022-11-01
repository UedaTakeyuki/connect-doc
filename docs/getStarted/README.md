# Get started

## Sign in to the service
![](./ss.2022-08-10.13.56.36.png)
## Get DeviceID
## Install & setup

### 1. Get connect clinet
Log in on your Raspberry pi, get **connect client** as 

```bash:
git clone https://github.com/UedaTakeyuki/connectcli.git
```

or download lates zip or tarball of releases from [releases](https://github.com/UedaTakeyuki/connectcli/releases/) and expand it.

### 2. Run setup.sh script
Go into "connectcli" folder created by **git clone** or "connectcli.xx.yy.zz" folder downloaded and expanded from [releases](https://github.com/UedaTakeyuki/connectcli/releases/) and expand it.

```bash:
# in case git clone
cd connectcli

# or download and expand it
cd connectcli.xx.yy.zz
```

Then run ``setup.sh `` script

```bash
./setup.sh
```

This script downloads the appropriate version of the application **connect client** and makes an appropriate .service file of the unit definition of Linux service. 

### 3. Get deviceID

Log in or sign in to [Connect](https://connect.uedasoft.com/) service in your browser. You will see something like the following:

![](./ss.2022-10-31.20.46.50.png)

Click the **"V"** shaped dropdown menu icon on the far right of the middle row indicating "Connection: Not Connected". The meaning of this row will be explained later.

Then, you will see a menu dropped down as follows:

![](./ss.2022-10-31.20.47.06.png)

A new menu written as "Selected Device: Device Not Selected" will appear. 
Click the **"Select"** round blue button on the far right of this menu. 
The meaning of this menu will be explained later.

Then, you will see a dialog popped as follows:

![](./ss.2022-08-10.13.56.36.png)

Click the **"REQUEST ONE"** round blue button lower left of this dialog. The detail of this dialog will be explained later.

Then the 6-digit words will appear, which is a brand-new created device ID for you. Note it and return to the Raspberry Pi which you've downloaded the **connectcli**. 

