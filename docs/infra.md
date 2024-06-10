# Door access - register a new user

1. create a new user on the UDM Pro and put the new user in the Hackerspace Members group
2. click the button to register an NFC tag, and swipe it on the correct reader when the system tells you to do. This can be done either locally (gateway IP) or through the remote control panel (https://unifi.ui.com). Data is stored locally, and it doesn't need internet or a cloud service to work.

It's fail open for fire safety because we do not have any other way to exit. 

# Doorbell

Very straightforward implementation:

* A `ring the bell` button on [https://hackerspace.gent/landing/contact.php](https://hackerspace.gent/landing/contact.php) that writes a file on disk containing a timestamp
* A cronjob on the Pi (pi@10.51.3.195) that is connected to the flappers that checks every x amount of seconds if a new file is written
* When an updated timestamp if found, instruct the flappers

# Drinks

An overview of ClubMate sellers: [https://lite.framacalc.org/hs-gent-clubmate-2024](https://lite.framacalc.org/hs-gent-clubmate-2024)
