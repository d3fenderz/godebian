# godebian

A simple Bash script to configure Debian-based Linux distros

                 _      _     _ 
  __ _  ___   __| | ___| |__ (_) __ _ _ __
 / _` |/ _ \ / _` |/ _ \ `_ \| |/ _` | `_ \
| (_| | (_) | (_| |  __/ |_) | | (_| | | | |
 \__, |\___/ \__,_|\___|_.__/|_|\__,_|_| |_|
 |___/


![](https://github.com/jmau111-org/golinux/raw/main/screenshot.png)

## How to use

```
git clone https://github.com/jmau111-org/godebian
sudo -s
cd godebian
bash godebian
```

## Opt out

You can either select "1" to proceed or "2" to skip a specific step.

## Why do I use the keyword `function`?

To prevent nasty collisions with existing aliases, as I use generic names.

## Warnings

Be careful. The script assumes you won't need many default configurations such as printers, FTP, telnet.

Fortunately, you can choose to opt out of some steps. Just choose "No" (type 2).

**I strongly encourage you to update && upgrade** to prevent bad errors and apply security patches.
