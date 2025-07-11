# IR-Device-DB – Offene Infrarot-Codes Datenbank

Dies ist eine frei nutzbare Datenbank für IR-Codes von Fernbedienungen und Geräten aller Art – inklusive TV, Receiver, Klimaanlagen, Projektoren u. v. m.  
Ziel ist es, eine zentrale, überprüfbare Quelle für DIY-Projekte mit ESP32, Arduino, Flipper Zero und Smart Home-Systemen zu schaffen.

---

## ✅ Projektziele

- **Sammeln** von IR-Codes aus freien Quellen und durch eigene Messungen
- **Strukturierte Ablage** nach Hersteller, Gerätetyp, Modell
- **Bereitstellung als JSON, CSV und optional SQLite**
- **Offene Nutzung** für private, kommerzielle oder forschende Zwecke

---

## 📁 Ordnerstruktur
ir-device-db/ 
├── devices/               # Einzelgeräte als JSON oder CSV │   
├── samsung/ │ 
├── lg/ │  
└── sony/
├── tools/                 # Arduino/ESP32-Scripts, Parser, Tools 
├── db/                    # Gesamtübersicht als index.json, SQLite usw.
├── LICENSE 
├── README.md
└── .gitignore

---

## 🧰 Tools enthalten

- **ESP32 IR-Empfänger** zum Aufzeichnen von Signalen
- **LIRC-Parser** zur Umwandlung existierender Linux-Remotes
- **Merge-Tools** zur Einbindung externer IRDBs

---

## 📜 Lizenz

- **Quellcode & Tools:** MIT License  
- **IR-Datenbank-Einträge:** Creative Commons Zero (CC0) – komplett gemeinfrei

Siehe [LICENSE](./LICENSE) für Details.

---

## 🙋‍♂️ Mitmachen

Pull Requests, Issues und neue IR-Datensätze sind jederzeit willkommen.  
Bitte stelle sicher, dass du die Quelle der IR-Daten dokumentierst, falls sie nicht selbst erfasst wurden.
