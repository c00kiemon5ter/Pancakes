Pancakes
========
Minimal IRC bot and logger in pure Bash.

- Owner can talk through it, sending data to the appropriate
  pipe created for each channel it connects to.
- Supports connections to multiple networks and channels.
- Dynamic configuration and adjust of commands.
- Can support different commands per channel or user.

Dependencies
------------
Only deps are Bash shell and coreutils
(`/bin/{mkdir,mkfifo,rm}`, `/usr/bin/{env,dirname}`)

Test it
-------
Connect to freenode network (_irc.freenode.net:6667_)
and join _#foss-aueb_ channel. Try `!list`. Have fun!

Proposed features
-----------------
- respond to queries
  requires setting up a new fd to talk back

Proposed commands
-----------------
- !all
  hilight everyone in the room

ToDo
----
- Documentation
- Webpage

License
-------

    ----------------------------------------------------------------------------
    "THE BEER-WARE LICENSE" (Revision 42):
     <ivan.kanak[at]gmail.com> wrote this file and scripts. As long as you retain
     this notice you can do whatever you want with this stuff. If we meet some
     day, and you think this stuff is worth it, you can buy me a beer in return,
        -- Ivan c00kiemon5ter V Kanakarakis
    ----------------------------------------------------------------------------

by [Ivan c00kiemon5ter Kanakarakis][blog] ~ <ivan.kanak[at]gmail.com>

  [blog]: http://c00kiemon5ter.github.com

