# Bar
## Register a new user

Steps to create a new bar account for a new member:

1. Update the members.beancount file on [Github/0x20/tab-data/static/members.beancount](https://github.com/0x20/tab-data/blob/master/static/members.beancount)
2. **Important:** the membername is case-sensitive and has to start with an uppercase!
3. Add the new user and add mm_name to receive barbot Mattermost message for each transaction. [Example commit](https://github.com/0x20/tab-data/commit/a20cee70454b478addbb0c7481cba8d528829289)
4. Press the 'Sync' button on the bar display
5. The new account should be available on the very end of the list

## Switch the bar to/from event mode

  1. SSH in: ssh hsg@uberbarmaid.lan.0x20.be
  2. Edit config: sudo nano /etc/backtab.yml → set event_mode: true (or false)
  3. Restart: sudo systemctl restart backtab
  4. Press Sync on the bar terminal
  5. Check: Soda shows €2.50 in event mode, €1.50 normal

## SEPA QR code
Quick link to create a SEPA tx QR code (not payconiq): https://www.qr-code-generator.com/solutions/epc-qr-code/
