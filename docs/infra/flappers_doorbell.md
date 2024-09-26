# Doorbell

Very straightforward implementation:

* A `ring the bell` button on [https://hackerspace.gent/landing/contact.php](https://hackerspace.gent/landing/contact.php) that writes a file on disk containing a timestamp
* A cronjob on the Pi (pi@10.51.3.195) that is connected to the flappers that checks every x amount of seconds if a new file is written
* When an updated timestamp if found, instruct the flappers

