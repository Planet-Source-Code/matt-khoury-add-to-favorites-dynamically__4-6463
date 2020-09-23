<div align="center">

## Add to Favorites \- Dynamically\!


</div>

### Description

After searching throughout the web for a JavaScript function that would add a web page to a users favorites folder, I grew increasingly impatient with the laziness of others code, (hey why re-create the wheel?) because others code only lets you add one page to a users favorites folder. Therefore, I created a DYNAMIC &#8220;Add to Favorites&#8221; function, that for example will add the web page where the code is located to the users favorites. Just create an include virtual, (for script) and insert the include onto all of your pages, or preferably if you have a header page include, just copy the code into that &#8211; and Voila! As long as you have the TITLE tags on your page, you&#8217;re set!
 
### More Info
 
None, the code is very generic, so just copy the code as is.

You MUST have TITLE tags on your web pages! Also, make sure the TITLE tags are ABOVE your start JavaScript tag.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Matt Khoury](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/matt-khoury.md)
**Level**          |Intermediate
**User Rating**    |4.4 (66 globes from 15 users)
**Compatibility**  |ASP \(Active Server Pages\), HTML, VbScript \(browser/client side\)

**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__4-9.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/matt-khoury-add-to-favorites-dynamically__4-6463/archive/master.zip)





### Source Code

```
<HTML>
 <HEAD>
 <TITLE>ADD To Favs</TITLE>
 <SCRIPT language="JavaScript1.2">
 	var bookmarkurl = window.location.href;
 	var bookmarktitle = document.title;
 	function addfav(){
 	if (document.all) window.external.AddFavorite(bookmarkurl,bookmarktitle);
 	}
 </SCRIPT>
 </HEAD>
 	<BODY>
 		<A href="javascript:addfav()">Add page To favorites</A>
 	</BODY>
 </HTML>
```

