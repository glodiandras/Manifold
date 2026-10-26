# Manifold

A Manifold hivatalos, magyar és angol bemutatóoldala.

- English: https://glodiandras.github.io/Manifold/
- Magyar: https://glodiandras.github.io/Manifold/hu.html
- Weboldalverzió: **v0.0** — ez nem alkalmazásverzió.

A bemutatóvideó még készül. Ez a változat nem kínál alkalmazásletöltést.

## Frissítés a tulajdonos jóváhagyásával

Az AI elkészítheti a változásokat, de a tulajdonos dönti el, mi és mikor kerül
nyilvánosságra. Ez a repó kész, statikus webes fájlokat tartalmaz; nincs saját
kiadási workflow, ütemezett feladat vagy kapcsolat a privát fejlesztői repóval.

1. Készüljön el az új webes export, és ellenőrizd az előnézetet.
2. A jóváhagyott exportot a **Code → Add file → Upload files** felületen töltsd
   a repó gyökerébe. A ZIP-et előbb bontsd ki; az `index.html` közvetlenül a
   gyökérbe kerüljön. A meglévő `.nojekyll` fájl maradjon meg.
3. A **Commit changes** lépéssel véglegesítsd a frissítést a `main` ágon.
4. A GitHub Pages ezután kiszolgálja a jóváhagyott fájlokat. Ellenőrizd a magyar
   és az angol oldalt is.

GitHub Pages beállítás: **Settings → Pages → Source: Deploy from a branch →
main → /(root) → Save**. A Custom domain mező üres marad.

A Pages a publikáló ágra kerülő változásokat közzéteszi, ezért erre az ágra
csak már jóváhagyott anyag kerüljön. Előkészítés és ellenőrzés helyben történik.

## Alkalmazáskiadások később

Az alkalmazás telepítői a **Releases** részbe kerülnek, nem a Git-fájlok közé.
Jóváhagyott új kiadásnál:

1. **Releases → Draft a new release**: hozz létre verziócímkét, például `v1.0.2`.
2. Add meg a verzió nevét és a felhasználóknak szóló változásokat.
3. Csatold az ellenőrzött DMG-t, az ellenőrzőösszegeket és a kiadáshoz tartozó
   szükséges licenc- és forráscsomagokat.
4. Ellenőrzésig maradjon **draft**; jóváhagyáskor válaszd a **Publish release**
   lehetőséget.
5. Ezután kerüljön fel a hozzá tartozó, ellenőrzött letöltési link a weboldalra.

A régebbi kiadások maradjanak elérhetők a Releases alatt. A weboldal nem
frissül a kiadások alapján magától, és nem frissíti automatikusan az alkalmazást.

GitHub dokumentáció: [Pages publikálási forrás](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site),
[kiadások kezelése](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository).
