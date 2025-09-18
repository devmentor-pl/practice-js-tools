__git init__ - inicjalizacja nowego repozytorium.

__git clone [URL]__ - skopiowanie istniejącego repozytorium.

__git status__ - sprawdzenie aktualnego stanu plików (co zostało zmienione, dodane, usunięte).

__git add .__ - dodanie wszystkich zmienionych/nowych plików do "strefy przejściowej" (staging area) przed zatwierdzeniem.

__git commit -m "Twoja wiadomość opisująca zmianę"__ - zatwierdzenie zmian w repozytorium lokalnym wraz z opisem.

__git push origin main__ - wysłanie zatwierdzonych zmian z lokalnego repozytorium na zdalny serwer (np. GitHub, GitLab).

__git pull origin main__ - pobranie najnowszych zmian z serwera zdalnego do lokalnego repozytorium.

__git revert --no-commit [id]__ -  przywrócenie struktury sprzed jakiegoś commita

----
### Conventional commits

Sposób pisania commitów z podziałem na ich specyficzne kategorie
Podstawowa struktura wiadomości commitu składa się z trzech części:

**1. Nagłówek (Header)**: To pierwsza linia, która ma ustalony format.

- **`<typ>[!(opcjonalny zakres)]: <opis>`**
    
- **`typ`**: To słowo kluczowe, które klasyfikuje rodzaj zmiany (np. `feat`, `fix`, `docs`). Jest ono obowiązkowe.
    
- **`opcjonalny zakres`**: To element, który precyzuje, w której części projektu zmiana została wprowadzona (np. `api`, `login`, `cli`). Jest opcjonalny.
    
- **`opis`**: Krótki, zwięzły opis samej zmiany. Należy go pisać w czasie teraźniejszym i unikać wielkich liter na początku.
    

**2. Ciało (Body)**: Opcjonalna, bardziej szczegółowa część, która wyjaśnia, co zostało zmienione i dlaczego.

**3. Stopka (Footer)**: Opcjonalna część, która może zawierać informacje o **Breaking Changes** (zmianach łamiących) lub referencje do problemów w systemach do śledzenia błędów (np. `Closes #123`).

#### Typy Commitów
 Najczęściej używane typy. Warto zauważyć, że typy `feat` i `fix` mają specjalne znaczenie, ponieważ to one determinują, kiedy należy podnieść numer wersji w systemie automatycznego wersjonowania (np. w oparciu o Semantic Versioning).

- **`feat`**: Nowa funkcjonalność. Gdy dodajesz nową, istotną funkcję.
    
- **`fix`**: Poprawka błędu. Używa się, gdy naprawiasz coś, co nie działało poprawnie.
    
- **`docs`**: Zmiany w dokumentacji. Obejmuje pliki `README.md`, dokumentację API, czy komentarze w kodzie.
    
- **`style`**: Zmiany w formatowaniu kodu. Nie wpływają na logikę (np. białe znaki, formatowanie, średniki).
    
- **`refactor`**: Przebudowa kodu bez zmian w funkcjonalności. Zmiany nie dodają nowych funkcji ani nie naprawiają błędów.
    
- **`test`**: Dodanie lub zmiana testów (np. testy jednostkowe, integracyjne).
    
- **`chore`**: Zmiany, które nie dotyczą kodu produkcyjnego ani testów. (np. aktualizacja narzędzi, zmiany w konfiguracji kompilacji).
    
- **`ci`**: Zmiany w konfiguracji ciągłej integracji. (np. pliki konfiguracyjne CircleCI, GitLab CI).
    
- **`perf`**: Zmiany, które poprawiają wydajność.
    
- **`build`**: Zmiany, które wpływają na system kompilacji lub zależności. (np. zmiana w pliku `package.json`).



