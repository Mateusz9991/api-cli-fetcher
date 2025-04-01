# api-cli-fetcher
Aplikacja data-fetcher-cli to narzędzie wiersza poleceń (CLI), które pozwala na pobieranie danych z zewnętrznego API i zapisywanie ich w pliku JSON. Jest to przydatne narzędzie do zbierania danych z API i przechowywania ich w formacie, który jest łatwy do dalszej obróbki i analizy.

# Instrukcje instalacji
1 **Zainstaluj Node.js i npm
Aplikacja wymaga środowiska Node.js oraz menedżera pakietów npm. Jeśli jeszcze nie masz zainstalowanego Node.js, pobierz go ze strony:
https://nodejs.org/**

  2 **Skopiuj repozytorium na swój komputer
W terminalu sklonuj repozytorium za pomocą komendy:**
**https://github.com/Mateusz9991/api-cli-fetcher.git**

 3 **W terminalu przejdź do folderu projektu:**
   ```bash
   cd data-fetcher-cli
   ```
4 **W katalogu głównym projektu uruchom poniższą komendę, aby zainstalować wszystkie niezbędne pakiety:**
```bash
npm install
```
# Konfiguracja #
**Przykładowa konfiguracja (plik config.json)**
```bash
{
  "apiUrl": "https://api.example.com/data"
}
```
# Przykłady użycia:#
**1 Pobierz dane z domyślnego API i zapisz do pliku output.json:**
```bash
node index.js --output output.json
 
```
