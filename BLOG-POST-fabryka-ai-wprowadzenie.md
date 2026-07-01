# Blog Post: Czym jest fabryka.ai?

## Tytuł: **Czym jest fabryka.ai? Most między badaniami AI a produktami, które działają**

Alternatywne tytuły:
- fabryka.ai: laboratorium, które przerabia papiery AI na produkty
- Od artykułu naukowego do działającego narzędzia: poznaj fabryka.ai
- Polski neolab AI: nie agencja, nie newsletter, tylko realna praca

---

## Wersja do opublikowania

### Wstęp

Między akademickimi artykułami o AI a produktami, z których korzystamy na co dzień, jest ogromna przepaść.

Jedni piszą prace naukowe o nowych modelach. Inni budują startupy, które obiecują rewolucję. A gdzie pośrodku jest miejsce na czyś, kto bierze te najnowsze pomysły, testuje je na realnych danych, porównuje, naprawia, a potem pakuje w działające narzędzia?

Tym właśnie jest **fabryka.ai**.

---

## Czym jest fabryka.ai?

Sami siebie nazywają **„Neolab for applied AI systems”**. Nie agencją. Nie newsletterem. Nie kolejnym startupem, który ma tylko pitch deck.

**To laboratorium łączące badania z produktem.**

> „The weird useful layer between AI papers and working products.”

Czyli: dziwna, ale użyteczna warstwa między publikacjami naukowymi a działającymi produktami. Ich celem jest przeprowadzenie pomysłu od stadium artykułu naukowego do momentu, w którym można to wdrożyć i używać.

---

## Dlaczego to jest potrzebne?

Bo świat AI ma problem:

- **Papers With Code** pokazuje, że model istnieje i ma jakiś wynik.
- **Vendorzy** obiecują, że ich narzędzie rozwiąże wszystko.
- **Realne produkty** wymagają jednak testów na brzydkich, nieuporządkowanych danych, parsowania dokumentów, wyboru odpowiedniego modelu, routing u i uczciwej ewaluacji.

fabryka.ai siedzi dokładnie w tym miejscu. Nie produkuje hype'u. Nie sprzedaje obietnic. Buduje narzędzia, mierzy je publicznie i pokazuje, co naprawdę działa.

---

## Co robią?

### „Benchmark, parse, route, ship.”

To cztery słowa, które opisują ich filozofię:

1. **Benchmark** — najpierw sprawdzają, które modele są warte uwagi.
2. **Parse** — uczą się, jak przetwarzać dokumenty, obrazy, dane.
3. **Route** — wybierają odpowiedni model do odpowiedniego zadania.
4. **Ship** — wypuszczają działające produkty.

To podejście znacznie różni się od „ups, zbudujmy chatbota na GPT-4 i zobaczmy, co wyjdzie”.

---

## Aktywne projekty

fabryka.ai prowadzi siedem głównych ścieżek:

### 1. CodeSOTA

Kontynuacja idei Papers With Code. Taski, rankingi modeli, notatki o dowodach i praktyczne wskazówki, który model wybrać.

- benchmarki według zadań
- redakcyjny wybór modeli
- dowody zamiast obietnic vendorów

Link: https://codesota.com

### 2. Hardparse

Infrastruktura do parsowania dokumentów i OCR. Paragony, PDF-y, tabele, skany. Testowana na prawdziwych, brzydkich dokumentach.

- pipeline'y OCR
- parsowanie PDF-ów i obrazów
- porównania na bałaganiarskich dokumentach

Link: https://hardparse.com

### 3. Hermes SDK

SDK i runtime dla systemów agentowych. Agenci, narzędzia, lokalne i hostowane wykonanie, przekazywanie zadań.

- runtime agentów
- bramki narzędziowe
- lokalne + hostowane wykonanie

Link: https://github.com/search?q=hermes-sdk+fabryka

### 4. Router

Własny router inferencji: jeden endpoint, wiele modeli i providerów. Wybiera model na podstawie jakości, opóżnienia i kosztu.

- jeden endpoint, wiele modeli
- routing po jakości, koszcie, opóźnieniu
- open-weight + hostowane backendy

Link: https://router.fabryka.ai

### 5. Robotnik

AI coworker w Microsoft Teams. Czyta wątki, analizuje załączniki, odpowiada w kanale i wykonuje realną pracę przez Graph API.

- żyje w Teams
- czyta wątki i załączniki
- działa przez Graph API

Link: https://fabryka.ai/robotnik

### 6. ZusWaveBench

