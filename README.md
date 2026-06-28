# TRENER — Coach Elite (HYROX)

System współpracy trenerskiej. Cel zawodnika: **HYROX Solo, Masters 40-44, sub-1:15 —
listopad 2026, Poznań.**

Prowadzi **Coach Elite** — trener z 25-letnim stażem, specjalizacja HYROX. To repo jest
**pamięcią współpracy**: profil zawodnika, wskaźniki fizjologiczne, log sesji, raporty
i protokoły. Każda sesja zaczyna się od wczytania [`CLAUDE.md`](CLAUDE.md).

## Struktura

```
CLAUDE.md                      # Rdzeń pamięci: rola + kontekst + zasady pracy
zawodnik/
  profil.md                    # Dane stałe: cel, kategoria, kontekst zdrowotny
  wskazniki-fizjologiczne.md   # HRmax, LTHR, strefy, VO₂, HRR, tempa, testy
  dane-sesje.md                # Log sesji (HR, TRIMP, VO₂, HRR) — trendy
  flagi-otwarte.md             # Co czeka na rozstrzygnięcie / brakujące dane
protokoly/                     # Plany treningowe, periodyzacja, suplementacja
raporty/                       # Raporty wytrenowania (HTML + streszczenia MD)
```

## Status (28.06.2026)
- Faza 1 (Baza Z2) zamknięta. Pierwszy raport: [`raporty/`](raporty/).
- 🔴 **Flaga blokująca:** diagnoza zdarzenia 17.06 (RPE 9 przy normalnym tętnie) —
  rozstrzygnąć przed powrotem do intensywności. Szczegóły: [`zawodnik/flagi-otwarte.md`](zawodnik/flagi-otwarte.md).
- Następny krok: przejście do Fazy 2 — odwrócenie proporcji obciążenia (bieg/cardio > mata).

## Poufność
Materiał zawiera dane zdrowotne (TRT, wyniki lab) — do użytku własnego zawodnika.
