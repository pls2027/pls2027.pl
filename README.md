# Polska Loteria Sejmowa 2027 — Nowoczesna strona

Strona zbudowana w **Astro + Tailwind CSS v4**.

## Jak uruchomić lokalnie

1. Zainstaluj zależności:
   ```bash
   npm install
   ```

2. Uruchom serwer deweloperski:
   ```bash
   npm run dev
   ```

3. Otwórz http://localhost:4321

## Dodawanie grafik

Wrzuć swoje obrazy do folderu `public/images/`:

- `hero-poster.jpg` — główny plakat z ręką i losem (do sekcji Hero)
- `protest.jpg` — zdjęcie manifestacji (opcjonalnie do użycia w sekcjach)
- Inne grafiki z załączników

Następnie zaktualizuj ścieżki w pliku `src/pages/index.astro` (sekcja Hero ma już przygotowane tło).

## Funkcje dodane

- Nowoczesny, responsywny design w ciemno-czerwonej kolorystyce ruchu
- Pełna treść z Twojej oryginalnej strony
- **Rejestr Kandydatów** z mockami + możliwość oceny
- **Formularz zapisu do losowania**
- **Sekcja współpracy nad dokumentami** (propozycje + głosowanie społeczności)
- **Licznik podpisów** + przycisk do petycji
- **Asystent AI** (prosty chat z regułami — można rozbudować o prawdziwe API)
- Linki do social media (YouTube, X, TikTok — uzupełnij linki)
- Płynna nawigacja i animacje

## Co dalej? (zalecenia)

1. **Backend** — podłącz Supabase lub Firebase:
   - Rejestracja użytkowników
   - Baza kandydatów + oceny
   - Zapis do losowania
   - System propozycji zmian w dokumentach

2. **Autentykacja** — logowanie przez Google / email

3. **Prawdziwy AI** — podłącz Grok API, OpenAI lub inny model do asystenta

4. **Formularze** — połącz z Formspree, Resend lub własnym backendem

5. **Domeny i hosting** — Vercel lub Netlify (Astro działa idealnie)

## Struktura projektu

```
pls2027/
├── src/
│   ├── pages/
│   │   └── index.astro     ← Główna strona
│   ├── layouts/
│   │   └── Layout.astro
│   ├── components/         ← Tu możesz dodawać nowe komponenty
│   └── styles/
│       └── global.css
├── public/
│   └── images/             ← Tu wrzuć grafiki
├── astro.config.mjs
└── package.json
```

Powodzenia! Jeśli potrzebujesz więcej sekcji, zmian lub pomocy z backendem — daj znać. 

# Prawdziwa demokracja zaczyna się od Ciebie.