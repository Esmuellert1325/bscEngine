# bscEngine
- Egy 2D JavaScript játékmotor, amit a szakdolgozatomhoz készítettem

## Készítette
- Név: Faa Nándor
- Neptun: HWEHWK

### Telepítendő eszközök

*  [Visual Studio Code](https://code.visualstudio.com/#alt-downloads) kódszerkesztő
  * [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) bővítmény (a Visual Studio Code-hoz)
  
## Játékmotor használata
1. ZIP fájl letöltése
    - Code -> Download ZIP
2. __Scripts__ mappa és __bscEngine.js__ bemásolása a játékunk könyvtárába
 - Ajánlott egy extra _bscEngine_ nevű könyvtárba másolni őket 
3. HTML struktúra kialakítása (index.html)
``` HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <script type="module" src="script.js"></script>
</body>
</html>
```
4. __script.js__ fájl létrehozása (abba a könyvtárba ahol az __index.html__ van)
5. __style.css__ létrehozása (opcionális)
6. __Assets__ mappa létrehozása, amennyiben lesznek grafikák (opcionális)
7. Kód írása a __script.js__ fájlba

## Live Server indítása
- Fontos, hogy meglegyen a kiinduló __index.html__ fájlunk!
- Ha telepítve van, akkor a VS Code jobb alsó sarkában lesz egy __Go Live__ gomb
- A __Go Live__ gomb megnyomása után helyi hálózatra, áltlában az 5500-es portra fogja az __index.html__-t hosztolni
- Így láthatjuk valós időben a változtatásokat és futtathatjuk a játékunkat
