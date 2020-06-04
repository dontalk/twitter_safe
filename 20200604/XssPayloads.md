##User: XssPayloads	Time: 20200604
> 
``` A simple way to find 'on.*' event handlers by @airispoison 
Object.getOwnPropertyNames(window).filter(function(x){return x.startsWith('on')})```
  
  