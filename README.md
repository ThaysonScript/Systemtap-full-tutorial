# Systemtap-full-tutorial

## Source guide
https://sourceware.org/systemtap/

## Systemtap Install Guide for Debian
### Running in Root User

```bash
apt install systemtap linux-headers-$(uname -r)
```
now
```bash
apt install systemtap linux-image-$(uname -r)-dbg
```

## Try out this hello world one-liner:
```stap
stap -v -e 'probe oneshot {println("hello world") }'
```

## Other Docs
https://pt.slideshare.net/tchelinux/introduo-ao-systemtap-joo-avelino-bellomo-filho-tchelinux-caxias-2018

## Help Others
https://wiki.debian.org/SystemTap