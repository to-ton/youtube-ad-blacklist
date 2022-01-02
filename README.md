
# youtube-ad-blacklist
youtube *.googlevideo.com blacklist. fetched timely.

+The list above combined by the following regex below filter out most youtube ads to date.
```
/^https?:\/\/r[12]?\d---sn-\w{8}(?:\w{3}-\w{4})?\.googlevideo\.com(?:\/|:|$)/

@@/^https?:\/\/r[12]?\d---sn-2xouxaxq5u5-5cx\w\.googlevideo\.com(?:\/|:|$)/

^r[0-9]*([-]{1,3}|.)sn-[a-z0-9]{4,}-[a-z0-9]{4,}\.googlevideo	

/^https?:\/\/rr[12]?\d---sn-\w{8}(?:\w{3}-\w{4})?\.googlevideo\.com(?:\/|:|$)/

^rr[0-9]*([-]{1,3}|.)sn-[a-z0-9]{4,}-[a-z0-9]{4,}\.googlevideo	
```
