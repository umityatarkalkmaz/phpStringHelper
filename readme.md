# Basic string cleaner
Delete special caracters and more hyphen and dots.

Usage example
```php
<?php
require 'path/to/stringhelper.php';
use UmitYatarkalkmaz\StringHelper;
$str = '-Special #@$String-';
$cleanString = StringHelper::cleanString($str);
echo $cleanString; //specialstring
```
