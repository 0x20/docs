# Infra

## Doorbell

Very straightforward implementation:

* A `ring the bell` button on [https://hackerspace.gent/landing/contact.php](https://hackerspace.gent/landing/contact.php) that writes a file on disk containing a timestamp
* A cronjob on the Pi (pi@10.51.3.195) that is connected to the flappers that checks every x amount of seconds if a new file is written
* When an updated timestamp if found, instruct the flappers

## Drinks

An overview of ClubMate sellers: [https://lite.framacalc.org/hs-gent-clubmate-2024](https://lite.framacalc.org/hs-gent-clubmate-2024)

## 2D Printer

A Samsung M4020nd printer is available in the space (donated by TQ and Johan for the printer).
DNS: `hsgprinter.lan.0x20.be`
#### MacOS
`Settings -> Printer -> Add printer -> Samsung M332x 382x 402x Series (SEC30CDA71FA048)`
#### Ubuntu
`Printers -> magic happens -> it's already there`

## 3D Printers

### Bambulab mini

This printer is property of mateo and miker, but free to use if you know
what you're doing (if not, ask help).

The printer is configured in LAN-only mode, and can be accessed on the network
via OrcaSlicer software. Install the proprietary network plugin, click on
Devices, click on add printer and you should see the bambulab in the network.

DNS: bambu-mini.lan.0x20.be


## Stadsmakers

There is an internal website used by Stadsmakers with info for the coop's. See the `SpaceMembers` mattermost channel info header to find the link. Not posting the link here as it contains private data.
