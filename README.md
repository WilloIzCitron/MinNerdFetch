# NerdFetch
 A Minimal POSIX \*nix (Linux, macOS, Android, \*BSD, etc) fetch script using Nerdfonts

<!-- ![Screenshot](https://i.imgur.com/and9kuQ.png) -->
![Screenshot](https://linus-sex.tips/YaceZlOLdx.png)

### Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- Anything but Windows

### To install and run:

#### Install with package manager:

unfortunately i didnt upload to package manager :sad:, i need maintainer for maintain it

#### Manually:

Copy-paste this into your terminal:

```sh
sudo curl -fsSL https://raw.githubusercontent.com/WilloIzCitron/MinNerdFetch/master/minnerdfetch -o /usr/bin/minnerdfetch
sudo chmod +x /usr/bin/minnerdfetch
minnerdfetch
```

#### Android with Termux:

Copy-paste this into Termux:

```sh
curl -fsSL https://raw.githubusercontent.com/WilloIzCitron/MinNerdFetch/master/nerdfetch -o /data/data/com.termux/files/usr/bin/nerdfetch
chmod a+x /data/data/com.termux/files/usr/bin/nerdfetch
nerdfetch
```

#### Run once:

Note that this will ***not*** install the program.
```sh
curl -fsSL https://raw.githubusercontent.com/WilloIzCitron/MinNerdFetch/master/minnerdfetch | sh
```

### Features:
- Strong cross-OS compatability
- Not bloated
- Minimal
- Portable
- POSIX

### TO DO:
- [ ] complete nerd font os icon

### OSes supported:
- Debian based Linux
- Ubuntu based Linux
- Arch based Linux
- RedHat based Linux
- SUSE based Linux
- Bedrock Linux
- Alpine Linux
- KISS Linux
- Void Linux
- Gentoo Linux
- Exherbo Linux
- NixOS Linux
- Solus Linux
- yiffOS Linux
- Slackware Linux\*
- macOS 10.x + 11.x
- Android

### Known issues:
- \*In Slackware Linux, make sure to have `/usr/sbin` in PATH
- In FreeBSD, no hostname and no uptime
- In OpenBSD, no hostname and no uptime, and no package count
