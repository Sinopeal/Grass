# How to use
## Get User Id

Open the link and log in https://app.getgrass.io/dashboard
Press F12 on the page to open the console and enter the code (Ctrl + Shift + i) inspect
Write localStorage.getItem('userId') in the console
"PRINTED TEXT IS THE USER_ID"
![image](https://github.com/user-attachments/assets/abdd663d-22e0-4198-94d2-24e88a06607a)

## Get Proxy
The format of the proxy should be 

socks5://username:password@ip:port

or 

http://username:password@ip:port

## Configure your settings
1. replace your user id.

![image](https://github.com/user-attachments/assets/db4915d1-9e40-4729-8bb2-636eea6775fc)

2. write your proxies into file proxy.txt

![image](https://github.com/user-attachments/assets/2963cc56-7a31-4a36-a88c-0ada14502716)

## Run and earn
1. Install the requirements
``` bash
pip install -r requirements.txt
```
2. Run the script
``` bash
python3 main.py
```
