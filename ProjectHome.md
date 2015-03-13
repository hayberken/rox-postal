## Description ##

Yes, ROX needs another Mail Check applet!

None of the existing ones supported IMAP, and rather than hacking on one of those, I created my own.

Postal displays the results of checking your IMAP folders in a tooltip. Unseen (new) and total counts per folder are shown. Folders with no mail are suppressed.

Postal has options to support a single host and unlimited mailboxes. The port can be customized, but there is no support (yet) for SSL connections (I need to set up a server to test with first). The password is hidden from view, but at this point is stored in the options.xml file in plaintext (probably should use md5 or something here). The polling interval can be set in minute increments from 1 to 100.

Additionally, you can specifiy a mail client to be run when the applet icon is clicked.

## Status ##

003 (2006-10-03) Big rewrite to support POP and MBOX and multiple accounts.

002 (2006-01-17) Fixed small bug(s), Added sound event for new mail. Changed Icon.

## Requirements ##

  * ROX-Lib2
  * python