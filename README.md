ORIGINAL PROGRAM BY DIGITALARC, This is merely a custom build I made for myself.

All I've really done is strip out the Cloud related stuff as I don't use it, and renamed a few items.

For contributions please see the original project @ https://gitlab.com/digitalarc/guardian


## Guardian
Simple custom firewall used for the game GTA5

- [Requirements](#requirements)
  - [System](#system)
  - [Packages](#packages)
- [Build from source](#build-from-source)
- [Contributions](#contributions)
- [Changelog](CHANGELOG.md)
- [License](LICENSE)

## Requirements
#### System
- Python 3.6+ 64 bit
- Windows Vista/7/8/10 or Windows Server 2008 64 bit
- Administrator Privileges
#### Packages
- Unsure, this needs to be filled.

## Build from source
Run `make_exe.cmd` or
```
set TCL_LIBRARY=P:\Program Files (x86)\Python36\tcl\tcl8.6
set TK_LIBRARY=P:\Program Files (x86)\Python36\tcl\tk8.6
python setup.py build
```


Usage of software:

  Run Guardian.exe AS AN ADMINISTRATOR

    Solo Session
    Blocks everyone from joining, until you turn it off.

    Leave Lobby
    Does the same thing but doesn't continue to block people once you use it.

    Whitelisted Session
    Only allows people you've allowed to join.

    Blacklist Session
    Blocks people you've blocked.

    Lock Lobby
    Grabs the IPs of everyone currently in the session, and blocks everyone else effectively making a private session right then and there.

    Kick by IP
    Grabs the IPs of everyone in the session and lets you choose to block a number at a time. Don't do more tha one person at a time if you're not the session host.

    Kick Unknowns
    Kicks everyone that's not in the whitelist. Dont use it if you're not session host. I never even touch it and might remove it from the next Custom build.

    Lists
    Custom/Whitelist
    This is where you configure the whitelist.

    Blacklist
    This is where you configure the blacklist.

        Select
        lets you enable/disable blocks
        Add
        lets you add peopl to the specific list
        List
        shows you the specific list and lets you edit/remove people.