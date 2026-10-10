# Football Manager: Zmajevi — prototip v0.1

Prvi statični prototip igre za reprezentaciju Bosne i Hercegovine. Napravljen je u HTML/CSS/JavaScriptu bez build alata, tako da se može otvoriti direktno ili objaviti na GitHub Pages.

## Pokretanje lokalno

1. Preuzmi ZIP i raspakuj ga.
2. Otvori `index.html` u pregledniku.
3. Za najbolji rezultat koristi noviji Chrome, Firefox ili Edge.

## Objavljivanje na GitHub Pages

1. Napravi GitHub repozitorij, npr. `football-manager-zmajevi`.
2. Uploadaj sva četiri fajla/foldera iz ZIP-a (`index.html`, `styles.css`, `app.js`, `players.js`, `README.md`) u korijen repozitorija.
3. Otvori **Settings → Pages**.
4. U odjeljku **Build and deployment** izaberi **Deploy from a branch**, branch `main`, folder `/ (root)`, pa **Save**.
5. Sačekaj da GitHub objavi stranicu.

## Šta radi u v0.1

- Kontrolna tabla i mobilna navigacija.
- Pretraga i filteri za igrače.
- Profili s OVR/POT ocjenama.
- Formacije 4-3-3, 4-2-3-1, 4-4-2, 3-5-2 i 5-3-2.
- Promjena igrača na terenu i čuvanje taktike.
- Jednostavna probna simulacija utakmice.
- Lokalno čuvanje karijere kroz `localStorage`.

## Izvori i ograničenja podataka

Ukupne ocjene su preuzete iz FIFA Index FC 26 baze za igrače iz BiH; potencijali su preuzeti iz tima FC 26 gdje su prikazani, a za igrače koji nisu u tom sastavu potencijal je postavljen na prikazani OVR jer javna nacionalna lista tako prikazuje tabelu. To je izvorna vrijednost iz igre, ne korisnički unos. Različita izdanja EA FC/FC 26 baze mogu se razlikovati. Statusi „prvi tim/kandidat/mladi igrač”, godine i klupski podaci u ovoj prvoj verziji su početni podaci koje treba dodatno provjeriti prije konačnog izdanja. Ovo je nezvanični fan projekat i nije povezan s EA Sports ili NS/FS BiH.

## Sljedeće faze

1. Provjerena baza igrača i detaljni atributi po javnim profilima.
2. Pravi match engine s dosljednom statistikom i događajima.
3. Pseudo-3D teren s animiranim igračima.
4. Takmičenja, kalendar, tabele i višesezonska karijera.
