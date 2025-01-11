# 3x-ui-auto_add_ssl

Bash script to execute after 3x-ui installation to automatically add self-signed SSL cert for the admin panel

## WARNING
  This script is intended to be ran only once on a VPS that has freshly-configured 3x-ui panel that has no SSL certificates set.

## How to use

1. Run after installation of 3x-ui panel

```
bash <(curl -Ls https://github.com/SibMan54/3x-ui-auto_add_ssl/blob/22ac3e9b2bbfd8b21d5da7367d2586b2bd75cd26/3x-ui-autossl.sh)
```
2. Restart the panel

