# PrintHub launcher (GitHub Pages)

Deploy these two files to the root of the `r4p5.github.io` repository (or any GitHub Pages site).
`404.html` is identical to `index.html` so every `/<mobile-number>` path is handled without
creating per-shop files.

Shop QR codes look like `https://r4p5.github.io/9066191970#h=192.168.1.10:3000`. The page
validates the number and the private LAN address, remembers it per shop, and forwards the
browser to `http://192.168.1.10:3000/?shop=9066191970`, which the shop's PrintHub app serves.
