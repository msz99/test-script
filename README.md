### To install please run this twice

```
wget https://raw.githubusercontent.com/msz99/test-script/main/testing.sh && chmod +x testing.sh && ./testing.sh
```

### Script Feature

SSH & OpenVPN

OHP SSH & OHP Dropbear & OHP OpenVPN

V2RAY VMESS & VLESS (TLS & NON TLS)

XRAY VLESS (XTLS, TLS & GRPC)



### Os Supported

Tested on Debian 10 works fine

### Service & Port

OpenSSH                 : 22

OpenVPN                 : TCP 1194, UDP 2200

Stunnel4                : 442

Dropbear                : 109, 143

Squid Proxy             : 3128, 8080

OHP DropBear            : 8170

OHP OpenVPN             : 8180

Badvpn                  : 7300

Nginx                   : 81

V2Ray VMess TLS         : 443

V2Ray VMess None TLS    : 80

V2Ray VLess TLS         : 443

V2Ray VLess None TLS    : 80

XRay XTLS               : 901

XRay TLS                : 902

XRay GRPC               : 903


### Server Information & Other Features

Timezone              : Asia/Kuala_Lumpur (GMT +8)
Fail2Ban              : [ON]
DDoSDeflate           : [ON]
IPtables              : [ON]
Auto-Reboot           : [ON]
IPv6                  : [OFF]

Autoreboot On 05.00 GMT +8

Auto Delete Expired Account (auto lock account when 0 days validity, auto delete account after 3 days of expiry)

Auto Ban Multiple Login Account (can be unlock)

### Script by : t.me/msz99

### Note : to fix the stunnel4 is not running error, change the port at "menu>5>2>2" to any port u want (because im lazy to edit the file again)
