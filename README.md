# SSEncrypt.module
SSEncrypt.module for Surge

作者为 Surge 作者

# MD5 验证
MDE5:f7653207090ce3389115e9c88541afe0

来源：https://trello.com/c/BTr0vG1O/47-ss-libev-%E7%9A%84%E6%94%AF%E6%8C%81%E6%83%85%E5%86%B5

# 使用方法
单个
```
Proxy = custom, 1.2.3.4, 443, chacha20-ietf-poly1305, password, https://raw.githubusercontent.com/ConnersHua/SSEncrypt/master/SSEncrypt.module, obfs=tls,obfs-host=yunjiasu-cdn.net
```
群组
```
[Proxy]
🇯🇵 JP = custom, 1.2.3.4, 443, chacha20-ietf-poly1305, password, https://raw.githubusercontent.com/ConnersHua/SSEncrypt/master/SSEncrypt.module, obfs=tls,obfs-host=yunjiasu-cdn.net
🇸🇬 SG = custom, 1.2.3.4, 443, chacha20-ietf-poly1305, password, https://raw.githubusercontent.com/ConnersHua/SSEncrypt/master/SSEncrypt.module, obfs=tls,obfs-host=cloudfront.net
🇰🇷 KR = custom, 1.2.3.4, 443, chacha20-ietf-poly1305, password, https://raw.githubusercontent.com/ConnersHua/SSEncrypt/master/SSEncrypt.module
🇺🇸 US= custom, 1.2.3.4, 443, chacha20-ietf-poly1305, password, https://raw.githubusercontent.com/ConnersHua/SSEncrypt/master/SSEncrypt.module

[Proxy Group]
Proxy = select,🕹 Auto,🇯🇵 JP,🇸🇬 SG,🇰🇷 KR,🇺🇸 US
🕹 Auto = url-test,🇯🇵 JP,🇸🇬 SG,🇰🇷 KR,🇺🇸 US,url = http://www.gstatic.com/generate_204
```
