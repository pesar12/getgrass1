# getgrass
## installation
install python3

for windows: https://www.python.org/ftp/python/3.12.2/python-3.12.2-amd64.exe 

for linux distros: ```sudo apt-get install python3``` or ```sudo yum install python3``` or ```sudo dnf install python3```
# clone the repo
```bash
git clone https://github.com/pesar12/getgrass1.git
cd getgrass1
```

## module install 
```bash
pip install -r requirements.txt
```
**or install one by one**
install websocket
```
pip install websockets==12.0
```
install fakeuseragent
```
pip install fake_useragent
```

install loguru
```
pip install loguru
```

install websockets_proxy
```
pip install websockets_proxy
```

## register: 
- https://app.getgrass.io/register/?referralCode=Hfcd2LgzYoRLmTW ( use this link instead! )

## how to use

#### getting your user id

- login to [https://app.getgrass.io](https://app.getgrass.io/register/?referralCode=Hfcd2LgzYoRLmTW)

then insert this code ```localStorage.getItem('userId')```
IF YOU GET Don’t paste code into the DevTools Console
just type ```allow pasting``` and ENTER

![0001](https://github.com/im-hanzou/getgrass_bot/blob/main/pasting.JPG)

then insert this code again
```localStorage.getItem('userId')```

![0001](https://github.com/im-hanzou/getgrass_bot/blob/main/userid.JPG)

#### usage command

- fill your proxy in `proxy.txt `
- edit your id in `user_id.txt` each line for 1 account
- then run the script
```
python3 main.py
```
or run script for auto update proxy list
```
python3 grass.py
```
 






