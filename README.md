Get Firefox Button
----------------------

Displays a 'humble' recommendation for website visitors to download Mozilla Firefox if they aren't using it.

Place either version the following code anywhere you want the button to be rendered.

```javascript
JavaScript
<script>		
		if (navigator.userAgent.indexOf("Firefox") == -1) {
			document.writeln("<a class='getff' href='http://www.mozilla.org/en-US/firefox/new/' target='_blank'></a>");
		}
</script>
```

```php
PHP
<?php
if (preg_match('/\b Firefox \b/x', $_SERVER['HTTP_USER_AGENT']) != 1){
	echo = "<a href='http://www.mozilla.org/en-US/firefox/new/' class='getff' target='_blank'></a>";
}
?>
```

License
----------------------
Font : Michroma - SIL OPEN FONT LICENSE

-Jed Burke
