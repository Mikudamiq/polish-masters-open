# Polish Masters Open — strona wydarzenia

Statyczna strona (2 pliki HTML, bez zależności zewnętrznych poza Google Fonts w wersji roboczej):

- `index.html` — strona główna
- `info.html` — podstrona Info & regulamin

## Wdrożenie na GitHub Pages

1. Stwórz nowe repozytorium na GitHub (np. `polish-masters-open`), publiczne.
2. Dodaj te dwa pliki do repo (przez GitHub Desktop: File → Add local repository → wskaż ten folder → commit → publish/push).
3. W repo na GitHub: **Settings → Pages**.
4. W sekcji "Build and deployment" → Source: **Deploy from a branch**.
5. Branch: **main**, folder: **/ (root)** → Save.
6. Po 1–2 minutach strona będzie dostępna pod adresem:
   `https://<twoj-user>.github.io/polish-masters-open/`

Wszystkie linki wewnętrzne (`info.html`, `index.html#packages` itd.) są względne, więc będą działać poprawnie niezależnie od tego, pod jakim adresem/subpath strona wyląduje — nie trzeba niczego poprawiać w kodzie.

## Własna domena (opcjonalnie, na później)

Jeśli w przyszłości chcecie podłączyć własną domenę (np. `mastersopen.polskisquash.pl`):
1. Dodajcie plik `CNAME` z samą domeną w treści.
2. U dostawcy DNS ustawcie rekord CNAME wskazujący na `<twoj-user>.github.io`.
3. W Settings → Pages wpiszcie tę domenę w polu "Custom domain".
