# saver
Just a script to save YouTube links from a discord channel, nothing fancy.

# Usage

You need python3.5 and discord.py installed.

  ~~~ sh
  $ wget https://raw.githubusercontent.com/daedreth/saver/master/saver
  $ chmod +x saver
  $ sudo cp saver /usr/bin/saver
  $ saver <token> <server> <channel> <limit> <filename>
  ~~~

Your token can be retrieved from the client, just search for how to find it.
The server and channel names follow, these are case sensitive and in the event that they contain spaces, surround them with quotation marks.
The limit is a number of how many messages you want to go back, if you wanna log it all just use a huge number.
The filename is just any string, if you use "myFile" as the argument, the output will be named myFile.html, this is saver in your $HOME directory.


It also crashes once it's done, but don't worry, it worked.

# License
It's GPL-3, but it's just a little script.

Do what you must.
