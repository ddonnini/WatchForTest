WatchForTest
============

The watchfortest script will listen to all changes to php files in a specific folder and execute a specific command.

Requirements
============

Watchdog (https://github.com/gorakhargosh/watchdog)

Usage
=====

Copy the script, for example, in /usr/bin/watchfortest

Then:

watchfortest "phpunit" .
