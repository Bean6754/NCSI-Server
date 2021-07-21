# Microsoft-NCSI
A Microsoft NCSI web-server

This will fix that DNS/Enable Active Probing/Globe WiFi icon/WiFi Action Required issue!  ;)

## How to
- Setup an IIS server by going to `Control Panel` -> `Programs and Features` -> `Turn Windows features on or off` -> Enable `Internet Information Services` with the defaults or your preferred options.

- Place the contents of `wwwroot` inside of `%systemdrive%\inetpub\wwwroot` or your other web-root folder.

- Copy `hosts` (or add the Microsoft NCSI domains host entry) to `%windir%\system32\drivers\etc\hosts` to reflect your new local Microsoft NCSI DNS server.

### This should also work with any other web-server as it only needs to serve static-content.
