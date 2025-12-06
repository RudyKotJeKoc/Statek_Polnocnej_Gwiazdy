# NIESPÓJNOŚCI I FIXLIST – Systematyczna Lista Poprawek

**Format:** ID | Priorytet | Typ | Dowód (plik:linia) | Proponowana poprawka

**Priorytety:**
- **P0** = psuje sens lub wprowadza sprzeczność (wymaga naprawy)
- **P1** = osłabia wiarygodność (warto naprawić)
- **P2** = kosmetyka (opcjonalnie)

---

## P0 – KRYTYCZNE (psują sens lub wprowadzają sprzeczność)

### P0-01 | Brak precyzji w dacie sabotażu tamy
**Typ:** Daty / Timeline
**Dowód:**
- OUTLINE:24 → „2000–2012/2014: źródło umiejętności i pierwsze mechanizmy destrukcji"
- Rozdzial1:całość → Brak konkretnej daty „kiedy tama została zniszczona"

**Problem:**
Czytelnik nie wie, czy Bóbr budował tamę 10 lat, 12 lat czy 14 lat przed zniszczeniem. Zakres „2000–2012/2014" jest zbyt szeroki.

**Proponowana poprawka:**
W Rozdziale 1, scena I (po linii 15, przed „Pewnego popołudnia…") dodać jedno zdanie:

```markdown
Przez dwanaście lat Bóbr budował, zanim przyszła noc siekiery.
```

Alternatywnie, jeśli chcesz zachować nieprecyzyjność jako celowy zabieg:

```markdown
Przez wiele lat Bóbr budował – nie liczył czasu, tylko kolejne tamy.
```

**Efekt:** Czytelnik wie, że to był **długi okres**, nie „rok czy dwa".

---

### P0-02 | „Article 11" zamiast „Artykuł 11" (pomieszanie języków)
**Typ:** Terminologia NL/PL
**Dowód:**
- Rozdzial9:38 → „Artykuł 11: Geheimhouding." (poprawnie PL)
- Rozdzial9 (hipotetycznie, jeśli występuje) → „Article 11" (angielski)

**Problem:**
W OUTLINE i większości tekstu używane jest „Artykuł 11" (polski). Jeśli gdziekolwiek pojawia się „Article 11" (angielski), to jest niespójność językowa.

**Proponowana poprawka:**
Globalna zamiana: wszędzie „Artykuł 11" (nigdy „Article").

**Find & Replace:**
```
Article 11 → Artykuł 11
```

**Efekt:** Konsekwentna terminologia PL dla kluczowej klauzuli.

---

### P0-03 | Brak sceny „żelaznej przepustki" (luty 2022)
**Typ:** Logika / Brak mostu scenicznego
**Dowód:**
- OUTLINE:67 → „W lutym 2022 dostaje żelazną przepustkę – formalne 'zostajesz'."
- Rozdzial3:78 → Tylko wzmianka: „Żelazna przepustka: spokój tylko na papierze"

**Problem:**
OUTLINE mówi o ważnym momencie formalnym, ale w tekście nie ma sceny, gdzie Bóbr faktycznie **dostaje** tę przepustkę. Czytelnik nie wie, co to jest (papier? klucz? plakietka?).

