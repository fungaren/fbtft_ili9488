# ili9488 support for fbtft driver

Apply the patch:

```bash
cd ~/linux
patch -p1 < ~/ili9488.patch
```

Revert the patch:

```bash
cd ~/linux
patch -Rp1 < ~/ili9488.patch
```

# Acknowledgement

- https://github.com/mahathug/linux_4.20/blob/master/fb_ili9488.patch
- https://github.com/birdtechstep/fbtft-4.14/blob/master/fb_ili9488.c
