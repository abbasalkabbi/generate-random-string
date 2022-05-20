# generate-random-string
### this is my first Package in Php 

generate-random-string 

[Link in Composer](https://packagist.org/packages/developer_abbas/generate-random-string)
## Getting Started
1.composer require 
```sh
   composer require developer_abbas/generate-random-string
   ```
   2. Create index.php
   3. in index.php Write this
```sh
<?php 
require_once __DIR__ . '/vendor/autoload.php';


$myG= new \Generator\StringGenerate();
echo $myG->generate(100);

?>
   ```
