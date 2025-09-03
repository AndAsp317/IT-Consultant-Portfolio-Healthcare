# Power BI – Schnellstart (Healthcare)

1. **Get Data → Text/CSV**: `demo/data/Patients.csv` & `Appointments.csv` laden
2. Beziehungen: `Appointments.patient_id ↔ Patients.patient_id`
3. Beispiel-Measures:
   - `NoShow % = DIVIDE(CALCULATE(COUNTROWS(FILTER(Appointments, Appointments[status] = "keine_Anwesenheit"))), COUNTROWS(Appointments))`
   - `Avg Wait (min)` – falls Wartezeiten-Feld vorhanden
4. Visuals: Karte (No-Show %), Balken (Termine nach Typ), Tabelle (Termindetails)
