##User: XssPayloads	Time: 20200611
> 
``` Unicode security guide, a most useful resource by @w3be
 https://bit.ly/3hdXXFs ```
  
  > 
``` An FF only event from @PortSwiggerRes cheatsheet:  https://portswigger.net/web-security/cross-site-scripting/cheat-sheet#onloadend …

<image src=validimage.png onloadend=alert(1)>```
  
  > 
``` Removing Referrer from your xml httprequests, a good tip by @Michael1026H1 

var meta = document.createElement('meta');
 http://meta.name  = "referrer";
meta.content = "no-referrer";
document.getElementsByTagName('head')[0].appendChild(meta);

// you xml httprequest here```
  
  