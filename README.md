# Manifold

Jegyzetek, források és tanulási eszközök egyetlen, helyben működő Mac-alkalmazásban.
A Manifold hivatalos bemutatóoldala és jóváhagyott alkalmazáskiadásai.

- [Magyar bemutató](https://glodiandras.github.io/Manifold/hu.html)
- [English showcase](https://glodiandras.github.io/Manifold/)
- [Manifold 1.0.2 Showcase letöltése macOS-re](https://github.com/glodiandras/Manifold/releases/download/v1.0.2-showcase.1/Manifold-1.0.2-showcase.1.dmg)
- [Kiadási információk és ellenőrzőösszegek](https://github.com/glodiandras/Manifold/releases/tag/v1.0.2-showcase.1)
- [Korábbi alkalmazáskiadások](https://github.com/glodiandras/Manifold/releases)

A jelenlegi kiadás **1.0.2-showcase.1**, alkalmazásverzió **1.0.2, build 4**.
Apple Silicon Mac és macOS 26.2 vagy újabb rendszer szükséges; a kezelőfelület angol.
Az alkalmazás ingyenesen használható a mellékelt saját feltételek szerint.
A kiadás önaláírt, Apple-notarizáció nélkül; a telepítési útmutató a kiadási oldalon van.
A bemutatóvideó még készül.

## Saját forráskód és külső komponensek

A Manifold saját alkalmazás-forráskódja **privát, nem nyilvános**. Ez a repó
kizárólag a kész bemutatóoldalt és a jóváhagyott terjesztési fájlokat tartalmazza.
A Releases alatt automatikusan megjelenő „Source code” archívumok ennek a
nyilvános webes repónak a fájljai, nem a Manifold alkalmazás saját forrásai.

A külső komponensek megőrzik saját licenceiket. A hozzájuk szükséges
forráscsomagok, a DMG/ZIP és a SHA-256-jegyzék együtt szerepelnek a kiadásnál.

## Kézzel jóváhagyott frissítések

Az AI előkészítheti és ellenőrizheti a változásokat; a tulajdonos dönt arról,
mi és mikor kerül nyilvánosságra. Nincs saját kiadási workflow, ütemezett
feltöltés vagy kapcsolat a privát fejlesztői repóval.

1. Ellenőrizd az új alkalmazáscsomagot, kiadási leírást és ellenőrzőösszegeket.
2. A jóváhagyott verziót külön címkével tedd közzé a Releases alatt;
   a régi kiadásokat hagyd elérhetően.
3. Ezután töltsd fel a hozzá tartozó kész statikus weboldalt a `main` ágra.
   A ZIP-et előbb bontsd ki; az `index.html` a gyökérbe kerüljön.
4. Ellenőrizd az élő magyar és angol oldalt, valamint a letöltést.

A weboldal letöltési hivatkozása kézzel kiválasztott verzióra mutat, nem változik
meg magától egy új release létrehozásától.
GitHub Pages: `main` ág, `/(root)` mappa, üres Custom domain; a `.nojekyll` maradjon meg.
