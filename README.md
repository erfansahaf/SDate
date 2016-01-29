# (S)hamsi (Date)

This is an easy php class that can convert ` Gregorian ` date to ` Jalali ` (Shamsi) date by using [JDate] (http://jdf.scr.ir/rahnama/?t=jdate) php functions
> You can use this class in Codeigniter and Native codes by following instruction

## Use in Codeigniter 3

for use in **Codeginiter 3** framework, you must copy SDate.php to `Application/libraries/SDate.php` path and push it into `$autoload['libraries']` array:

**application/config/autoload.php**
```php
$autoload['libraries'] = array("sdate");
```
also you can load this class in **your controller** instead autoload file
```php
$this->load->library('sdate');
```
after load the class, you can access to SDate public methods and jdate functions by following line
```php
$this->sdate->SOME_METHOD();
```
## Use in Native codes

It's very simple! just include SDate.php class and create an object from this:
```php
include 'SDate.php';

$sdate = new SDate();
$sdate->SOME_METHOD();
```

method details will be updating...
