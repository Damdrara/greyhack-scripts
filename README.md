# greyhack-scripts

Scripts for the Game "Grey Hack". Grey Hack is a massively multiplayer hacking simulator game. You’re a hacker with full freedom to act as you wish on a vast network of procedurally generated computers.

https://greyhackgame.com

## binlist v1.1
Lists all the libraries, cli commands and gui apps on the current machine.

if `metaexploit.so` is found in `/lib` or the current directory, library versions will be listed as well.

**Optional dependency:** `metaxploit.so`

![Example](https://github.com/Damdrara/greyhack-scripts/blob/main/binlist/examples/binlist.png?raw=true)


## discover v1.0
Runs whois, nmap and scanrouter on a target ip

![Example](https://github.com/Damdrara/greyhack-scripts/blob/main/discover/examples/discover.png?raw=true)


## decrypt v2.0
An improved version of the game's `decipher` tool, allowing the user to not only decipher:

- a single credential line from a file (like the default tool)
- all the credential lines from a file
- a credential line given as parameter
- a password hash given as parameter

**Dependency:** `crypto.so`

![Example](https://github.com/Damdrara/greyhack-scripts/blob/main/decrypt/examples/decrypt-hash.png?raw=true)
![Example](https://github.com/Damdrara/greyhack-scripts/blob/main/decrypt/examples/decrypt-line.png?raw=true)
![Example](https://github.com/Damdrara/greyhack-scripts/blob/main/decrypt/examples/decrypt-passwd.png?raw=true)