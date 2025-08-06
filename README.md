# keenetic-routes

Keenetic devices support [static routing](https://support.keenetic.ru/eaeu/ultra/kn-1811/en/15880-static-routing.html), which allows for manually directing network traffic through a designated gateway or interface (very useful for implementing split tunneling).

Instead of configuring each route individually, Keenetic allows for bulk import of routes using a batch file. This repository contains .bat files that specify the subnets and IP addresses for various online services.