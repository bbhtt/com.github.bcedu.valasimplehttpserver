# VServer


VServer opens an http server in the desired folder. Very usefull to share files in a easy and fast way.
Do you have a film in the computer and you want to watch it on the mobile phone? Just start Vserver in you computer and go to the given link with the mobile phone, you will have the film right there!

<ul>
<li>Start an http server through a clean and minimalist gui.</li>
<li>Use the command line options to start an http server through the console (type "com.github.bcedu.valasimplehttpserver --help" to learn more).</li>
<li>Choose the port where vserver listens through the gui.</li>
</ul>


VServer is "inspired" in the well known python SimpleHTTPServer.


## Installation

### Install .deb file

Comming soon.

### Elementary App Store

Download VServer through the elementary app store. It's always updated to lastest version.
Easy and fast.

### Manual Instalation

You will need the following packages, that can be installed through apt:
- gobject-2.0
- glib-2.0
- gtk+-3.0
- granite
- gee-0.8
- libsoup-2.4

Download last release (zip file), extract files and enter to the folder where they where extracted.

Install your application with the following commands:
- meson build --prefix=/usr
- cd build
- ninja
- sudo ninja install

DO NOT DELETE FILES AFTER MANUAL INSTALLATION, THEY ARE NEEDED DURING UNINSTALL PROCESS

To uninstall type from de build folder:
- sudo ninja uninstall

