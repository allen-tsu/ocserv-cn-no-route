# ocserv-cn-no-route

## OpenConnect VPN Server

��ҳ��[http://www.infradead.org/ocserv/](http://www.infradead.org/ocserv/)

���أ�[http://www.infradead.org/ocserv/download.html](http://www.infradead.org/ocserv/download.html)

������ʷ��[http://www.infradead.org/ocserv/changelog.html](http://www.infradead.org/ocserv/changelog.html)

Դ�룺[https://gitlab.com/ocserv/ocserv.git](https://gitlab.com/ocserv/ocserv.git)

## OpenConnect VPN Client

��ҳ��[http://www.infradead.org/openconnect/](http://www.infradead.org/openconnect/)

���أ�[http://www.infradead.org/openconnect/download.html](http://www.infradead.org/openconnect/download.html)

������ʷ��[http://www.infradead.org/openconnect/changelog.html](http://www.infradead.org/openconnect/changelog.html)

Դ�룺[http://git.infradead.org/users/dwmw2/openconnect.git](http://git.infradead.org/users/dwmw2/openconnect.git)

## [Cisco AnyConnect VPN Client](https://cnlic.com/share/client.html)

## ע�����

1��0.10.5 ��֮ǰ�汾ocserv��Ҫ�޸�src/vpn.h��֧�ֳ���96��(ocservĬ��ֵ)��������200��(Cisco AnyConnect���ֵ)��·�ɱ�:

```
#define MAX_CONFIG_ENTRIES 96
```

96��Ϊ200����

0.10.6 ��֮��汾ocserv����Ҫ�޸ģ��ο�[https://gitlab.com/ocserv/ocserv/issues/17](https://gitlab.com/ocserv/ocserv/issues/17)

2������[Cisco�ٷ��ĵ�](http://www.cisco.com/c/en/us/products/collateral/security/ios-sslvpn/prod_white_paper0900aecd80512071.html)��no-route��route����ͬʱʹ�á�

```
You can specify either split-include or split-exclude, but you cannot specify both options.
```

## ϲѶ

2015/12/08 Debian�йٷ�ocservԴ�ˣ�[https://tracker.debian.org/pkg/ocserv](https://tracker.debian.org/pkg/ocserv)

```
echo 'deb http://ftp.debian.org/debian/ unstable main contrib non-free' >> /etc/apt/sources.list
apt-get update
apt-get install ocserv
```
## �ƹ�

[���߹�](https://bandwagonhost.com/aff.php?aff=1366)VPS�ƹ�����

| ����                                              | �ײ�                   | �۸�($�긶)            | ����                                           |
|---------------------------------------------------|------------------------|------------------------|------------------------------------------------|
| https://bandwagonhost.com/aff.php?aff=1366&pid=12 |10G VZ - PROMO|19.99|512M�ڴ桢500GB����/�¡�10GB SSDӲ��|
| https://bandwagonhost.com/aff.php?aff=1366&pid=27 |SPECIAL 10G VZ PROMO V3 - PHOENIX AZ|11.99|512M�ڴ桢1000GB����/�¡�10GB SSDӲ��|
| https://bandwagonhost.com/aff.php?aff=1366&pid=28 |SPECIAL 20G VZ PROMO V3 - PHOENIX AZ|18.99|1024M�ڴ桢2000GB����/�¡�20GB SSDӲ��|
| https://bandwagonhost.com/aff.php?aff=1366&pid=34 |SPECIAL 10G VZ PROMO V3 - LOS ANGELES - CHINA DIRECT ROUTE|19.99|512M�ڴ桢1000GB����/�¡�10GB SSDӲ��|
| https://bandwagonhost.com/aff.php?aff=1366&pid=36 |SPECIAL 10G VZ PROMO V3 - FREMONT CA|19.99|512M�ڴ桢1000GB����/�¡�10GB SSDӲ��|
| https://bandwagonhost.com/aff.php?aff=1366&pid=43 |10G KVM - PROMO|19.99|512M�ڴ桢500GB����/�¡�10GB SSDӲ��|

������DNS��Ⱦ������hosts��������������

```
104.20.6.63	bandwagonhost.com
104.20.7.63	bandwagonhost.com
```

[VULTR](https://www.vultr.com/?ref=6923829)VPS�ƹ�����

| ����                                              | �۸�($�¸�)            | ����                                           |
|---------------------------------------------------|------------------------|------------------------------------------------|
| https://www.vultr.com/?ref=6923829 |2.50|1CPU��512MB�ڴ桢500GB����/�¡�20GB SSDӲ��|
| https://www.vultr.com/?ref=6923829 |5.00|1CPU��1GB�ڴ桢1000GB����/�¡�25GB SSDӲ��|
| https://www.vultr.com/?ref=6923829 |10.00|1CPU��2GB�ڴ桢2000GB����/�¡�40GB SSDӲ��|
| https://www.vultr.com/?ref=6923829 |20.00|2CPU��4GB�ڴ桢3000GB����/�¡�60GB SSDӲ��|