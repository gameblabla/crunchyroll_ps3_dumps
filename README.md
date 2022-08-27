Crunchyroll PS3 packet dumps
============================

Hello guys,
as you may know already Crunchyroll will shutdown servers for old consoles in August 29, 2022.

Thanks to Charles Proxy and RPCS3, i was able to dump some packets from Crunchyroll.

I also have dumps for the premium version but for now, i won't be able to share them (because it was my personal account :P).

I was also able to get partial dumps from the Vita version : 
this was done by forcing HTTP:// in ApiRequestSpec.js (see provided diff file).

The video feeds themselves were https though but worst case, these could be figured out from the PS3 dumps.

Note that the PSVita dumps are somewhat "tainted" because i changed the privacy link to one of my websites to see if it worked and it infact it did :)...

Enjoy the dumps

Here are the IPs from the SSL proxy you should exclude if you want to snoop (i might be missing a few) :
```
65.9.95.105:80
65.9.95.69:80
65.9.95.32:80
65.9.95.86:80
65.9.95.96:80
52.35.236.71:80
65.9.95.5:80
172.64.147.123:80
104.18.40.133:80
3.231.143.107:80
38.98.139.48:80
65.9.95.4:80
3.231.143.108:80
3.144.50.145:80
3.231.143.27:80
52.84.106.63:80
52.84.106.94:80
52.84.106.50:80
52.84.106.7:80
3.231.143.26:80
3.231.143.15:80
3.231.143.13:80
52.84.106.95:80
52.84.106.87:80
18.155.153.59:80
18.155.153.57:80
18.155.153.49:80
18..155.153.121:80
18.155.153.121:80
18.155.145.49:80
18.155.145.30:80
```
