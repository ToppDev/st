# st - simple terminal (suckless)

This is my fork of [st, the simple terminal](https://st.suckless.org/) emulator for X which sucks less.


# Requirements

In order to build st you need
- the `Xlib` header files
- the `libharfbuzz` build files


# Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st

```
sudo make clean install
```

# Patches applied

- [alpha](https://st.suckless.org/patches/alpha/)
- [anysize](https://st.suckless.org/patches/anysize/)
- [blinking cursor](https://st.suckless.org/patches/blinking_cursor/)
- [bold is not bright](https://st.suckless.org/patches/bold-is-not-bright/)
- [boxdraw](https://st.suckless.org/patches/boxdraw/)
- [desktopentry](https://st.suckless.org/patches/desktopentry/)
- [dynamic-cursor-color](https://st.suckless.org/patches/dynamic-cursor-color/)
- [font2](https://st.suckless.org/patches/font2/)
- [scrollback](https://st.suckless.org/patches/scrollback/)