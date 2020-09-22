<div align="center">

## Banner Rotator v2


</div>

### Description

This Script displays a different Banner each time your site is loaded.Took Me 5 minutes
 
### More Info
 
To change the ammount ao banners to display is very easy just change the "how many ads part" just look at it it fairly straight forward.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[C\.O\.T\.B\.S](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/c-o-t-b-s.md)
**Level**          |Intermediate
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/c-o-t-b-s-banner-rotator-v2__2-2037/archive/master.zip)





### Source Code

```
<script LANGUAGE="JavaScript">
<!-- Begin
var how_many_ads = 2;
var now = new Date()
var sec = now.getSeconds()
var ad = sec % how_many_ads;
ad +=1;
if (ad==1) {
txt="";
url="";
alt="";
banner="";
width="";
height="";
}
if (ad==2) {
txt="";
url="";
alt="";
banner="";
width="";
height="";
}
document.write('<center>');
document.write('<a href=\"' + url + '\" target=\"_top\">');
document.write('<img src=\"' + banner + '\" width=')
document.write(width + ' height=' + height + ' ');
document.write('alt=\"' + alt + '\" border=0><br>');
document.write('<small>' + txt + '</small></a>');
document.write('</center>');
// End -->
</script>
```

