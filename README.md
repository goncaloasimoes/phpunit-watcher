# Automatically rerun PHPUnit tests when source code changes

Modification of code on https://github.com/spatie/phpunit-watcher for personal use.

Change was made so that after any number (1+) failed test notifications, only one sucessfull test notification is sent, until the code fails the tests again.
