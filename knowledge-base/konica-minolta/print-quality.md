# Print Quality Diagnose – Konica Minolta

## 🧾 Allgemeine Grundsätze

- Ein Scan eines fehlerhaften Ausdrucks zeigt das Fehlerbild, aber nicht zwingend die Ursache.
- Visuelle Einschätzungen können irreführend sein.
- Immer zwischen Druckprozess und Scanbild unterscheiden.

---

## ⚠️ Typische Fehlinterpretationen

### Scan sieht nach Fusing-Problem aus
- Das Fehlerbild kann so aussehen, als ob die Fusing Unit defekt ist
- Tatsächlich kann die Ursache im Entwicklungssystem liegen

👉 Merksatz:
Ein gescanntes Fehlerbild ist KEIN sicherer Beweis für die Ursache

---

## 🛠️ Wichtige Baugruppen bei schwarzen Druckproblemen

- Developer Unit (Developing Unit)
- Imaging Unit
- Tonerzufuhr
- Transfer-Einheit
- Fusing Unit

---

## 🔍 Diagnose-Logik bei schwarzem Tonerauftrag

Wenn:
- großflächig schwarzer Toner auf dem Papier ist
- zusätzlich zum Text Flächen entstehen

Dann prüfen:

1. Betrifft es nur Schwarz?
2. Ist der Toner fixiert oder verschmierbar?
3. Tritt der Fehler bei allen Drucken auf?
4. Interne Testseite prüfen

---

## ⚙️ Service Mode Analyse (Konica Minolta)

Pfad:
Service Mode → State Confirmation → Table Number

Wichtige Werte:
- VDC
- VG

### Beispiel:
- VDC K = 254

👉 Interpretation:
- Hinweis auf Problem in der Developer Unit (Schwarz)
- möglicher Verschleiß oder Defekt

---

## ✅ Beispiel aus Praxis

### Problem:
Schwarze Ausdrucke mit flächigem Tonerauftrag

### Erste Vermutung:
Fusing Unit (durch Scanbild)

### Tatsächliche Ursache:
Developer Unit Schwarz defekt

### Lösung:
Developer Unit Schwarz ersetzt

### Erkenntnis:
- Scanbild irreführend
- Service Mode Werte entscheidend
``
