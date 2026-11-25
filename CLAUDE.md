# Instrukcje dla Claude

- Użytkownik pisze po polsku i nie zna Gita – odpowiadaj po polsku, prostym językiem, bez żargonu.
- **Każdą gotową i sprawdzoną zmianę od razu wgrywaj do gałęzi `main`** (bez pytania o zgodę). Commituj na gałęzi roboczej, a potem wypchnij ją także na `main` (fast-forward, np. `git push origin <gałąź>:main`). Nie zakładaj pull requestów, chyba że użytkownik o to poprosi.
- Przy każdej zmianie w `index.html` podbij wersję `CACHE` w `sw.js`, żeby telefon pobrał nową wersję aplikacji.
- Aplikacja to jeden plik `index.html` (PWA, dane w localStorage) – testuj zmiany w Playwright/Chromium przed wgraniem.
