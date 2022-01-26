## Installation

Install the latest version with

```shell
composer require artox-lab/example-protobuf-messages
```

## Basic usage

```php
<?php

require_once 'vendor/autoload.php';

$message = new \ArtoxLab\ExampleMessage\V1\Order\Created();
$message->setId('f0ec71ed-fcc5-47bd-9389-a9640e890f3d');
```
