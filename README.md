# 📧 Generator Stopki E-mail — Meritoros

Narzędzie do generowania firmowych stopek e-mail dla pracowników **MERITOROS SA**. Wystarczy wypełnić formularz i wkleić gotową stopkę do Outlooka.

---

## 🚀 Jak używać

1. Otwórz plik `meritoros-stopka.html` w przeglądarce (Chrome / Edge / Firefox)
2. Wybierz wersję językową: **PL / EN / UA / RU**
3. Uzupełnij swoje dane:
   - Imię i nazwisko
   - Stanowisko
   - Adres e-mail *(z walidacją formatu)*
   - Numer telefonu *(opcjonalnie)* — wybierz kierunkowy z listy
4. Kliknij **„Kopiuj stopkę do schowka"**
5. Wklej (`Ctrl+V` / `⌘+V`) do ustawień podpisu w kliencie pocztowym

---

## ✉️ Jak wkleić podpis

### Outlook (Web / Desktop)
1. Ustawienia → **Podpis** (lub *Signature*)
2. Utwórz nowy podpis lub edytuj istniejący
3. Kliknij w pole tekstowe podpisu i wklej (`Ctrl+V`)

### Gmail
1. Ustawienia (⚙️) → **Wszystkie ustawienia** → zakładka **Ogólne**
2. Przewiń do sekcji **Podpis**
3. Kliknij w pole podpisu i wklej (`Ctrl+V`)

---

## 🌍 Warianty językowe

| Wersja | Pozdrowienie | Klauzula poufności |
|--------|-------------|-------------------|
| 🇵🇱 PL | Pozdrawiam | PL |
| 🇬🇧 EN | Best regards | EN |
| 🇺🇦 UA | З повагою | UA |
| 🇷🇺 RU | С уважением | RU |

---

## 📋 Dane statyczne w stopce

Poniższe dane są wspólne dla wszystkich pracowników i nie podlegają edycji:

- **Firma:** MERITOROS SA
- **Adres:** Aleja Pokoju 62/8, 31-564 Kraków
- **Strona:** meritoros.pl
- **Social media:** Facebook · LinkedIn · Instagram

---

## 🛠️ Techniczne

- Jeden plik `.html` — zero zależności, zero serwera
- Stopka generowana jako pełny dokument HTML z inline styles — zgodny z Outlookiem i Gmailem
- Czcionka: **Arial** (wymuszona inline, odporna na podmianę przez klientów pocztowych)
- Kopiowanie przez `ClipboardItem API` (text/html) z fallbackiem dla starszych przeglądarek
- Telefon: jeśli pole jest puste — wiersz nie pojawia się w stopce

---

## 📁 Pliki

```
meritoros-stopka.html   # generator stopki (otwórz w przeglądarce)
README.md               # ten plik
```
