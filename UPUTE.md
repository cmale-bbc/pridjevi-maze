# Upute: objava na GitHub Pages i pojavljivanje na Googleu

## 1. Zamijeni KORISNIK

U datotekama `index.html`, `README.md`, `robots.txt` i `sitemap.xml` zamijeni `KORISNIK` svojim GitHub korisničkim imenom (malim slovima). Ako repozitorij nazoveš drukčije od `pridjev-escape`, zamijeni i to.

Primjer: korisnik `ivana-skola` daje adresu `https://ivana-skola.github.io/pridjev-escape/`.

## 2. Napravi repozitorij

1. Na github.com klikni **New repository**.
2. Naziv: `pridjev-escape`, vidljivost: **Public**.
3. Klikni **Create repository**.

## 3. Učitaj datoteke

Najlakše je preko preglednika: **Add file → Upload files**, povuci svih 5 datoteka (`index.html`, `README.md`, `robots.txt`, `sitemap.xml`, `.nojekyll`) i klikni **Commit changes**.

Datoteka `.nojekyll` počinje točkom pa je na nekim računalima skrivena. Ako je ne vidiš, nije nužna za ovu stranicu, možeš je preskočiti.

## 4. Uključi GitHub Pages

1. U repozitoriju otvori **Settings → Pages**.
2. Pod **Build and deployment** odaberi **Deploy from a branch**.
3. Branch: `main`, mapa: `/ (root)`, klikni **Save**.
4. Za minutu-dvije stranica je dostupna na `https://KORISNIK.github.io/pridjev-escape/`.

## 5. Prijavi stranicu Googleu

Google će je sam pronaći tek za nekoliko tjedana, a ovo ubrzava stvar:

1. Otvori [Google Search Console](https://search.google.com/search-console) i prijavi se Google računom.
2. Dodaj svojstvo **URL prefix** i upiši `https://KORISNIK.github.io/pridjev-escape/`.
3. Verifikacija: odaberi **HTML tag**, kopiraj ponuđeni `<meta name="google-site-verification" ...>` i zalijepi ga u `index.html` unutar `<head>`. Učitaj izmjenu na GitHub i klikni **Verify**.
4. U izborniku **Sitemaps** upiši `sitemap.xml` i pošalji.
5. U **URL Inspection** zalijepi adresu stranice i klikni **Request indexing**.

Indeksiranje obično traje od nekoliko dana do par tjedana. Provjeri s pretragom `site:KORISNIK.github.io/pridjev-escape`.

## 6. Savjeti za bolji poredak

- Što više ljudi povezuje na stranicu (škola, kolege, forumi), to bolje.
- U GitHub repozitoriju u **About** (desno gore) upiši opis i dodaj temu (topics): `pridjevi`, `hrvatski-jezik`, `kviz`.
- Ako dodaš nove zadatke, ažuriraj `lastmod` u `sitemap.xml`.
