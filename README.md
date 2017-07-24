# tldr-luk3yx

[![Snap Status](https://build.snapcraft.io/badge/luk3yx/tldr-luk3yx.svg)](https://build.snapcraft.io/user/luk3yx/tldr-luk3yx)

A simple bash tldr viewer.

This viewer **does not comply with the [recommended standards](https://github.com/tldr-pages/tldr/wiki/Minimum-specifications-for-TLDR-command-line-clients)**.

## What is tldr?
tldr is a collection of community-maintained simplified manpages. You can find out more [here](https://github.com/tldr-pages/tldr/blob/master/README.md).

## Can I view tldr manpages on [...]?
Possibly, you can find a list of other clients [on this page](https://github.com/tldr-pages/tldr/wiki/TLDR-clients).
Alternatively, use the 'find out more' link.

## How do I install this tldr client?

### Manually (on UNIX-based systems):
Download the 'tldr' file, mark it as executable, and copy it to somewhere in your path!
#### With sudo:
~~~
cd /tmp
git clone https://github.com/luk3yx/tldr-luk3yx.git
cd tldr-luk3yx
chmod 755 tldr
sudo cp tldr /usr/local/bin
~~~
#### With su:
~~~
su
cd /tmp
git clone https://github.com/luk3yx/tldr-luk3yx.git
cd tldr-luk3yx
chmod 755 tldr
sudo cp tldr /usr/local/bin
~~~

### As a snap (coming soon!):
If you have a compatible system, simply [click here](snap://tldr-luk3yx) to install. Alternatively, run the following commands in a terminal:
~~~
sudo snap install tldr-luk3yx
sudo snap alias tldr-luk3yx tldr
~~~
What is a snap? Find out [here](https://snapcraft.io).
