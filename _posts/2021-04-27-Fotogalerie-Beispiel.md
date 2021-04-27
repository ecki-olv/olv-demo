---
title: "Fotogalerie Beispiel"
categories:
  - blog
tags:
  - galerie
  - beispiel
---

Freitag, 32. Mai 2021, Goldberghalle Ohrdruf


1. neues Album in Google Photos erstellen
2. Freigabe-Link für dieses Album erzeugen
3. https://www.publicalbum.org/blog/embedding-google-photos-albums - dort gibt es ein paar Tools, die mit Hilfe des Freigabelinks etwas HTML-Code erzeugen. Den kopiert man dann hier rein.
4. Beispiel:

<script src="https://cdn.jsdelivr.net/npm/publicalbum@latest/embed-ui.min.js" async></script>
<div class="pa-gallery-player-widget" style="width:640px; height:480px; display:none;"
  data-link="https://photos.app.goo.gl/pUPor91eJWB6XHYp7"
  data-title="OLV-Testalbum"
  data-description="6 new photos added to shared album">
  <object data="https://lh3.googleusercontent.com/EyYRX7X-1CyUEDWQLwrQixfu7CoMo-Xhq20TN9-DxJe6ycRXZA5RYjg07yGq3NoY6BkpueX_c14U3Xf6rffSf6QmEPZF0KytFvNfjTRtTujsD0Gfzmsg762sWv-AMde6ezicnSOB3gM=w1920-h1080"></object>
  <object data="https://lh3.googleusercontent.com/oleiCu1rKtLd9GhleTuewMxgy7gFGdPy2KXV225kNX2XpVzFn-YHn_jjO9wTMEQ9Hz_ETfFV3ajRw6CHAl6wzj_vk6Xi12KMK3jWk9xLmeS6ObhMUHhrJPEtVKOqcjyMlHeH0DmLeTg=w1920-h1080"></object>
  <object data="https://lh3.googleusercontent.com/Dimdr62Rvo3WOaqqJ9mBydE5qted48EyTd9JAQ4l2fWqgc2Vjjy4eqiM9kREvwh_XWi6nfcVsa4xBCzRPCLGhqC00LPmR-EowD3LmACNs2YahT6pRTwZSi-WDlJh-mO6U_kjXbJruXc=w1920-h1080"></object>
  <object data="https://lh3.googleusercontent.com/moy2bdBV03AZvWwDPPPaZs4mPy5uNFgKh3njSI2gYHntZAkiuKZrHlRmQgyLUlRlZgP9zfHdb6eoKYdldd0P4AahODdiq3_aAgjB-kwBvFhPkjFZEc4kH-SbSq5LuHmRlwDBayELxOg=w1920-h1080"></object>
  <object data="https://lh3.googleusercontent.com/Tb2E_VL4Zb0WuZvZOesl3awZlsxQKd5N6yODvTO19wzGMG4r4DJOzPZ8MI_ZeHR51rOAixVf2Q-CnbDQNRYP0yK0P7yXWDNTwJq9IBLd3tRAxbGq0wHiM5xnatKVi9iGJQeXbbHB7wQ=w1920-h1080"></object>
  <object data="https://lh3.googleusercontent.com/-SL9ejOVHfHS7uaDsSvptiR1-jU224PINojkwmA8TFuDjH1eLBWqr0rL56hxDN0wmiZMX4mBf7s34tZBoR2oBkMajRseFcniayasbOwdASwAxj2MRjq_fIstg-NEeg4lD0Y_m9Uqc3Y=w1920-h1080"></object>
</div>
