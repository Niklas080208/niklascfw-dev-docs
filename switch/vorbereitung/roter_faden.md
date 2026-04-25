---
icon: list-ordered
label: "Start: Roter Faden"
order: 1000
description: "Von Null bis lauffähiger CFW mit OmniNX als Hauptpfad. NiklasCFW Pack ist als Legacy-Fallback ganz unten verlinkt."
---

# Start: Roter Faden (0 → fertig)

Diese Seite ist der **rote Faden** durch die Dokumentation: Du kannst Schritt für Schritt vorgehen, unabhängig davon, ob du neu einsteigst oder nur einzelne Punkte nachschlägst.

!!!success Hauptpfad dieser Docs
**OmniNX ist ab jetzt der primäre Installationsweg** in dieser Dokumentation.  
Der **NiklasCFW Pack** bleibt als **Legacy/Deprecated-Fallback** erhalten und ist weiter unten separat verlinkt.
!!!

---

## Phase 1: Konsole & SD klären

[!ref](voraussetzungen/switch_ungepatcht_check)
[!ref](voraussetzungen/richtige_sd)
[!ref](sd_format)

---

## Phase 2: RCM und erster Payload

**RCM Softmod** (dein System wählen):

[!ref text="Windows"](rcm-methode/switch_v1_softmod_windows)
[!ref text="macOS"](rcm-methode/switch_v1_softmod_mac)
[!ref text="Linux, Android, ChromeOS"](rcm-methode/switch_v1_softmod_linux)

Damit erreichst du **Hekate** bzw. den ersten Start über Payload – Grundlage für alles Weitere.

---

## Phase 3: Backup (dringend empfohlen)

Bevor du System- oder emuMMC-Daten veränderst: **SysNAND sichern**.

[!ref](../system-backup/nand_backup)
[!ref](../system-backup/nand_backup_restore)
[!ref](../system-backup/sd_partition_backup_restore)

---

## Phase 4: OmniNX installieren (primärer Pfad)

### 4.1 Überblick und Varianten

[!ref](omninx/einfuehrung)

### 4.2 Voraussetzungen-Check (optional)

Wenn du Phase 1 und 2 komplett erledigt hast, kannst du den OmniNX-Check meist direkt überspringen.  
Die Seite ist trotzdem praktisch als kompakte Gegenprüfung:

[!ref](voraussetzungen/voraussetzungen.md)

### 4.3 Download und Dateien auf SD kopieren

[!ref](omninx/download)

### 4.4 OmniNX installieren

[!ref](omninx/installation_omninx)

### 4.5 emuMMC erstellen

[!ref](omninx/emummc_erstellen)

### 4.6 Pack einrichten (Forwarder, Zeit, Basics)

[!ref](omninx/pack_einrichten)

### 4.7 Updates und optionale OC-Themen

[!ref](../updates/omninx-update)
[!ref](../updates/firmware-update)
[!ref](../overclocking)

---

## Phase 5: Nach der Einrichtung

[!ref](../nachher/autoboot_aktivieren)
[!ref](../nachher/auto_rcm_aktivieren)
[!ref](../nachher/forwarder_installieren)

---

## Legacy/Deprecated: NiklasCFW Pack (nur Fallback)

Der NiklasCFW Pack bleibt erreichbar, ist aber **nicht mehr der Standardpfad** dieser Docs.

[!ref](../niklascfw-pack/guide1.4.0)
[!ref](../niklascfw-pack/guide2)
[!ref](../niklascfw-pack/guide3)
[!ref](../niklascfw-pack/guide4)
[!ref](../niklascfw-pack/guide5)

Vertiefung: Ordner **„Gut zu wissen"**, **„Fehlerbehebung"**, **„Erweiterte Guides"** in der Seitenleiste.

---

## Kurzüberblick als Liste

1. Modell & SD → FAT32  
2. RCM + Payload  
3. **Backup**  
4. **OmniNX** installieren und einrichten  
5. Nachbereitung (Autoboot, Forwarder, …)  
6. Optional: **NiklasCFW Pack (Deprecated Fallback)**

Wenn du bei einem Schritt hängen bleibst, zuerst unter **Fehlerbehebung** nachschlagen oder die verlinkte Detailseite erneut komplett lesen.
