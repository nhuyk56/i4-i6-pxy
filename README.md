bash <(curl -s "https://raw.githubusercontent.com/nhuyk56/i4-i6-pxy/master/scripts/install.sh")

firewall-cmd --permanent --add-port=$port/tcp

/sbin/ifconfig enp1s0 inet6 del 20011:19f0:4400:4eda:e228:110f:1eae:ed22/64

207.148.123.54::
curl -x 207.148.123.254:10010 --proxy-user usrcN0BD:passFnpUw -L https://icanhazip.com
curl --proxy "http://usrcN0BD:passFnpUw@207.148.123.254:10010" https://google.com
curl --proxy "http://usrcN0BD:passFnpUw@207.148.123.254:10010" ""



![cover](cover.svg)

## Requirements
- Centos 7
- Ipv6 \64

## Installation
[Video tutorial](https://youtu.be/EKBJHSTmT4w), used as Centos setup

1. `bash <(curl -s "https://raw.githubusercontent.com/nhuyk56/i4-i6-pxy/master/scripts/install.sh")`
1. `bash <(curl -s "https://raw.githubusercontent.com/dukaev/ipv6_proxy/master/scripts/install.sh")`

1. After installation dowload the file `proxy.zip`
   * File structure: `IP4:PORT:LOGIN:PASS`
   * You can use this online [util](http://buyproxies.org/panel/format.php
) to change proxy format as you like

## Test your proxy

Install [FoxyProxy](https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/) in Firefox
![Foxy](foxyproxy.png)

Open [ipv6-test.com](http://ipv6-test.com/) and check your connection
![check ip](check_ip.png)

