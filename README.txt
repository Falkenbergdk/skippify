Skippify PWA v3

NYT I V3
- Rettet PWA-cache så index.html altid forsøges hentet frisk fra GitHub Pages
- Gammel cache ryddes automatisk ved ny service worker
- skipWaiting + clients.claim gør opdateringer hurtigere aktive
- Appen virker stadig offline som fallback

OPDATER GITHUB
Erstat disse filer i dit eksisterende repo:
- index.html
- sw.js

Commit ændringerne.

Efter GitHub Pages har deployet:
1. Åbn GitHub Pages-linket i Safari én gang.
2. Genindlæs siden.
3. Luk Skippify fra appskifteren.
4. Åbn Skippify fra hjemmeskærmen igen.

Fremover bør nye commits slå igennem langt hurtigere uden at du skal kæmpe med gammel app-cache.
