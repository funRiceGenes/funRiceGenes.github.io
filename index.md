---
layout: page
title: Welcome to funRiceGenes!
tagline: 
---

<head>
<meta name="referrer" content="origin">
</head>

__A comprehensive database of functionally characterized rice genes__


* 2800+ cloned rice genes [[Download↓]](https://funricegenes.github.io/geneInfo.table.txt)  
* 400+ gene families [[Download↓]](https://funricegenes.github.io/famInfo.table.txt)  
* 400+ keywords [[Download↓]](https://funricegenes.github.io/geneKeyword.table.txt)  
* 4800+ literatures [[Download↓]](https://funricegenes.github.io/reference.table.txt)  
* 200+ interaction networks [[Download↓]](https://funricegenes.github.io/net.pdf)  
* Contact: ywhzau at gmail.com   
* Help manual [[Download↓]](https://funricegenes.github.io/help.pdf)  


<br>
<form action="{{ page.url | relative_url }}">
  <div class="tipue_search_left"><img src="{{ "/assets/tipuesearch/search.png" | relative_url }}" class="tipue_search_icon"></div>
  <div class="tipue_search_right"><input type="text" name="q" id="tipue_search_input" pattern=".{3,}" title="At least 3 characters" required></div>
  <div style="clear: both;"></div>
</form>

<div id="tipue_search_content"></div>

<script>
$(document).ready(function() {
  $('#tipue_search_input').tipuesearch();
});
</script>

  
<br>
__To interactively query this database, go to the following site!__  
[<img src="https://funricegenes.github.io/images/shiny.png" alt="Dynamic query of this database"  style="width: 600px;"/>](http://funricegenes.ncpgr.cn)   


<br>
__If you find any error information in our database or any functionally characterized rice genes missing from our database, please leave us a message.__
<form action="http://formspree.io/venyao@qq.com" method="POST" class="dark-matter">
<label>
<span>Your Email :</span>
<input id="email" type="email" name="email" placeholder="Valid Email Address" />
</label>
<label>
<span>Message :</span>
<textarea id="message" name="message" placeholder="Your Message to Us"></textarea>
</label>
<label>
<span>&nbsp;</span>
<button type="submit" class="button">Send</button>
</label>
</form>


<br>
__If you use the data in this database, please cite [our website](https://funricegenes.github.io/) for now.__
