# Prompt Engineering – Przykłady i wyjaśnienia

Ten folder zawiera przykładowe prompty stworzone w różnych stylach, zgodnie z najlepszymi praktykami Prompt Engineeringu, jakie poznaliśmy podczas kursu.

Każdy prompt zawiera:
-  Cel i zastosowanie
-  Dlaczego działa
-  Na co uważać
-  Przykład odpowiedzi od modelu

---

## 📌 Przykład 1: Klasyczny prompt testera – przypadki testowe

**Prompt**:
> Wygeneruj przypadki testowe dla funkcji logowania. Uwzględnij przypadki pozytywne, negatywne oraz graniczne. Przedstaw je w formie tabeli z nazwą testu, krokami, oczekiwanym wynikiem i wnioskami.

**Dlaczego działa**:
- Określa **konkretne zadanie** (testy logowania)
- Podaje **format odpowiedzi** (tabela + pola)
- Wymusza **różne typy przypadków** (negatywne, graniczne)

**Efekt**:
Model wygeneruje klarowną tabelę przydatną do automatyzacji.

---

## 📌 Przykład 2: Prompt chain – analiza i kod testów

**Prompt 1**:
> Przeanalizuj funkcję dodania produktu do koszyka. Użytkownik wybiera rozmiar, kolor, ilość, następnie przechodzi do zakupu.

**Prompt 2**:
> Wygeneruj przypadki testowe dla tej funkcji w tabeli. Uwzględnij błędy, scenariusze brzegowe i pozytywne testy.

**Prompt 3**:
> Na podstawie tych przypadków, wygeneruj kod testu automatycznego w Cypress.

**Dlaczego działa**:
- Dzieli zadanie na **etapy** (prompt chaining)
- Pozwala modelowi budować **kontekst krok po kroku**
- Ostatecznie prowadzi do kodu

**Efekt**:
Zautomatyzowany test gotowy do wdrożenia na CI/CD.

---

## 📌 Przykład 3: Prompt diagnostyczny

**Prompt**:
> Jako mentor AI, przeanalizuj podany prompt i wskaż, co działa dobrze, co można poprawić, i jakie są możliwe błędy w jego działaniu. Podaj wersję poprawioną.

**Dlaczego działa**:
- Model wchodzi w **rolę krytyczną** (diagnostyk)
- Uczy się poprzez **refleksję**
- Pomaga poprawić jakość promptów

**Efekt**:
Poprawiona wersja + nauka na błędach

---

## 📌 Przykład 4: Prompt do testowania agenta AI

**Prompt**:
> Wygeneruj przypadki testowe dla AI agenta obsługującego formularz wysyłkowy. Uwzględnij sytuacje, w których brakuje danych, dane są niepoprawne, lub formularz jest wypełniony prawidłowo.

**Dlaczego działa**:
- Skupia się na realnym zastosowaniu agenta
- Wymusza pokrycie wielu przypadków użycia
- Nadaje się do testowania modeli generatywnych

**Efekt**:
Zestaw testów do oceny jakości agenta AI

---

## 📌 Przykład 5: Prompt kreatywny – porównania

**Prompt**:
> Porównaj sposób działania agenta AI do gotowania zupy. Zbuduj metaforę i wytłumacz proces uczenia modelu w sposób przystępny.

**Dlaczego działa**:
- Wymusza **analogiczne myślenie**
- Pomaga **tłumaczyć trudne pojęcia**
- Idealne do tworzenia materiałów szkoleniowych
