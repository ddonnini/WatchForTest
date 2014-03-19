WatchForTest
============

The script will listen to all php files' changes in a specific folder and execute a specific command.

Requirements
============

Install watchmedo (https://github.com/gorakhargosh/watchdog)

Create the script (for example in /usr/bin/watchfortest)

 #!/bin/sh

watchmedo shell-command --wait --recursive --patterns="*.php" --command="[ \${watch_event_type} = 'modified' ] && $1" $2


Usage
=====

watchfortest "phpunit" .
