# CLAUDE.md

Kontekst projektu i zasady współpracy dla Claude Code. Plik jest czytany na starcie każdej sesji.

## Właściciel

Jarosław Chybicki: psycholog i psychoterapeuta (CBT, ACT), wykładowca akademicki (UG, PG), trener
(FEBI, Leadership Development Framework), praktykujący Zen (tradycja Soto). Tworzy materiały
szkoleniowe i narzędzia dla klientów korporacyjnych (m.in. Lyra Polska, EAP).

- Komunikacja po polsku, zwięźle, z fachową terminologią (CBT, ACT, RFT). Bez pop-psychologii.
- Gdy intencja jest niejasna, zadaj pytanie zamiast zgadywać.

## Zawartość repozytorium

- `index.html`: **Energy Audit**, interaktywna strona z webinaru „Zarządzanie energią
  i efektywność bez wypalenia” (program „Odporni i gotowi”, Lyra Polska).
  **Nie nadpisywać.** To gotowa, osobna strona.
- Planowana **strona projektu szkoleniowego** to osobna strona. Jej lokalizacja (nowy katalog,
  osobne repozytorium lub osobny serwis Netlify) nie jest jeszcze ustalona, więc przed
  rozpoczęciem budowy zapytaj.

## Identyfikacja wizualna

- Kolory marki: `#084C61` (ciemny morski), `#177E89` (morski), `#DB3A34` (koralowy akcent).
- Tła ciepłe: `#FFFDFB` (krem), `#FFF3E6` (piasek), `#F5F0EB` (ciepła szarość).
- Fonty (Google Fonts): **Fraunces** do nagłówków, **DM Sans** do tekstu.
- Wzorzec stylu: tokeny CSS w `:root` w `index.html`. Nowe strony mogą z nich korzystać,
  chyba że właściciel wskaże inny charakter.
- Strony statyczne (pojedynczy plik HTML), responsywne, działające na telefonie.

## Przepływ pracy nad treścią

1. Treść merytoryczna powstaje w Claude czacie (Projekt).
2. Gotowe materiały trafiają do **folderu na Google Drive** (dostęp przez konektor Google Drive).
   Preferowane nazewnictwo plików: `01_hero`, `02_program`, `05_prowadzacy_bio`, `zdjecia/`.
3. W Claude Code: odczyt materiałów z Drive, budowa strony, commit, push, wdrożenie na Netlify.

- NotebookLM nie ma konektora. Notatki z niego trafiają do Google Docs na Drive.
- OneDrive: konto prywatne jest poza zasięgiem, preferowany jest Google Drive.

## Git i wdrożenia

- Praca na gałęzi wskazanej w sesji. Bez zgody nie zmieniać `main`.
- Pull request tworzyć tylko na wyraźną prośbę.
- Wdrożenia: Netlify (przez konektor Netlify).

## Zasady bezpieczeństwa

- Przed działaniami nieodwracalnymi lub zewnętrznymi (wysyłka maila, publikacja, usuwanie,
  zmiany na `main`) zawsze pytać o potwierdzenie.
- Maile: domyślnie tworzyć **szkic** zamiast wysyłać.
- Nie przetwarzać ani nie wysyłać danych klientów terapeutycznych ani informacji objętych
  tajemnicą zawodową bez wyraźnego potwierdzenia właściciela.
- Treści oparte na badaniach (EBP) oznaczać do weryfikacji. Ostatnie słowo merytoryczne należy
  do właściciela.
