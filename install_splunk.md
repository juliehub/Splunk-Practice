Create an account on splunk.com and download the installation package for Linux
```bash
$ wget -O splunk-8.0.5-a1a6394cc5ae-Linux-x86_64.tgz 'https://www.splunk.com/bin/splunk/DownloadActivityServlet?architecture=x86_64&platform=linux&version=8.0.5&product=splunk&filename=splunk-8.0.5-a1a6394cc5ae-Linux-x86_64.tgz&wget=true'
$ sudo mv splunk-8.0.5-a1a6394cc5ae-Linux-x86_64.tgz /opt/
$ cd /opt
$ sudo tar -xvzf splunk-8.0.5-a1a6394cc5ae-Linux-x86_64.tgz
```
Start Splunk
```bash
$ cd /opt/splunk/bin
$ sudo ./splunk start --accept-license

This appears to be your first time running this version of Splunk.

Splunk software must create an administrator account during startup. Otherwise, you cannot log in.
Create credentials for the administrator account.
Characters do not appear on the screen when you type in credentials.

Please enter an administrator username: admin
...
Waiting for web server at http://127.0.0.1:8000 to be available..... Done


If you get stuck, we're here to help.  
Look for answers here: http://docs.splunk.com

The Splunk web interface is at http://upc1:8000
```
