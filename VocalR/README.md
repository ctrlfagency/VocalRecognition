# VocalR Javascript Library
VocalR library is a library created to interact voice commands between you and your browser.
Some of the features :
* Multiples languages
* Easy to use
* search commands
* Licensed under GPL3

## How to use :
Includes the vocalR.js script on the top of your webpage. 
```sh
<script src="vocalR.js"></script>

```
Create your own javascript functions.. 
Such as 
```sh			
			function bonjour () 	{
					alert("Tout va bien ?");
						};
			function tqui (searchtag) 	{
					dit_qui = searchtag.split(" ");
					alert('bonjour '+dit_qui[0]);
						};


```
and add them into the  VocalR_obj_functions.
```sh
			var VocalR_obj_functions = {
				bonjour:  "bonjour ",
				VocalR_obj_functions_S : { tqui:	"je suis "}
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



  

