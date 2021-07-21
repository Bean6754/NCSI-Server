# Microsoft NCSI Server
An unofficial Microsoft NCSI web-server

This will fix that DNS/Enable Active Probing/Globe WiFi icon/WiFi Action Required issue!  ;)

## About

What is NCSI?
- From Wikipedia: [NCSI (Network Connectivity Status Indicator), an internet connection awareness protocol used in Microsoft's Windows operating systems](https://en.wikipedia.org/wiki/NCSI).

## How to
- Setup an IIS server by going to `Control Panel` -> `Programs and Features` -> `Turn Windows features on or off` -> Enable `Internet Information Services` with the defaults or your preferred options.

- Place the contents of `wwwroot` inside of `%systemdrive%\inetpub\wwwroot` or your other web-root folder.

- Copy `hosts` (or add the Microsoft NCSI domains host entry) to `%windir%\system32\drivers\etc\hosts` to reflect your new local Microsoft NCSI web-server.

### NOTE: This should also work with any other web-server as it only needs to serve static-content.
