# 📌 IT-Support Troubleshooting Guide

Willkommen zu deinem **IT-Support Troubleshooting Guide**! 🎯
Dieses Repository enthält eine Sammlung typischer IT-Probleme für **Windows & Linux** sowie Lösungen und Automatisierungsskripte.

## 📁 Projektstruktur
```
IT-Support-Troubleshooting-Guide/
│── 📜 README.md  (Projektbeschreibung)
│── 📂 docs/       (Markdown-Dokumentation zu Fehlern & Lösungen)
│── 📂 scripts/    (PowerShell & Bash Skripte für Automatisierung)
│── 📂 logs/       (Beispiele von Windows/Linux Logs zur Analyse)
│── 📂 tools/      (Links zu hilfreichen IT-Tools)
│── 📂 assets/     (Screenshots & Diagramme für Dokus)
```

---

## 🔧 Typische IT-Probleme & Lösungen

### **Windows: Netzwerkprobleme lösen**
📌 **Problem:** Kein Internetzugang, obwohl das Netzwerk aktiv ist.

✅ **Lösung:**
1. **Netzwerkverbindung prüfen:**  
   ```powershell
   ipconfig /all
   ```
2. **DNS-Cache leeren & Netzwerk zurücksetzen:**
   ```powershell
   ipconfig /flushdns
   netsh int ip reset
   netsh winsock reset
   ```
3. **Firewall & Antivirus überprüfen** (Blockierung ausschließen).
4. **Router & Adapter zurücksetzen.**

---

### **Linux: „Permission Denied“ Fehler**
📌 **Problem:** Datei oder Verzeichnis kann nicht geöffnet oder ausgeführt werden.

✅ **Lösung:**
1. **Rechte des Files prüfen:**
   ```bash
   ls -l datei.sh
   ```
2. **Ausführungsrechte setzen:**
   ```bash
   chmod +x datei.sh
   ```
3. **Mit root-Rechten ausführen:**
   ```bash
   sudo ./datei.sh
   ```

---

## 📂 Geplante Features
✅ **PowerShell & Bash Skripte für häufige IT-Aufgaben** (Netzwerkdiagnose, Benutzerverwaltung, Backup)  
✅ **Markdown-Dokumentation für weitere IT-Probleme & Lösungen**  
✅ **Windows Event Logs & Linux System Logs analysieren**  
✅ **Liste mit nützlichen Open-Source IT-Tools**

---

### 📌 **Mitmachen & Repository nutzen**
📥 Klone das Repository und erweitere es mit eigenen Erfahrungen:
```bash
git clone https://github.com/deinname/IT-Support-Troubleshooting-Guide.git
```
🚀 **Feedback & Pull Requests willkommen!**
