# YACo - Yes Another COlor !
Change background / color / border on scroll and more !

Just a simple and light background/color/border changer jQuery plugin.

![ScreenShot](http://rawgithub.com/tom4dev/YACo/gh-pages/logo.png)




[Just try it](http://tom4dev.github.io/YACo)


Author: Thomas Brodusch

Version
---------
1.0.0 - (9 november 2014)

Installation
-------------
> 1. Load **jQuery**
	
> 2. Load **YACo.js**

>``npm install yaco``

```html
	<script src="../src/jquery.yaco.js"></script>
```



> 3.Let **YACo do the rest !**
```html
<script type="text/javascript">
	// Default background-color change when scroll with nice random Flat colours !
		$(document).scroll(function(){
        	$('html').yaco();
        });
	// With some options on a specific element
			$('#anotherDiv').yaco({
				change: ['border','color'],
				colors: ['#3498db','#9b59b6','#34495e'],
				delay: '0.8s',
				transition: 'ease'
			});
	</script>
```


Options
-----------
> **change**: (array) - Apply the change on background/color/border 
			
>> (ex:['background', 'border'])
	
>**colors**: (array) - Pass the set of colors you want to use 
			
>>(ex: ['#1abc9c','#16a085','#3498db'])

>**excludes**: (array) - You want to excludes some colors
>>(ex: ['#1abcd4','#16a085'])

>**delay**: (float) 
>>(ex: 0.7)

>**transition**: (string) - Css transition 
>> (ex:'ease')

>**random**: (boolean) - You want a random set of colors ? Set it to true.
>>(ex: true)


	