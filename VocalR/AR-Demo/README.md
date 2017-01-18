# VocalR Javascript Library (Arabic Demo)
VocalR library is a library created to interact voice commands between you and your browser.
Some of the features :
* Multiples languages
* Easy to use
* search commands
* Licensed under GPL3

## How to use (In Arabic) :
Change the value  **VocalR_obj.lang** into the vocalR.js file. IE :
```sh
VocalR_obj.lang = "ar-MA";

```

Includes the vocalR.js script on the top of your webpage. 
```sh
<script src="vocalR.js"></script>

```
Create your own javascript functions.. 
Such as 
```sh			
			function bonjour () 	{
					alert("و عليكم السلام");
						};
			function tqui (searchtag){
					dit_qui = searchtag.split(" ");
					alert('مرحبا '+dit_qui[0]);
						};
```
and add them into the  VocalR_obj_functions.
```sh
			var VocalR_obj_functions = {
				bonjour:  	"السلام عليكم",
				stop:			"قاف",
				VocalR_obj_functions_S : { 
					tqui:	"اسمي "
									}
								};
```
Thats all folks..
## License
(c) Thibaut Marie Pierre LOMBARD
GNU - GPL3
General Public License V3

## contact
Feel free to contact me for a partnership, a job opportunity, i am currently open to most of coding proposals at **contact@ctrlfagency.com**.

[comment]: #



  

