# minify-js


```php
<?php
include('Minifier.php');

// Basic (default) usage.
$minifiedCode = Minifier::minify($js);

// Disable YUI style comment preservation.
$minifiedCode = Minifier::minify($js, array('flaggedComments' => false));
```

i try to use https://github.com/tedivm/JShrink but  i get some error with php so i had changed it and publishing it here to use 

refrence https://github.com/tedivm/JShrink 
