# Vzdělávací středisko a hotel při VOŠ, SPŠ a SOŠ Varnsdorf

Toto je redesign webu Vzdělávacího střediska a hotelu při VOŠ, SPŠ a SOŠ Varnsdorf ve formě prezentace.

## HTML struktura

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ubytovani Varnsdorf VOS a SS</title>
  </head>
  <body>
    <div class="content">
      <img src="web.png" alt="stranka">
    </div>
  </body>
</html>
```
## CSS

```css
body {
  margin: 0;
  overflow-y: scroll;
}

.content {
  width: 100%;
  height: 100%;
}

img {
  width: 100%;
  height: auto;
  display: block;
  max-width: 100%;
}

@media only screen and (max-width: 600px) {
  img {
      width: 100%;
      height: auto;
  }
}
```
Tento soubor obsahuje základní strukturu HTML dokumentu, odkaz na externí CSS soubor (style.css) a jednoduchou strukturu těla stránky. Obrázek web.png je zobrazen ve středovém kontejneru s třídou content. CSS styly definují responzivní chování obrázku pro různé šířky obrazovek, s maximální šířkou obrázku na 600px.