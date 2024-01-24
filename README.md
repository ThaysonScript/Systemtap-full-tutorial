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

## Help Others
https://wiki.debian.org/SystemTap