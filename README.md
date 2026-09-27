# Wykaz pojazdów R-7 (erka)

Pomocnicza aplikacja do wypełniania dokumentu „Wykaz pojazdów kolejowych w składzie pociągu” (R-7) i generowania PDF.
Autor: Grzegorz Rejszel (kier. poc. 186).

Strona statyczna – bez serwera i bez budowania. Całość to `index.html` plus biblioteki PDF w `vendor/`.

## Struktura
- `index.html` – aplikacja
- `vendor/` – html2canvas 1.4.1 i jsPDF 2.5.1 (lokalnie, bez zależności od CDN)
- `favicon.svg`, `icon-192.png`, `icon-512.png`, `manifest.webmanifest` – ikona i „Dodaj do ekranu głównego” na telefonie
- `vercel.json` – nagłówki (cache bibliotek, podstawowe zabezpieczenia)

## Aktualizacja
Podmień `index.html` i wypchnij zmiany do repozytorium (albo uruchom ponownie `vercel --prod`).
