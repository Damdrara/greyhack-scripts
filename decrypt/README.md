# decrypt v1.1
An improved version of the game's `decipher` tool, allowing the user to not only decipher:

- a single credential line from a file (like the default tool)
- all the credential lines from a file
- a credential line given as parameter
- a password hash given as parameter

**Dependency:** `crypto.so`

![Example](https://github.com/Damdrara/greyhack-scripts/blob/main/decrypt/examples/decrypt-hash.png?raw=true)
![Example](https://github.com/Damdrara/greyhack-scripts/blob/main/decrypt/examples/decrypt-line.png?raw=true)
![Example](https://github.com/Damdrara/greyhack-scripts/blob/main/decrypt/examples/decrypt-passwd.png?raw=true)

## Updates
v1.1
- Fixes wrong command name in header and usage
- Prefers local `crypto.so` over `/lib/crypto.so` if available

v1.0
- Initial Release