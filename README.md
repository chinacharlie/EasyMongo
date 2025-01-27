# EasyMongo [中文版说明](./README_CN.md)
EasyMongo is a Mongodb web management application. This project is based on [iwind/RockMongo](https://github.com/iwind/rockmongo), uses the latest mongodb extension + phplib mode, supports Mongodb3.0+, and all versions above php5.6.

## Installation
Make sure that the mongodb extension is installed, then execute the following command:
~~~
$ git clone https://github.com/pkuoliver/EasyMongo.git
~~~
Install mongodb php library with [Composer](https://getcomposer.org/)
~~~
$ composer require mongodb/mongodb
~~~
Prepare config file.
~~~
$ cp config.sample.php config.php
~~~
Modify the database host/port and other related configurations to your own information.

## Thanks
[Liu Xiaochao/iwind](https://github.com/iwind)

[lxp_kidd/lxphelloworld](https://github.com/lxphelloworld)