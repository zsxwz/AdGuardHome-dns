# AdGuardHome分流规则。

dns-China.txt : 国内的域名，走的是阿里的doh，剩下的都走google或者cloudflare的doh。

dns-global.txt :国外的域名，走的是cloudflare的doh3，doh3想不与doh性能可能稍微好点，接近udp。支持doh3的目前应该是只有google和cloudflare了。剩下的走国内的阿里，腾讯之类的。

自己喜欢哪种规则就下哪种，自己用的是dns-global.txt，你可以下载下载修改为你喜欢用的dns。
