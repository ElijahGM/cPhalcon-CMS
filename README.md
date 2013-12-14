cPhalcon-CMS
============

This is a proposal to come up with a complete CMS based on CPhalcon Framework
There is an existing CMS based on cPhalcon but coming up with another robust CMS with lean database schema is our priority


Structure
================================================================================
The folder structure below is the propsed structure of the CMS
```html
<pre>
[app]
 [frontend]
	   [controllers]
	   [models]
	   [views]
	   Module.php
    
 [backend]
       [controllers]
	   [models]
	   [views]
	   Module.php  
 [plugins]
   [plugin1]
   [plugin..n]

 [modules]
   [module1]
        Module.php
	    [controllers]
	    [models]
	    [views]
	        (main layout is coming from here)
   [module2]
        Module.php
	    [controllers]
	    [models]
	    [views]
	        (main layout is coming from here)
 [views]
    (master main layout should come from here?)
 [public]
    [css]
    [js]
    [images]

	[themes]
	     [theme1]
	     [theme..n]

</pre>

The folder structure is borrowed heavily from various leading frameworks Such as yii
The main reason we need to maintain the above structure is for developer who will be migrating to use our CMS to find it easier to use
