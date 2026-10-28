# Peaso Torneo — web inicial

Aquesta carpeta conté una primera versió visual de la nova web del Peaso Torneo.

## Què inclou
- Disseny responsive per ordinador i mòbil.
- Portada i seccions: grups, eliminatòries, rànquing històric, participacions i dades.
- Sistema de punts que has indicat: 20, 14, 9, 6, 3 i 1.
- Intenta carregar el TSV publicat de Google Sheets.
- Si la lectura automàtica falla, la secció **Dades** permet importar un fitxer TSV/CSV manualment.

## Important sobre la connexió a Sheets
L'enllaç proporcionat és un TSV publicat i pot representar només una pestanya del document. A més, el navegador pot bloquejar la lectura automàtica per CORS. Perquè la web actualitzi tots els apartats automàticament, cal confirmar l'estructura exacta de les columnes i publicar/obtenir un enllaç per a cada pestanya que calgui.

Aquesta versió és una base de disseny funcional, però encara no interpreta semànticament les columnes dels històrics ni les classificacions de grups perquè no s'ha pogut llegir el contingut real del full.

## Prova local
Obre `index.html` al navegador. Si el navegador bloqueja la lectura del full, ves a **Dades** i importa un TSV/CSV descarregat de Google Sheets.

## Publicar gratuïtament amb GitHub Pages
1. Crea un compte o inicia sessió a GitHub.
2. Crea un repositori nou, per exemple `peaso-torneo`.
3. Puja `index.html` al directori principal del repositori.
4. Ves a **Settings → Pages**.
5. A **Build and deployment**, tria **Deploy from a branch**, branca `main`, carpeta `/ (root)` i desa.
6. GitHub et mostrarà l'adreça pública de la web.

No posis dades privades al full publicat. Aquesta web està pensada per a dades que es poden fer públiques.
