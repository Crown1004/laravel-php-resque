laravel-php-resque
=============================

##Запуск тестов из под workbench

./vendor/bin/phpunit workbench/kodeks/php-resque/tests/LogOutputTest

./vendor/bin/phpunit workbench/kodeks/php-resque/tests/ResqueQueueTest

./vendor/bin/phpunit workbench/kodeks/php-resque/tests/ListenCommandTest

./vendor/bin/phpunit workbench/kodeks/php-resque/tests/StopCommandTest

./vendor/bin/phpunit workbench/kodeks/php-resque/tests/PauseResumeCommandTest

./vendor/bin/phpunit workbench/kodeks/php-resque/tests/RestartCommandTest


##Installation

in **composer.json**:
>```
"require": {
		...
                "kodeks/php-resque": "dev-master"
	}
```
