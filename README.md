<div align="center">

## IIS Redirects


</div>

### Description

A REAL TIME SAVER

I felt the need to do this bcause i had a huge bundle of asp scripts all containing tags like <img src = "anyimage.gif">. now as a cumpulsory requirement all images were to be stored in a diff directory ( ../images/ )(earlier it was in the same folder as the asp scripts)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Pulsar180](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/pulsar180.md)
**Level**          |Beginner
**User Rating**    |2.8 (11 globes from 4 users)
**Compatibility**  |ASP \(Active Server Pages\), HTML, VbScript \(browser/client side\)

**Category**       |[Server Side](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/server-side__4-31.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/pulsar180-iis-redirects__4-7819/archive/master.zip)





### Source Code

```
suppose this is the new directory structure
wwroot
|--------asp
      |----- *.asp
|--------images
      |------*.gif
I didnt want to go thru ASP scripts and change every img tag. neither could i use PERL or any Reg Exp trick .. as the img tag was being scripted sometimes.
so i wanted a way for IIS to recognize all content-type images/gif references to the ASP folder be now searched in that folder or the ../images folder.
well it turned out simpler
see the screenshot
all it needs is to give an IIS redirections
use wild cards
wwroot/IIShelp.asp has more on that
i have made submissions bfore .. but i think u can vote for this one
```

