# PyExchangePasswordSpray forked from the orginal author  iomoath/PyExchangePasswordSpray
# Accept --delay and --jitter as the only delay variables for controlling time between requests.
# Generate random delays for each request.
# Replace the original delay feature with added delay in each request along jitter

Microsoft Exchange password spraying tool with proxy capabilities.


### Features
* Proxy List Support . HTTP & HTTPS
* Set a delay between each password spray.
* Use user & password list from a txt file
* Multi-threading support
* Accept --delay and --jitter as the only delay variables for controlling time between requests.
* Generate random delays for each request.


### Usage

```
$ python3 exchange_password_spray.py -U userlist.txt -P password.txt --url https://webmail.example.org/EWS/Exchange.asmx --delay 3 --jitter 2 -T 1 -ua "Microsoft Office/16.0 (Windows NT 10.0; MAPI 16.0.9001; Pro)" -O result.txt -v
```


```
##################### AUTH URLs samples #####################

# https://webmail.example.org/mapi/
# https://webmail.example.org/EWS/Exchange.asmx
# https://mail.example.org/autodiscover/autodiscover.xml
```

### Proxy Setups
Put your proxy list in ```proxy.txt``` file with the format ```IP:PORT```



# Screenshots
![Demo](MS_Exchange_password_spray.png?raw=true "Demo")




## Meta
Article link:
https://c99.sh/microsoft-exchange-password-spraying/

Moath Maharmeh -  moath@vegalayer.com

https://github.com/iomoath/PyExchangePasswordSpray
