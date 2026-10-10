# Football Manager: Zmajevi — v0.2

Prvi igrivi prototip menadžera reprezentacije Bosne i Hercegovine. Projekat je statična web aplikacija (HTML, CSS, JavaScript) i može se objaviti na GitHub Pages.

## Pokretanje

1. Raspakuj `football-manager-zmajevi-v0.2.zip`.
2. Otvori folder `zmajevi-game`.
3. Otvori `index.html` u pregledniku.
4. Na ekranu **Centar utakmice** izaberi protivnika, takmičenje i da li je BiH domaćin ili gost, pa klikni **Igraj utakmicu**.

## Šta je uključeno

- Lista od 40 stvarnih igrača: polazni spisak A reprezentacije za SP 2026 i dodatni kandidati.
- EA SPORTS FC 26 OVR/POT ocjene iz FIFA Indexa kada su dostupne. Ako ocjena nije potvrđena, prikazuje se crtica umjesto izmišljene vrijednosti.
- Pretraga i filteri igrača, profili i izvor ocjene.
- Formacije 4-3-3, 4-2-3-1, 4-4-2, 3-5-2 i 5-3-2; izbor igrača u postavi.
- Izbor između 28 protivničkih reprezentacija, takmičenja i domaće/gostujuće utakmice.
- Simulirani rezultat, događaji utakmice i osnovna statistika.
- Historija odigranih mečeva i čuvanje karijere u `localStorage` preglednika.
- Prilagođen prikaz za telefon i desktop.

## Izvori i ograničenja podataka

- Zvanični spisak BiH za SP 2026: https://www.fifa.com/en/articles/bosnia-and-herzegovina-sergej-barbarez-names-squad
- Spisak na stranici NS/FS BiH: https://www.nfsbih.ba/en/sp2026-squad/sp-2026-squad-list-en-gb/
- EA SPORTS FC 26 reprezentacija BiH: https://fifaindex.com/teams/105013-bosnia-herzegovina/fc26
- EA SPORTS FC 26 ocjene igrača po nacionalnosti: https://fifaindex.com/nations/8-bosnia-and-herzegovina/fc26

Ocjene su verzijske vrijednosti iz FC 26, nisu zvanične ocjene Saveza niti nužno aktuelne ocjene u kasnijim izdanjima igre. Kandidat nije isto što i potvrđen aktuelni poziv. Neke godine/klubovi u FC 26 podacima mogu biti zastarjeli.

Protivničke reprezentacije i njihova snaga u ovoj verziji su za potrebe simulacije; nisu predstavljene kao službene FIFA/EA ocjene. Rezultati se generišu lokalno i nisu stvarni rezultati niti prognoze.

## Ograničenja prototipa

- Utakmica se trenutno simulira odmah; još nema animiranog 3D terena.
- Takmičenja su izbor za kontekst meča, a ne potpuna simulacija stvarnog rasporeda, žrijeba ili pravila kvalifikacija.
- Karijera se čuva u istom pregledniku/uređaju; nema online sinhronizacije.
