# Switch Hosts

A simple hosts file switcher using hosts files from [https://github.com/StevenBlack/hosts](https://github.com/StevenBlack/hosts).

## Installation

```
$ git clone https://github.com/unforswearing/switch-hosts.git .
$ cd switch-hosts && source switchhosts
```

Or install with [basher](https://github.com/basherpm/basher)

```
$ basher install unforswearing/switch-hosts
$ include unforswearing/switch-hosts switchhosts
```


## Usage

```
hosts [clear|list|allow|restore|schedule|switch|update] [default|loose]
```

*Warning*

As noted in "Usage" above, the function in `switchhosts` is called `hosts` which may collide with the `host` command at `/usr/bin/host` on Macos.


## To Do

May eventually rewrite this in a more useful language (Python)