# imapsync_ruby

This is a small program that will help copy messages from one IMAP folder to another, even across servers. It makes it really easy for example to migrate from one gmail account to another, and it has also been tested with many different IMAP servers.

**USE AT YOUR OWN RISK.**

# Instructions

1. Open up the imapsync.rb file and edit lines 6 - 19 as needed.
1. You will need to provide a host name, user name, and password for the source account and the destination account.
1. You can optionally change the UID\_BLOCK\_SIZE if necessary.

# Thanks

A big thanks to [wonko.com](http://wonko.com/post/ruby_script_to_sync_email_from_any_imap_server_to_gmail) for creating the script and publishing it. Thank you also to the many contributors and testers in the comments of that post who made this script work even better.