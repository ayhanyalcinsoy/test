# Pisi GNU/Linux

[![Telegram](https://img.shields.io/badge/Telegram-Pisi%20GNU%2FLinux-blue)](https://t.me/joinchat/DnOmFNS_KOjzEpnn)
[![Forum](https://img.shields.io/badge/Forum-Pisi%20GNU%2FLinux-orange)](https://www.pisilinux.org/forum)
[![Website](https://img.shields.io/badge/Website-Pisi%20GNU%2FLinux-green)](https://www.pisilinux.org/)

**Özgürlük Şimdi Başladı**

![](https://www.pisilinux.org/upload/slider/__slider-pisi211-banner.jpg)

## Key features
* View and edit text documents, spreadsheets, presentations & more
* Collaborative editing features
* Works in any modern browser – no plugin needed
* Open Source

## Website

For many more details, build instructions, downloads and more please visit https://collaboraonline.github.io/

## Developer assistance
Please ask your questions on `irc.freenode.net` in our `#cool-dev` channel

Join the conversation on our Discourse server at https://forum.collaboraonline.com/

Watch the tinderbox status (if it's green) at
https://cpci.cbg.collabora.co.uk:8080/view/Tinderbox/job/Tinderbox%20for%20online%20master/

## Development bits

This project has several components:
* **wsd/**
  * The Web Services Daemon - which accepts external connections
* **kit/**
  * The client which lives in its own chroot and renders documents
* **common/**
  * Shared code between these processes
* **loleaflet/**
  * The client side JavaScript component
* **test/**
  * C++ based unit tests
* **cypress_test/**
  * JavaScript based integration tests

## Further recommended reading with build details

Please consult the README files in the component's directory for more details:
- wsd/README
- loleaflet/README

## iOS and Android apps

See the corresponding READMEs:
* **ios/README**
* **android/README**
