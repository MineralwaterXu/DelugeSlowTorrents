# DelugeSlowTorrents
Automatically delete slow torrents in deluge!

I left the code easily modifiable, I also capture most of the deluge-console info output and parsed it into a hash structure for future projects.

**$average** is in MiB/s

**$time** is in minutes.

You'll need to change both of those. Also, you will need to change the connect strings to suit your environment.

from
https://www.reddit.com/r/seedboxes/comments/b37h8k/scripthowto_automatically_delete_slow_torrents/


After making the required changes to the deluge-connect strings, you can run it like this:

1. Create a screen (ex: screen -dmS cleaner)
2. Go to that screen (ex: screen -r cleaner)
3. perl cleaner.pl
