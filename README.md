# Webes feladat összefoglaló

A feladat célja egy egyszerű webes projekt elkészítése, amely bemutatja az alapvető webfejlesztési technológiák használatát. A projekt során egy strukturált weboldal jön létre, ahol különválik a tartalom, a megjelenés és a működés.

A feladat segít megérteni a modern webfejlesztés alapjait, a verziókezelés szerepét, valamint azt, hogy a különböző technológiák hogyan egészítik ki egymást egy működő alkalmazásban.

## Felhasznált technológiák

* GIT
* HTML
* CSS3
* JavaScript

**GIT**: Verziókezelő rendszer, amely lehetővé teszi a projekt változásainak nyomon követését. Segítségével visszaállíthatók korábbi állapotok, valamint támogatja az egyéni és csapatmunkát is. A fejlesztés így átláthatóbb és biztonságosabb.

```bash
git status
git add .
git commit -m "Initial commit"
```

**HTML**: Egy leíró nyelv, amelyet a böngésző értelmez, és a benne található elemek alapján megjelenít egy weboldalt. A HTML határozza meg az oldal szerkezetét és tartalmát. Az elemek tagek segítségével kerülnek leírásra.

```html
<!DOCTYPE html>
<html lang="hu">
  <head>
    <meta charset="UTF-8" />
    <title>Példa oldal</title>
  </head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

**CSS3**: Stílusleíró nyelv, amely a HTML elemek megjelenését szabályozza. Segítségével beállíthatók a színek, betűtípusok, térközök és az oldal elrendezése. A CSS teszi vizuálisan vonzóvá a weboldalt.

```css
body {
  background-color: #f0f0f0;
  font-family: Arial, sans-serif;
}

h1 {
  color: darkblue;
}
```

**JavaScript**: Programozási nyelv, amely a weboldal működését és interaktivitását biztosítja. Használható eseménykezelésre, dinamikus tartalom módosítására és logikai folyamatok megvalósítására. A modern web egyik alapköve.

```javascript
const button = document.querySelector("button");
button.addEventListener("click", () => {
  alert("Gombra kattintottál!");
});
```

## Technológiák értékelése

| GIT  | HTML  | CSS  | JS    |
| ---- | ----- | ---- | ----- |
| **** | ***** | **** | *** |
