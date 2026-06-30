---
tags: #slayer-ai #podstawy-ai #jakosc #benchmarki
---

# Jak mierzymy jakość modeli?

**Proste wyjaśnienie benchmarków i testów AI**

---

## 🎯 Dlaczego musimy mierzyć jakość?

Wyobraź sobie, że chcesz zatrudnić pracownika. Nie wiesz, czy jest dobry, dopóki go nie przetestujesz.

Z modelami AI jest tak samo — musimy sprawdzić, jak dobrze radzą sobie z różnymi zadaniami.

---

## 📊 Co to jest benchmark?

**Benchmark = test dla modelu AI**

To jak egzamin, który sprawdza konkretne umiejętności:
- Rozumienie pytań
- Wiedzę o świecie
- Jakość języka
- Specjalistyczne umiejętności

**Analogia:** Jak test sprawdzający, czy kierowca zna przepisy i potrafi jeździć.

---

## 🏗️ Rodzaje testów

### 1. Testy polskie (nasze priorytety)

**LLMzSzŁ — egzaminy zawodowe**
- Testy z prawa, medycyny, administracji
- Sprawdza, czy model zna polskie realia
- Jak matura dla zawodów

**PES — egzamin państwowy**
- Ogólny test wiedzy
- Podstawowe umiejętności
- Jak egzamin gimnazjalny

**PoQuAD — pytania i odpowiedzi**
- Rozumienie tekstu po polsku
- Logiczne myślenie
- Jak test czytania ze zrozumieniem

### 2. Testy angielskie (kontrola jakości)

**MMLU — ogólna wiedza**
- 57 różnych przedmiotów
- Sprawdza, czy model nie zapomniał angielskiego
- Jak test wielozakładowy

**GSM8K — matematyka**
- Proste zadania matematyczne
- Logiczne rozumowanie
- Jak test z matematyki w szkole

---

## 🔄 Jak to działa w praktyce?

### Krok 1: Przygotowanie testu
- Mamy zestaw pytań i poprawnych odpowiedzi
- Każdy model dostaje dokładnie te same pytania
- Nikt nie widzi pytań wcześniej (anty-cheating)

### Krok 2: Testowanie modelu
- Model odpowiada na wszystkie pytania
- Każda odpowiedź jest oceniana automatycznie
- Wynik to procent dobrych odpowiedzi

### Krok 3: Porównanie
- Porównujemy wyniki różnych modeli
- Sprawdzamy, który jest lepszy
- Identyfikujemy mocne i słabe strony

---

## 🎯 Wyniki w praktyce

### Nasze wyniki (przykład)
- **Base Qwen3.5-9B:** 63.5 na LLMzSzŁ
- **Nasz model:** 66.8 na LLMzSzŁ (+3.3)
- **Angielski:** bez zmian (nie zepsuliśmy)

**Co to znaczy:**
- Nasz model jest lepiej przygotowany do polskich egzaminów
- Wciąż dobrze mówi po angielsku
- Poprawa jest realna, nie przypadkowa

---

## ⚠️ Pułapki i problemy

### Problem 1: Mała próbka
**Co się dzieje:** Testujemy na zbyt małej liczbie pytań
**Skutek:** Wynik może być przypadkowy
**Rozwiązanie:** Testujemy na co najmniej 400 pytaniach

### Problem 2: Kontaminacja
**Co się dzieje:** Model uczy się na pytaniach testowych
**Skutek:** Wynik jest sztucznie zawyżony
**Rozwiązanie:** Upewniamy się, że dane testowe nie były w treningu

### Problem 3: Różne metody testowania
**Co się dzieje:** Różne modele testujemy inaczej
**Skutek:** Porównanie nie jest uczciwe
**Rozwiązanie:** Używamy dokładnie tej samej metody dla wszystkich

---

## 🏆 Co jest dobrym wynikiem?

### Zależy od zastosowania
- **80%+** — bardzo dobry, gotowy do użycia
- **70-80%** — dobry, może potrzebować poprawek
- **60-70%** — średni, przydatny do prostych zadań
- **poniżej 60%** — słaby, wymaga dużo pracy

### Nasz cel
- **Polskie testy:** 70%+
- **Angielskie testy:** bez regresji (nie pogorszyć)
- **Jakość języka:** naturalna polszczyzna

---

## 🔍 Jak testujemy jakość języka?

### Test natywności
Nie wystarczą tylko testy wyboru. Sprawdzamy też, jak model pisze:

- **Gramatyka** — czy poprawnie odmienia słowa
- **Styl** — czy brzmi jak Polak
- **Realia** — czy zna polskie kontekst
- **Frazeologia** — czy używa polskich powiedzeń

**Jak to robimy:** Model pisze teksty, a inny mocny model ocenia jakość w skali 1-5.

---

## 📈 Jak wyniki się zmieniają?

### Poprawa w czasie
- **V1 (początek):** 63.5 na LLMzSzŁ
- **V2 (po treningu):** 66.8 na LLMzSzŁ
- **V3 (plan):** 70+ na LLMzSzŁ

### Co to pokazuje
- Nasze metody działają
- Każda wersja jest lepsza
- Postęp jest mierzalny

---

## 🌐 Dlaczego to ważne dla Ciebie?

### Jeśli jesteś użytkownikiem
- Wiesz, na co możesz liczyć
- Rozumiesz ograniczenia modelu
- Możesz wybrać najlepszą wersję

### Jeśli chcesz pomóc
- Widzisz, gdzie są problemy
- Możesz testować nowe wersje
- Rozumiesz, jak mierzyć postęp

### Jeśli jesteś ciekawski
- Znasz realne możliwości AI
- Rozumiesz, jak to działa
- Możesz porównywać różne modele

---

## 📚 Dalej w Wiki

Chcesz wiedzieć więcej?

🔹 [[Slayer-AI-Lab-Wiki/Jak działa trening modelu?]] — jak uczymy AI  
🔹 [[Slayer-AI-Lab-Wiki/Czym jest model językowy?]] — podstawy  
🔹 [[Slayer-AI-Lab-Wiki/Co to jest Slayer AI Lab?]] — projekt  
🔹 [[Slayer-AI-Lab-Wiki/Słownik pojęć]] — trudne słowa  

---

## 🌐 Zewnętrzne linki

- **Nasze wyniki:** https://slayer.fabryka.ai/leaderboard
- **Metodologia:** https://slayer.fabryka.ai/benchmarks
- **Przeglądarka testów:** https://slayer.fabryka.ai/bench-explorer

---

*Pamiętaj: wyniki testów to tylko jedna miara. Najważniejsze jest, jak model działa w praktyce.*