**Proponowana poprawka:**
W Rozdziale 3, część IV (po linii 78, przed „Rozmowa z Kapitanem z Tabelką") dodać krótką scenę:

```markdown
W lutym Uśmiechnięty Kwatermistrz wezwał Bobra do biura. Bez uśmiechu tym razem – tylko z metalową plakietką w dłoni.

— To dla ciebie — powiedział. — Stały dostęp do UR. Zostałeś.

Bóbr wziął plakietkę. Miała numer, zdjęcie i datę bez końca.

— Dziękuję.

Kwatermistrz skinął głową.

— To nie nagroda. To identyfikacja.

Bóbr schował plakietkę do kieszeni i wiedział, że „identyfikacja" to inne słowo na „ślad na wypadek winy".
```

**Efekt:** Scena zakotwicza „żelazną przepustkę" jako konkretny obiekt i moment przełomowy.

---

## P1 – ŚREDNIE (osłabiają wiarygodność)

### P1-01 | Powtórzenie puenty „to dopiero początek"
**Typ:** Powtórzenia / Osłabienie efektu
**Dowód:**
- Rozdzial7:212 → „— Gotów? — Jestem gotów. Ale nie na ich grę. — Na swoją."
- Rozdzial11:202 → „— Dobra. To teraz budujemy."
- Rozdzial14:237 → „— To dopiero początek. Ale tym razem mój."

**Problem:**
Puenta „to początek / moja gra / teraz buduję" powtarza się 3 razy w kluczowych momentach (Rozdz. 7, 11, 14). To osłabia efekt finalnej sceny (Rozdz. 14).

**Proponowana poprawka:**
Zostawić puentę **tylko w Rozdziale 14** (finał). W Rozdz. 7 i 11 zastąpić innymi frazami:

**Rozdział 7:212** (było: „Na swoją"):
```markdown
— Gotów?

Bóbr spojrzał na Kolosa, który już wiedział, że nie ma przyszłości, tylko harmonogram.

— Jestem gotów — powiedział cicho. — Ale nie na tonięcie razem z nimi.

Dotknął Medalionu.

— Na przetrwanie.
```

**Rozdział 11:202** (było: „To teraz budujemy"):
```markdown
Bóbr odłożył go na stół.

— Dobra — powiedział do siebie. — Teraz przestaję ratować ich statek.

I zaczął rysować własną tratwę.
```

**Efekt:** Finalna puenta w Rozdz. 14 („To dopiero początek. Ale tym razem mój.") zyskuje unikalność i siłę zamknięcia.

---

### P1-02 | Brak konsekwencji po „nocnej naprawie pompy" (Rozdz. 3, scena I)
**Typ:** Logika / Brak konsekwencji
**Dowód:**
- Rozdzial3:19–46 → Bóbr naprawia pompę nocą.
- Rozdzial3:41–42 → „Nikt nie zauważy. Nikt nie podziękuje."
- Rozdzial3 część IV → Podejrzliwość pojawia się, ale nie jest powiązana z tą konkretną naprawą.

**Problem:**
Scena nocnej naprawy pompy (Rozdz. 3, I) jest dobrze napisana, ale **nie ma konsekwencji** w dalszej fabule. Jeśli „nikt nie zauważy", to po co ta scena? Jeśli zauważą – powinno być to pokazane.

**Proponowana poprawka (opcja A – dodać konsekwencję):**
W Rozdziale 3, część IV (scena „Podejrzliwość zamiast wdzięczności", po linii 168) dodać jedno zdanie:

```markdown
Pewnego dnia jeden z ludzi zatrzymał Bobra w korytarzu.

— „Co ty robisz po nocach?"
— „Naprawiam."
— „Bez zlecenia?"
— „Tak."
— „To nie jest tu mile widziane. Ktoś widział cię przy pompie zeszłej nocy. Kwatermistrz pyta, czy to ty."

Bóbr skinął głową.

— „To ja. Uszczelka nie trzymała. Naprawiłem."
— „Ale nie było zlecenia. Jak coś pójdzie źle, to nikt nie chce mieć w papierach twoich śladów."
```

**Efekt:** Scena I (nocna naprawa) ma teraz konsekwencję w scenie IV (podejrzliwość).

**Proponowana poprawka (opcja B – wyciąć scenę I, jeśli nie ma roli):**
Jeśli scena I nie ma funkcji fabularnej poza „pokazaniem kompetencji Bobra", można ją wyciąć i zastąpić krótszym opisem w innym miejscu.

**Rekomendacja:** Opcja A (dodać konsekwencję) – scena jest dobrze napisana, warto ją wykorzystać.

---

### P1-03 | Hans/Stary Armator – wahanie w nazwie postaci
**Typ:** Nazwy / Niespójność
**Dowód:**
- Rozdzial2:120 → „Stary Armator"
- Rozdzial3:228 → „Stary Armator"
- Rozdzial10:137 → „Hans"
- Rozdzial11:95 → „Hans"
- Rozdzial12:46 → „Hans"
- OUTLINE:320 → „Stary Armator"

**Problem:**
Czytelnik może myśleć, że to dwie różne postacie (zwłaszcza jeśli czyta z przerwami).

**Proponowana poprawka:**
**Opcja A (zalecana):** Konsekwentnie używać „Hans" od początku.

W Rozdziale 2:120 zamienić:
```markdown
Było: „Stary Armator spojrzał na niego uważnie."
Poprawka: „Hans – stary właściciel budynku – spojrzał na niego uważnie."
```

W Rozdziale 3:228 i dalej: wszędzie „Hans" zamiast „Stary Armator".

**Opcja B:** Przy pierwszym wystąpieniu w Rozdz. 2 wprowadzić obie nazwy:
```markdown
Stary Armator – Hans – stał przy ogrodzeniu.
```
Potem konsekwentnie „Hans".

**Efekt:** Czytelnik wie od początku, że „Stary Armator" = „Hans".

---

### P1-04 | „Północna Gwiazda" vs „Kolos" – mieszanie nazw bez wprowadzenia
**Typ:** Nazwy / Brak mostu
**Dowód:**
- Rozdzial1–6 → „Kolos"
- Rozdzial7:7 → Pierwszy raz „Północna Gwiazda"
- Rozdzial13 → Konsekwentnie „Północna Gwiazda" lub „ITB"

**Problem:**
W Rozdz. 7 nagle pojawia się nazwa własna „Północna Gwiazda" bez wprowadzenia. Czytelnik może się zastanawiać: czy to ten sam statek, czy inny?

**Proponowana poprawka:**
W Rozdziale 7:7–8 dodać jedno zdanie wyjaśniające:

```markdown
Było:
„12 czerwca 2025 słońce świeciło bezczelnie jasno. […] Tyle że Północna Gwiazda tego dnia nie płynęła."

Poprawka:
„12 czerwca 2025 słońce świeciło bezczelnie jasno. […] Tyle że Północna Gwiazda – jak nazywano Kolosa w oficjalnych papierach – tego dnia nie płynęła."
```

Alternatywnie (jeśli chcesz zachować tajemniczość):
```markdown
„Tyle że Kolos – znany formalnie jako Północna Gwiazda – tego dnia nie płynął."
```

**Efekt:** Czytelnik wie, że to ta sama jednostka.

---

### P1-05 | Adrian „uczony liczenia" – brak sceny wprowadzającej (Rozdz. 5)
**Typ:** Logika / Brak mostu
**Dowód:**
- Rozdzial5:133–144 → Adrian mówi: „Oni mnie uczą liczyć rzeczy, nie rozumieć."
- Wcześniejsze rozdziały → Brak sceny, gdzie Adrian jest przydzielony do „Księgi" (spis majątków).

**Problem:**
Zdanie Adriana „wisi w próżni" – czytelnik nie wie, dlaczego nagle Adrian jest przy spisie.

**Proponowana poprawka:**
W Rozdziale 5, część I (po linii 48, przed „Uśmiechnięty Kwatermistrz") dodać jedno zdanie:

```markdown
Adrian był teraz przy Księdze Atramentu, spisując majątki pod okiem Kwatermistrza. Nie pytał, po co. Tylko wpisywał numery, tak jak mu kazano.
```

Potem w scenie V (linia 133) zdanie Adriana ma kontekst.

**Efekt:** Scena V (rozmowa z Bobrem) ma logiczne wprowadzenie.

---

## P2 – KOSMETYKA (drobne poprawki wizualne/stylistyczne)

### P2-01 | Formatowanie rozdziałów – brak spójnego nagłówka
**Typ:** Formatowanie
**Dowód:**
- Rozdzial1:1–3 → „BAŚŃ O BOBRZE I TONĄCYM STATKU | CZĘŚĆ I: PREHISTORIA | ROZDZIAŁ 1 – Rzeka, Tama i Wiedźma"
- Rozdzial2:1 → „Zaspawany w Skrzyni" (brak nagłówka CZĘŚĆ I ani ROZDZIAŁ 2)
- Rozdzial3:1 → „CZĘŚĆ II: LATA OSTRZEŻEŃ (2021–2024) | ROZDZIAŁ 3 | Medalion Mówi Prawdę"

**Problem:**
Niespójność wizualna – czasem pełny nagłówek z CZĘŚCIĄ, czasem bez.

**Proponowana poprawka:**
Ujednolicić nagłówki:

**Wariant A (zalecany):** CZĘŚĆ tylko na początku każdej sekcji, ROZDZIAŁ w każdym rozdziale:

```markdown
CZĘŚĆ I: PREHISTORIA

ROZDZIAŁ 1 – Rzeka, Tama i Wiedźma

[treść]

---

ROZDZIAŁ 2 – Zaspawany w Skrzyni

[treść]

---

CZĘŚĆ II: LATA OSTRZEŻEŃ (2021–2024)

ROZDZIAŁ 3 – Medalion Mówi Prawdę

[treść]
```

**Wariant B:** Zawsze pełny nagłówek (CZĘŚĆ + ROZDZIAŁ) w każdym rozdziale:

```markdown
CZĘŚĆ I: PREHISTORIA
ROZDZIAŁ 1 – Rzeka, Tama i Wiedźma

CZĘŚĆ I: PREHISTORIA
ROZDZIAŁ 2 – Zaspawany w Skrzyni

CZĘŚĆ II: LATA OSTRZEŻEŃ
ROZDZIAŁ 3 – Medalion Mówi Prawdę
```

**Rekomendacja:** Wariant A (czystszy wizualnie).

---

### P2-02 | „Medalion Przewidywań" vs „Medalion" – wahanie w użyciu pełnej nazwy
**Typ:** Terminologia / Niespójność
**Dowód:**
- Rozdzial1:113 → „Medalion Przewidywań" (pełna nazwa)
- Rozdzial3:115 → „Medalion" (skrót)
- Czasem mieszane w jednym rozdziale.

**Problem:**
Brak konsekwentnej zasady.

**Proponowana poprawka:**
Ustalić zasadę:
- **Pełna nazwa „Medalion Przewidywań"** przy pierwszym wystąpieniu w rozdziale.
- **Skrót „Medalion"** w dalszej części rozdziału.

**Find & Replace (manualnie):**
W każdym rozdziale sprawdzić, czy pierwsze wystąpienie ma pełną nazwę.

**Efekt:** Konsekwencja bez nadmiernej repetycji.

---

### P2-03 | „Ramiona Robotów" / „Żelazne Ramiona" / „Żelazny Tancerz" – mieszane nazwy tej samej maszyny?
**Typ:** Nazwy / Niejasność
**Dowód:**
- Rozdzial3:13 → „ramiona robotów"
- Rozdzial6:6 → „Żelazny Tancerz"
- Rozdzial12:146 → „Żelazne Ramiona"

**Problem:**
Czytelnik może nie wiedzieć, czy to jedna maszyna, czy różne.

**Proponowana poprawka:**
**Opcja A (zalecana):** Konsekwentnie używać jednej nazwy.

Jeśli „Żelazny Tancerz" to konkretna maszyna (np. robot Motoman), a „Żelazne Ramiona" to ogólna kategoria – wyjaśnić przy pierwszym użyciu:

```markdown
W Rozdziale 3:13:
„ramiona robotów – niektórzy nazywali je Żelaznymi Ramionami – poruszały się jak tancerze"

Potem w Rozdziale 6:6:
„Żelazny Tancerz – jeden z robotów Motoman"
```

**Opcja B:** Ujednolicić na jedną nazwę („Żelazne Ramiona" wszędzie).

**Rekomendacja:** Opcja A (zachowuje poetyckość + jasność).

---

### P2-04 | „Pieczęć" vs „pieczęć" – kapitalizacja niespójna
**Typ:** Kapitalizacja
**Dowód:**
- Rozdzial5:13 → „Pieczęć" (wielka litera)
- Rozdzial7 (hipotetycznie) → „pieczęć" (mała litera)

**Problem:**
Wahanie między traktowaniem „Pieczęci" jako nazwy własnej (baśniowy rytuał) vs rzecz powszechną.

**Proponowana poprawka:**
Konsekwentnie **„Pieczęć"** (wielka litera) jako nazwa rytuału/wydarzenia.

**Find & Replace:**
```
pieczęć → Pieczęć (tylko w kontekście inspekcji/rytuału)
```

Uwaga: Małą literą zostawić tylko w ogólnym kontekście (np. „pieczęć na papierze").

**Efekt:** Baśniowa ranga rytuału zostaje podkreślona.

---

### P2-05 | „Piraci z Południa" – brak konsekwencji użycia w późniejszych rozdziałach
**Typ:** Terminologia / Osłabienie metafory
**Dowód:**
- Rozdzial4:6 → „Piraci z Południa"
- Rozdzial5:częste użycie
- Rozdzial6–14 → Nazwa znika, używane „oni", „zarząd", „mostek"

**Problem:**
Mocna metafora („Piraci z Południa") jest wprowadzona w Rozdz. 4–5, ale potem znika. To osłabia konsekwencję baśniowej nomenklatury.

**Proponowana poprawka:**
W Rozdziale 10 (odmowa sprzedaży pieców) i Rozdziale 13 (retrospekcja) przypomnieć metaforę raz:

**Rozdział 10:100–111** (po zdaniu Martijna „Czasem decyzje nie są o pieniądzach"):
```markdown
Bóbr zrozumiał wtedy prostą prawdę: Piraci z Południa nie chcieli zysku. Chcieli braku ciągłości. Chcieli, żeby po zatonięciu nie było nic, co może pływać dalej pod inną banderą.
```

**Rozdział 13:232–234** (retrospekcja):
```markdown
Piraci zmienili mapę i nazwali to „optymalizacją".
```

**Efekt:** Metafora zostaje przypominana w kluczowych momentach, wzmacniając spójność baśniową.

---

## PODSUMOWANIE FIXLIST

### Liczba niespójności wykrytych:
- **P0 (krytyczne):** 3
- **P1 (średnie):** 5
- **P2 (kosmetyka):** 5
**Razem:** 13 niespójności

### Szacowany czas napraw:
- **P0:** 30 min (3 × 10 min na scenę/poprawkę)
- **P1:** 2 h (5 × 20–30 min)
- **P2:** 1 h (5 × 10–15 min)
**Razem:** ~3,5 h pracy redakcyjnej

### Skala zmian:
- **Dodanie scen:** 3 (żelazna przepustka, Adrian przy Księdze, konsekwencja nocnej naprawy)
- **Zamiany fraz/nazw:** 5 (puenty, Hans/Stary Armator, Kolos/Północna Gwiazda)
- **Globalne find & replace:** 3 (Article→Artykuł, kapitalizacja Pieczęć, Medalion)

### Ryzyko:
✅ **Niskie** – żadna z napraw nie wymaga przebudowy struktury fabularnej. Wszystko to 1–3 zdaniowe mosty lub zamiany terminów.

---

**Końcowy werdykt:**
Baśń ma bardzo niską liczbę niespójności jak na tekst ~120 tys. znaków. Wykryte problemy są naprawialne w jeden dzień pracy redakcyjnej. Po naprawie P0 i P1 tekst osiągnie poziom spójności profesjonalnej publikacji.
