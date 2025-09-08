# Sub Addresses
The following are the addresses that I collected from [cmliu](https://github.com/cmliu/)'s videos [CF VLESS从入门到精通 cmliu/edgetunnel 必看内容 免费节点 优选订阅 Workers & Pages CM喂饭干货满满24](https://www.youtube.com/watch?v=oRYnrp5rQSc&t=419s)
```
SUB.cmliussss.net
VLESS.cmliussss.net
VLESS.fxxk.dedyn.io
sub.cmliussss.workers.dev
noTLS.fxxk.dedyn.io
alvless.comorg.us.kg
3k.fxxk.dedyn.io
```


# Set RPROXYIP
Set `RPROXYIP` as true by adding this `&rproxyip=true` in the Subscription Address, 即可强制获取订阅器分配的ProxyIP(需订阅器支持) [Guide](https://www.youtube.com/watch?v=s91zjpw3-P8&t=1816s)


# Add Optimal IPs via API
Set up the variable: `ADDAPI`. Has to add the variable in the cloudflare panel. Also, ADDAPI won't take effect when using SUB.
See guide video here: [自有IP库](https://www.youtube.com/watch?v=oRYnrp5rQSc&t=992s) \
Example: 
Set the value of `ADDAPI` as the following APIs, which are found on this site [cf.090227.xyz](https://cf.090227.xyz/)
```
https://addressesapi.090227.xyz/ct
https://addressesapi.090227.xyz/cmcc
https://addressesapi.090227.xyz/cmcc-ipv6
https://addressesapi.090227.xyz/CloudFlareYes
https://addressesapi.090227.xyz/ip.164746.xyz
https://ipdb.api.030101.xyz/?type=bestcf&country=true
https://ipdb.api.030101.xyz/?type=cfv4;cfv6&country=true
https://ipdb.api.030101.xyz/?type=bestproxy&country=true&proxyip=true
```


# Troubleshooting
[常见问题汇总FAQ](https://vercel.blog.cmliussss.com/p/%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E6%B1%87%E6%80%BB/)
Note to generate UUID in the V2rayN, otherwise the UUID may not work.

https://vercel.blog.cmliussss.com/p/%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E6%B1%87%E6%80%BB/
