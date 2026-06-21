## Position (System-Hinweis)

- pos12: 0–11        (Position im 12‑Raum)
- pos4: 0–3          (Position im 4‑Raum)
- next12: (pos12+1)%12   → wer ist der nächste im 12‑Kreis
- prev12: (pos12+11)%12  → wer ist der vorherige im 12‑Kreis
- next4: (pos4+1)%4      → wer ist der nächste im 4‑Band
- prev4: (pos4+3)%4      → wer ist der vorherige im 4‑Band

Hinweis:
Diese Werte dienen nur der Orientierung für Operatoren.
2UX führt keine Logik aus und interpretiert diese Werte nicht.
