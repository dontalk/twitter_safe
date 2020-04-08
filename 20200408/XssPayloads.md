##User: XssPayloads	Time: 20200408
> 
 New XSS challenge by @SecurityMB
 https://securitymb.github.io/xss/2/?xss=null 

> 
 Some more JS tricks by @aemkei...
$=[...Object.keys(Error)[0]]
[object Array]: ["s", "t", "a", "c", "k", "T", "r", "a", "c", "e", "L", "i", "m", "i", "t"]

Some more letters available for your payload obfuscation...

> 
 alert(1) obfuscation by @aemkei 
Object.values(this)[145].call(this, +!0);

Note from the author: This works in Chrome 80 but the index (145) of "alert" in windows might be different in other versions or browsers.