Polski benchmark dla urzędniczej logiki. 48 zadań w 11 domenach, ocenianych deterministyczną punktacją, a nie subiektywnym sądem LLM-a.

- 48 zadań, 11 domen
- deterministyczny scorer
- publiczna, żywa tablica wyników

Link: https://kwikiel.github.io/ZusWaveBench/

### 7. Bozenka

Polski offline text-to-speech. Fine-tuning XTTS-v2 na własnym RTX 3090. Cały pipeline od surowego audio do działającego checkpointu.

- fine-tune XTTS-v2
- trenowane na RTX 3090
- budowane publicznie

Link: https://kwikiel.github.io/new-model-every-day/

---

## Filozofia: mały klaster, duża uczciwość

Jedna rzecz szczególnie wyróżnia fabryka.ai:

> „The cluster is one RTX 3090, a queue, and taste.”

To nie jest firma, która udaje hyperscalera. Ich klaster to jedna karta graficzna, kolejka zadań i „smak” — czyli umiejętność rozpoznawania, co warto robić.

Po co tak mało?

- żeby móc odtwarzać własne wyniki
- żeby testować open-weight modele
- żeby porównywać pipeline'y OCR
- żeby prowadziĆ uczciwe eksperymenty z agentami

Nie zaczynają od wielkiej infrastruktury. Zaczynają od małej, kontrolowanej, którą rozumieją. Dopiero potem skalują.

---

## Cel: zero do 100k miesięcznie

Strona główna wspomina cel:

> „Zero to 100k monthly by Jul 2027.”

To nie jest obietnica inwestorom. To publiczna deklaracja ambicji. Chcą przejść od zera do 100 tysięcy miesięcznych użytkowników produktów AI do lipca 2027 roku.

I robią to transparentnie, budując w publicznych repozytoriach, publikując benchmarki i opisując proces.

---

## Co to oznacza dla polskiej AI?

Polska AI potrzebuje właśnie takich miejsc.

- Miejsc, które mierzą, zamiast obiecywać.
- Miejsc, które testują na polskich dokumentach, polskich urzędach, polskich głosach.
- Miejsc, które pokazują, że można budować AI bez wielkich funduszy VC, ale z głową.

fabryka.ai nie jest dużym korporacyjnym laboratorium. Jest małym, szybkim, uczciwym laboratorium. I właśnie to czyni je interesującym.

---

## Dla kogo jest to ważne?

- Dla **programistów**, którzy szukają narzędzi, a nie obietnic.
- Dla **przedsiębiorców**, którzy chcą zobaczyć, co naprawdę działa.
- Dla **badaczy**, którzy potrzebują benchmarków na polskich danych.
- Dla **osób nietechnicznych**, które chcą zrozumieć, jak buduje się AI od kuchni.

---

## Co dalej?

To pierwszy post z serii. W kolejnych przyjrzymy się poszczególnym ścieżkom fabryka.ai:

- jak działa ZusWaveBench i dlaczego polska urzędowość potrzebuje własnych benchmarków
- jak Router wybiera model do każdego zapytania
- jak Robotnik pracuje w Microsoft Teams
- jak Bozenka uczy się polskiego głosu
- jak Hardparse radzi sobie z brzydkimi dokumentami

Będziemy opisywać to, co faktycznie robią, bez dodawania własnych wizji.

---

## Linki

- 🌐 Strona: https://fabryka.ai
- 📚 CodeSOTA: https://codesota.com
- 📄 Hardparse: https://hardparse.com
- 🔗 Router: https://router.fabryka.ai
- 🤖 Robotnik: https://fabryka.ai/robotnik
- 📊 ZusWaveBench: https://kwikiel.github.io/ZusWaveBench/
- 🗣️ Bozenka: https://kwikiel.github.io/new-model-every-day/
- 👥 GitHub: https://github.com/search?q=hermes-sdk+fabryka

---

## Tagi / hashtagi

#fabryka-ai #polska-ai #ai-lab #benchmark #ocr #router #agent-ai #tts #applied-ai #open-source

---

## Wersja skrócona (do social media)

„fabryka.ai to nie agencja, nie newsletter. To polskie „neolab”, które przerabia artykuły naukowe o AI na działające produkty. Jeden RTX 3090, kolejka zadań i siedem ścieżek: CodeSOTA, Hardparse, Hermes SDK, Router, Robotnik, ZusWaveBench i Bozenka. Wpis po wpisie będziemy opisywać, co robią.

Czytaj: https://blog.fabryka.ai"
