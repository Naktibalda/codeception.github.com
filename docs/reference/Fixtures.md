---
layout: doc
title: Fixtures - Codeception - Documentation
---


## Codeception\Util\Fixtures



Really basic class to store data in global array and use it in Cests/Tests.

{% highlight php %}

<?php
Fixtures::add('user1', ['name' => 'davert']);
Fixtures::get('user1');

?>

{% endhighlight %}



#### *public static* add($name, $data) 

[See source](https://github.com/Codeception/Codeception/blob/2.1/src/Codeception/Util/Fixtures.php#L20)

#### *public static* cleanup() 

[See source](https://github.com/Codeception/Codeception/blob/2.1/src/Codeception/Util/Fixtures.php#L34)

#### *public static* get($name) 

[See source](https://github.com/Codeception/Codeception/blob/2.1/src/Codeception/Util/Fixtures.php#L25)

<p>&nbsp;</p><div class="alert alert-warning">Reference is taken from the source code. <a href="https://github.com/Codeception/Codeception/blob/2.1/src/Codeception/Util/Fixtures.php">Help us to improve documentation. Edit module reference</a></div>
