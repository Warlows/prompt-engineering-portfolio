rzypadki testowe – Logowanie

| Nazwa testu                     | Kroki                                                                 | Oczekiwany wynik                                | Wnioski                                     |
|--------------------------------|-----------------------------------------------------------------------|-------------------------------------------------|---------------------------------------------|
| Logowanie poprawne             | Wpisz poprawny login i hasło → kliknij "Zaloguj"                      | Przekierowanie do serwisu                       | Funkcja działa poprawnie                    |
| Puste pole loginu              | Zostaw login pusty → wpisz hasło → kliknij "Zaloguj"                  | Komunikat "login wymagany"                      | Obsługa błędów działa poprawnie             |
| Puste pole hasła               | Wpisz login → zostaw hasło puste → kliknij "Zaloguj"                  | Komunikat "hasło wymagane"                      | Obsługa błędów działa poprawnie             |
| Nieprawidłowe dane logowania   | Wpisz zły login/hasło → kliknij "Zaloguj"                             | Komunikat "Nieprawidłowe dane logowania"        | System nie wpuszcza nieautoryzowanych osób  |
