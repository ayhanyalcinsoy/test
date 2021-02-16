# Pisi GNU/Linux

[![Telegram](https://img.shields.io/badge/Telegram-Pisi%20GNU%2FLinux-blue)](https://t.me/joinchat/DnOmFNS_KOjzEpnn)
[![Forum](https://img.shields.io/badge/Forum-Pisi%20GNU%2FLinux-orange)](https://www.pisilinux.org/forum)
[![Website](https://img.shields.io/badge/Website-Pisi%20GNU%2FLinux-green)](https://www.pisilinux.org/)

**Özgürlük Şimdi Başladı**
Pisi GNU/Linux; Pisi tabanlı son Pardus sürümünü temel alan, özgür yazılım topluluğu tarafından geliştirilen, bilgisayar kullanıcılarına kurulum, yapılandırma ve kullanım konusunda kolaylık sağlamaya çalışan, onların temel masaüstü gereksinimlerini karşılamayı amaçlayan, son kullanıcı odaklı bir GNU/Linux dağıtımıdır.

![](https://www.pisilinux.org/upload/slider/__slider-pisi211-banner.jpg)

## Özellikleri

*Son kullanıcı odaklı bir GNU/Linux dağıtımıdır.
*Kullanıcılarına Linux deneyimlerini olabildiğince özgür ve grafik arayüz kullanarak yaşamalarını sağlamayı amaçlar.
*Devraldığı tasarıları geliştirmeyi, yeni tasarıların gelişmesini sağlayarak özgür yazılım dünyasına katkıda bulunmayı amaçlar.
*Sunucu ya da Kurumsal sürüm çıkarmayı düşünmemektedir.
*Şimdilik yalnızca x86-64 mimarisini destekler.
*1, 2, 3 şeklinde süren bir ana sürüm ve 1.1, 1.2, 1.3 şeklinde süren ara sürüm adlandırılmasını kullanır.
*Güncel ve kararlı uygulamalar sunar.

## Web Sayfası

Daha fazla bilgi için web sayfamızı ziyaret edebilirsiniz https://collaboraonline.github.io/

## Kullanıcı Desteği
Telegram kanalından karşılaştığınız sorunlarla ilgili bilgi alabilirsiniz.[Telegram](https://t.me/joinchat/DnOmFNS_KOjzEpnn)

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
