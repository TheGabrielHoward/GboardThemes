# Gboard Themes
 ![Google Phone](https://img.shields.io/badge/Android-Lollipop+-blue.svg?logo=google&longCache=true&style=flat-square)
 ![Magisk](https://img.shields.io/badge/Magisk-17%2B-00B39B.svg?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAABg1BMVEUAAAD9/f39/f39p4v9o4UuP6L/ckT/ckMmPaWYgbj/bxb/bhybg7j4usj4usj6u8j6u8gyMTIyMTExMTExMTExMTEoLCsmKikxMTH////////9/f39/f39/f39/f39/f0xMTExMTExMTExMTH9///9vEP9sif9sif9vEP9///9km/9+/z95Lb9siX9siX95bj9+vz9i2b+bDv+xbP9+/P9tCv9tCv9/PT+xLH+bDu+YF/wdlX/5Nf9vEH9vUL/49fwdVS9YGD//+OFdrVPSpltYaHqs1TpslZtYaFPSpqGdrX//+T/1M/vtcaag7pkYrO4i1K3i1RkYrObg7rwtcf/1dAAAADmrrn/v8t4YWMwMC8wMC96Y2T/v8vmrrkAAAAhJiVIQUJXSk1BQUFPT09UVFVERERYTE5IQUIiJyYIDAuam5vm5uZjY2NoaGjm5uaZmpoBBAT///////9jY2Nqamr///////////9TU1NWVlb///8xMTExMTExMTExMTH///9CFnTpAAAAgHRSTlMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABEhQUEgEGcYqWlotvBVG3qbSzqrZPYq6ImpqIrmEDdsaZZmWaxnUDA5DGjiwskMaPAgVpuGiNjGa4aAUHRoerc3Wuh0UHCV2xrK65XAkZoLSylhIXeWoRIBgAAPXwkEAAAAABYktHRBnsbrWIAAAACXBIWXMAAAuJAAALiQE3ycutAAAAB3RJTUUH4gwCFTA4FQjaVQAAAKRJREFUCNdjYMAAjCqqauoamkwQHrOWto6unr6BIQuIx8pmZGxiamZuYcnOAeRycllZ29ja2Ts4cvMAubxOzi6ubu4enl7efEAuv4+vn39AYFBwSKgAkCsYFh4RGRUdExsXLwTkCickJiWnpKalZ2SKALmiYlnZObl5+QWF4hIgmySliopLSsvKJaGukpapqKyqlpWDuVJeoaZWEcnVSnX1ymAGAJVTH9o8hgBiAAAAJXRFWHRkYXRlOmNyZWF0ZQAyMDE4LTEyLTAyVDIxOjQ4OjU2LTA1OjAwAAhnNAAAACV0RVh0ZGF0ZTptb2RpZnkAMjAxOC0xMi0wMlQyMTo0ODo1Ni0wNTowMHFV34gAAAAASUVORK5CYII=)
## Table of contents
- [Description](#description)
- [How does it work?](#how-does-it-work)
- [Themes](#themes)
- [Pro Tips](#pro-tips)
- [Credits](#credits)

## Description
Gboard Themes is a Magisk module with themes invented trough modifying the only third party Gboard theme –  Material 2 theme, windows theme, ios theme...

## How does it work?
The module modifies two of your system props to map the theme location and adds a folder (/system/etc/gboard_themes) with actual themes inside.

## Themes
- Material Design 2
- Material Design 2 (AOSP)
- Material Design 2 (Ocean)
- Material Design 2 (Orange-Yellow)
- Material Design 2 (Purple)
- Material Design 2 (BlueSky)
- Material Design 2 (Dark)
- Material Design 2 (Red Dark)
- Material Design 2 (Amoled)
- Material Design 2 (Amoled)(AOSP)
- Material Design 2 (Amoled)(Ocean)
- Neon Dark Blue
- Teal 2
- Windows old
- White very rounded
- IOS
- IOS Dark
- TWRP
- XDA Blue Light
- Oreo Cookies

## PRO TIPS

All to change is in **expconfig.xml** located on:
> /data/data/com.google.android.inputmethodlatin/shared_prefs/expconfig.xml

- You need to revoke wirte acces to shared_prefs folder
- After save changes to expconfigs.xml, force close Gboard App

### Colored Navbar
"themed_navbar_style"

Change the value from 0 to 3

### M2 Gboard Theme
 "enable_m2_horizontal_scroll"
 
 "enable_m2_theme"
 
 "enable_m2_for_non_default"
 
 "enable_m2_for_expression_headers"
 
 "enable_m2_for_search_cards"
 
 
set "false" to "true"

### Clipboard
"enable_clipboard"

set "false" to "true"

### Minimal Google Logo
"enable_monochrome_g_icon"

set "false" to "true"
#
## Credits
- [@RadekBledowski](https://github.com/RadekBledowski) for the orginal module
- [@topjohnwu](https://github.com/topjohnwu) for Magisk

[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/TheGabrielHoward)
