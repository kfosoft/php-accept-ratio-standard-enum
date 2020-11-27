# Standard of accept ratio enum for PHP  
## Installation

Installation with Composer

Either run
~~~
    php composer.phar require kfosoft/php-accept-ratio-standard-enum:"*"
~~~
or add in composer.json
~~~
    "require": {
            ...
            "kfosoft/php-accept-ratio-standard-enum":"*"
    }
~~~

Well done!

API
-------------
    getResolutions             - Get standard resolutions.
    getAcceptRatio             - Get standard accept ratio.
    getAcceptRatioByResolution - Get accept ratio of resolution.
    getResolutionByAcceptRatio - Get resolutions of accept ratio.

#### Example 1
~~~
use KFOSOFT\Domain\Display\Enumeration\StandardAcceptRatio;

var_dump(StandardAcceptRatio::getAcceptRatioByResolution('1366x768'));  
~~~

##### Result
~~~
string(4) "16:9"
~~~
Enjoy, guys!
