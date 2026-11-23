# 🔒 Pridjev Escape

Besplatni online **escape room kviz o pridjevima** za učenike 3. razreda osnovne škole (hrvatski jezik).

**Igraj:** https://KORISNIK.github.io/pridjev-escape/

## Priča

Netko je zaključao učionicu 3.D i ukrao sve pridjeve iz rečenica. Ostale su samo imenice: stol, čovjek, kuća… Razred ima 10 minuta da pobjegne. Svaka soba otključava se tek kad se riješi zadatak s pridjevima.

## Sobe

| Soba | Zadatak | Što se vježba |
|------|---------|---------------|
| 1. Sef pravopisa | Upiši šifru `Markov7` | Posvojni pridjevi (-ov, -ev, -in) pišu se velikim početnim slovom kad su od vlastitih imena |
| 2. Laboratorij sročnosti | Odaberi imenicu uz koju ide *visok* | Slaganje pridjeva s imenicom u rodu, broju i padežu |
| 3. Tvornica stupnjevanja | Pomakni klizač na superlativ | jak → jači → najjači |
| 4. Final boss | Složi rečenicu *Ivanov drveni stol* | Red riječi: čiji? + od čega? + što? |

## Kako se igra

- Svaki učenik igra na svom mobitelu: ima vlastiti tajmer, savjete i bodove za brzinu.
- PIN za ulaz: `3D-ESCAPE`
- Pobjednik je tko prvi pobjegne.
- Učiteljica klikne **Voditelj** i na projektoru dobiva QR kod, PIN i prikaz napretka po sobama.

## Uživo praćenje napretka (nije obavezno)

Zadano radi demo-način i lokalna ljestvica. Za pravi prikaz s mobitela učenika na projektoru:

1. Napravi besplatni projekt na [Firebase](https://firebase.google.com/) i uključi **Realtime Database**.
2. U `index.html` pronađi `const FIREBASE_URL=""` i upiši svoj link, npr. `https://tvoj-projekt-default-rtdb.firebaseio.com/escape`.
3. U pravilima baze dopusti čitanje i pisanje (samo za školsku uporabu).

## Tehnički podaci

Jedna datoteka (`index.html`), bez knjižnica i bez instalacije. QR kod se generira preko servisa api.qrserver.com.
