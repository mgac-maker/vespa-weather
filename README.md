# Vespa Weather — komplet do GitHub Pages

## Pliki
- `index.html` — aplikacja z poprawką prognozy godzinowej, bez napisu „TWOJE CODZIENNE DECYZJE”, z obsługą błędów pobierania pogody.
- `apple-touch-icon.png` — ikona przygotowana z grafiki przesłanej przez użytkownika (512×512).
- `manifest.json` — metadane aplikacji.
- `README.md` — ta instrukcja.

## Wgranie na GitHub
1. Rozpakuj ZIP.
2. Otwórz repozytorium aplikacji na GitHub.
3. Wybierz **Add file → Upload files**.
4. Przeciągnij wszystkie cztery pliki z rozpakowanego folderu do katalogu głównego repozytorium (nie sam folder).
5. Zatwierdź przez **Commit changes**.
6. Wejdź w **Settings → Pages** i sprawdź, czy publikowanie jest ustawione z gałęzi `main` i katalogu `/ (root)`.
7. Po publikacji otwórz stronę aplikacji w Safari na iPhonie i wybierz **Udostępnij → Dodaj do ekranu początkowego**.

Jeśli skrót Vespa Weather był już dodany do ekranu początkowego, usuń stary i dodaj ponownie, aby odświeżyć ikonę. Jeśli Safari nadal pokazuje starą ikonę, odczekaj chwilę i spróbuj ponownie.

## Uwaga
Prognoza wymaga dostępu do internetu i odpowiedzi z używanego źródła pogody. Wersja ma komunikat błędu zamiast nieskończonego ładowania; nie mogę zagwarantować dostępności zewnętrznego API w każdej sieci.
