WatchForTest
============
Everytime I want to test my code, I need to open a terminal, execute my phpunit command, modify stuff in my project, go back to the terminal and re-execute last command, TDD style! But what if something else can execute my test suite whenever I change something in my project?

And here we go. The watchfortest script will listen to all changes to php files in a specific folder and execute a specific command, for example our phpunit command!

Requirements
============
Watchdog (https://github.com/gorakhargosh/watchdog)

Copy the script in /usr/bin/watchfortest

```
sudo cp watchfortest /usr/bin/watchfortest
```

Usage
=====
```
watchfortest "phpunit" .
```

Owyeah.
