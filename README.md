# python3HTTPSAuthServer
It's SimpleHTTPServer, with python3
Supports:
  - HTTP Basic AUTH   [username:pass]
  - HTTPS encryptioN


`usage: python3HTTPSAuthServer.py [-h] [-i IP] [-p PORT] [-a AUTH] [-s] [-c CERT] [-k PRIVATEKEY]`  
  
`Python HTTPS Auth Server`  
  
`optional arguments:`    
`-h, --help            show this help message and exit`  
`-i IP, --ip IP        Bind IP (Default all interfaces 0.0.0.0)`  
`-p PORT, --port PORT  Bind port, default 8443`  
`-a AUTH, --auth AUTH  HTTP BASIC auth [username:password]`  
`-s, --https           Use HTTPS`  
`-c CERT, --cert CERT  If you brought your own CERT, then by all means... [fullpath]`  
`-k PRIVATEKEY, --privatekey PRIVATEKEY If you brought your own PRIVATE_KEY, then by all means... [fullpath]`  
   
  
### Install using pip3:
`sudo python3 -m pip install python3HTTPSAuthServer`  

### Run the familiar way
`python3 -m python3HTTPSAuthServer`  

### Get Help
`python3 -m python3HTTPSAuthServer -h`  

### HTTPS Basic AUTH, port 8443:
`python3 -m python3HTTPSAuthServer --ip yourIPaddress --auth 'username:password' --https --cert /PATH/TO/CERT/NAMEOFCERT.pem --privatekey /PATHTOKEY/NAMEOFKEY.pem`





