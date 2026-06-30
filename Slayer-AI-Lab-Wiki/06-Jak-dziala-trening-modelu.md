---
tags: #slayer-ai #podstawy-ai #trening #techniczne
---

# Jak działa trening modelu?

**Proste wyjaśnienie, jak uczymy AI mówić po polsku**

---

## 🧠 Analogia: nauka języka obcego

Wyobraź sobie, że model językowy to **osoba ucząca się języka polskiego**:

### 1. **Podstawowa edukacja (Base model)**
- Uczy się z milionów książek i artykułów
- Poznaje gramatykę i słownictwo
- Rozumie, jak zdania się budują
- Ale nie zna polskich realiów

### 2. **Kurs specjalistyczny (Fine-tuning)**
- Uczy się polskiego prawa i administracji
- Poznaje polskie firmy i instytucje
- Uczy się polskiego stylu pisania
- Staje się „polskim ekspertem"

---

## 🔄 Etapy treningu

### Etap 1: Wybór bazy
**Co robimy:** Wybieramy gotowy model, który już dobrze mówi po angielsku.

**Dlaczego:** Budowanie od zera kosztuje miliony dolarów. Lepiej dostosować coś, co już działa.

**Nasza baza:** Qwen3.5-9B — sprawdzony model, który dobrze radzi sobie z polskim.

---

### Etap 2: Zebranie danych polskich
**Co zbieramy:**
- **Polskie akta prawne** (ISAP, orzeczenia)
- **Materiały edukacyjne** (Wikipedia, podręczniki)
- **Dokumenty urzędowe** (formularze, instrukcje)
- **Artykuły i książki** polskich autorów

**Jak to robimy:**
- Pobieramy z publicznych źródeł
- Czyścimy z błędów i powtórzeń
- Upewniamy się, że dane są legalne

---

### Etap 3: Specjalizacja (Fine-tuning)
**Co się dzieje:**
Model uczy się na polskich danych, ale nie zapomina angielskiego.

**Jak to działa:**
- **QLoRA** — tania metoda dopasowania
- **Adaptacja** — model staje się bardziej „polski"
- **Kontrola** — sprawdzamy, czy nie psuje angielskiego

**Efekt:** Model rozumie polskie kontekst, ale wciąż mówi dobrze po angielsku.

---

### Etap 4: Preferencje (DPO/ORPO)
**Co to jest:** Uczymy model, jakie odpowiedzi są lepsze.

**Przykład:**
- **Zła odpowiedź:** „Nie wiem, co to ZUS"
- **Dobra odpowiedź:** „ZUS to Zakład Ubezpieczeń Społecznych, polska instytucja..."

Model uczy się wybierać lepsze odpowiedzi.

---

### Etap 5: Trening na egzaminach (GRPO)
**Co robimy:** Uczymy model rozwiązywać polskie egzaminy.

**Jak to działa:**
- Model dostaje pytanie egzaminacyjne
- Odpowiada na nie
- Jeśli dobrze, dostaje „nagrodę"
- Jeśli źle, dostaje „karę"

**Efekt:** Model lepiej radzi sobie z polskimi testami zawodowymi.

---

## 🎯 Dlaczego to działa?

### Transfer wiedzy
Model już umie „myśleć" po angielsku. Teraz tylko uczy się polskich słów i kontekstu.

**Analogia:** Jesteś ekspertem w swojej dziedzinie, tylko uczysz się nowego języka.

### Dane jakościowe
Nie dajemy modelowi wszystkiego, tylko najlepsze materiały:
- Oficjalne dokumenty
- Sprawdzone informacje
- Czyste teksty

**Analogia:** Uczysz się z dobrych podręczników, nie z losowych internetowych tekstów.

---

## ⚖️ Balans: polski vs angielski

### Problem
Jeśli zbyt mocno nauczymy model po polsku, może zapomnieć angielski.

### Rozwiązanie
- **Kontrola regresji** — sprawdzamy angielskie testy
- **Mieszanie danych** — część polska, część angielska
- **Testowanie** — upewniamy się, że oba języki działają

**Wynik:** Model jest dobry w obu językach.

---

## 💰 Koszty i czas

### Ile to kosztuje?
- **Dane:** głównie darmowe (publiczne źródła)
- **Trening:** ~15-20 tysięcy złotych
- **Czas:** kilka tygodni na mocnym komputerze

### Dlaczego tak mało?
- **Open-source** — nie płacimy za licencje
- **Chmura** — wynajmujemy moc tylko na trening
- **Współpraca** — wiele osób pomaga za darmo

---

## 🔍 Jak wiemy, że to działa?

### Testy przed i po
Mierzymy wyniki na wielu testach:
- **Polskie:** LLMzSzŁ, PES, PoQuAD
- **Angielskie:** MMLU, GSM8K, ARC

### Porównanie
- **Base Qwen:** 63.5 na LLMzSzŁ
- **Nasz model:** 66.8 na LLMzSzŁ (+3.3)
- **Angielski:** bez regresji

**Wniosek:** Poprawiliśmy polski bez psucia angielskiego.

---

## 🚀 Co dalej?

### Lepsze modele
- Więcej danych treningowych
- Lepsze metody treningu
- Większe modele (jeśli będzie potrzebne)

### Specjalizacje
- Medycyna polska
- Prawo polskie
- Biznes polski

### Aplikacje
- Asystent prawnika
- Pomoc dla studentów
- Narzędzia dla firm

---

## 📚 Dalej w Wiki

Chcesz wiedzieć więcej?

🔹 [[Slayer-AI-Lab-Wiki/Czym jest model językowy?]] — podstawy  
🔹 [[Slayer-AI-Lab-Wiki/Jak mierzymy jakość modeli?]] — testowanie  
🔹 [[Slayer-AI-Lab-Wiki/Co to jest Slayer AI Lab?]] — projekt  
🔹 [[Slayer-AI-Lab-Wiki/Słownik pojęć]] — trudne słowa  

---

## 🌐 Zewnętrzne linki

- **Nasz harmonogram:** https://slayer.fabryka.ai/roadmap
- **Metody treningu:** https://slayer.fabryka.ai/trening
- **Wyniki:** https://slayer.fabryka.ai/leaderboard

---

*Pamiętaj: trening AI to ciągły proces. Uczymy się, testujemy, poprawiamy i znowu uczymy.*
