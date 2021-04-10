---
layout: post
title: Impresi DDE Ubuntu
date: 2021-04-09 03:22:34
categories: resensi
---
<p>Pertama kali makek, wow. Gue dapat menikmati keanggunan Ubuntu Deepin dengan backingan Linux Mint, wkwkwk. Overall, memuaskan, kalo elo tertarik buat nyoba, berikut caranya …</p><p>, tambahkan repositori dulu dari Deepin</p><p>$ sudo add-apt-repository ppa:ubuntudde-dev/stable</p><p>$ sudo apt-get update</p><p>Kemudian install makek&nbsp;</p><p>$ sudo apt install ubuntudde-dde</p><p>install file ekstra-nya,</p><p>$ sudo apt install ubuntudde-dde-extras</p><p>Kalo elo makek Linux Mint, udah makek LightDM untuk display manager-nya, tapi kalo Ubuntu, biasanya makek GDM atau Gnome Display Manager harus dikonfigurasi dulu makek&nbsp;</p><p>$ sudo dpkg-reconfigure gdm</p><p>terus dipilih LightDM</p><p>Kalo misal ada error, kayak dkms-nya gak cocok, coba gini</p><p>$ wget <a href="http://ppa.launchpad.net/ubuntudde-dev/stable/ubuntu/pool/main/d/deepin-anything/deepin-anything-dkms_5.0.1-7_all.deb">http://ppa.launchpad.net/ubuntudde-dev/stable/ubuntu/pool/main/d/deepin-anything/deepin-anything-dkms_5.0.1-7_all.deb</a></p><p>$ sudo dpkg -i deepin*.deb</p><p>Selesaiii …</p><p>&nbsp;</p>
