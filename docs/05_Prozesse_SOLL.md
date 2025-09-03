# Prozesse (SOLL)

```mermaid
flowchart LR
  P[Patient] --> T[Online-Termin buchen]
  T --> R[Reminder SMS/E-Mail]
  T --> D[Dokumentation in EPA]
  D --> V[Video-Sprechstunde optional]
  V --> A[Abrechnung]
```
