# discord-update-skip
A simple bash script to fix Discord wanting to update to a version that isn't in the repos.


## Dependencies
 * bash
 * [jq](https://github.com/stedolan/jq)

## Installation
### The script is available on the AUR:
```sh
paru -S discord-update-skip-git
```
### On any Other Distro than Arch,
```sh
bash <(curl -sSL https://raw.githubusercontent.com/n3oney/discord-update-skip/stable/set-config.sh)
```

## Usage
To patch your Discord configuration, you can simply run the script.

```sh
discord-update-skip
```
If you are on any other Distro, it is automatically run by using the install script.

The script should work even if your Discord configuration hasn't yet been initialized. It should inform you about it if that's the case.

## Discord versions
This is the stable branch, which is for the stable Discord version.
Other versions:
 * [PTB](https://github.com/n3oney/discord-update-skip/tree/ptb)
 * [canary](https://github.com/n3oney/discord-update-skip/tree/canary)
