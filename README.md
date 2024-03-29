# godebian

A simple Bash script to configure Debian-based Linux distros

![](https://github.com/d3fenderz/godebian/raw/main/screen.png)

## How to use

```
git clone https://github.com/d3fenderz/godebian
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
