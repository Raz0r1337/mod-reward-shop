# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore
## Ingame Belohnungssystem 

Belohnungssystem  [AzerothCore](http://www.azerothcore.org)

- Aktueller Build-Status mit azerothcore: [![Build Status](https://github.com/azerothcore/mod-reward-shop/workflows/core-build/badge.svg?branch=master&event=push)](https://github.com/azerothcore/mod-reward-shop)

Aktuelle Funktionen:

- Dieses Modul veranlasst einen NPC, eine Datenbankprüfung für einen Code durchzuführen, der im Spiel eingelöst werden kann. Der NPC überprüft, welche Aktion in der Datenbank aufgerufen wird, um die richtigen Gegenstände/Funktionen anzuwenden.

Datenbankaktionen:

1 = Item
2 = Gold
3 = Namensänderung
4 = Faktionsänderung
5 = Rassenänderung
6 = Level Up auf 80

Kommende Funktionen:
### 1) Wenn jemand glaubt, dass er eine Website erstellen könnte, die mit diesem Modul funktioniert, wäre das großartig. Ich werde sie in den Quellcode integrieren und auch die Urheberschaft angeben.


## Requirements

Das Reward Shop-Modul erfordert derzeit:

AzerothCore v1.0.1+

## How to install

### 1) Legen Sie das Modul einfach im Ordner „modules” Ihres AzerothCore-Quellordners ab.

### 2) Geben Sie die SQL-Datei in die Charakterdatenbank ein.

### 2a) Optional können Sie alle AC-Code-NPCs austauschen: Geben Sie die SQL-Dateien aus dem optionalen Ordner in die Weltdatenbank ein. Verwenden Sie zuerst die NPC.sql-Dateien und dann die Spawn.sql-Datei.

### 3) Führen Sie cmake erneut aus und starten Sie einen sauberen Build von AzerothCore.

**Das ist alles.**

### (Optional) Modulkonfiguration bearbeiten

Wenn Sie die Modulkonfiguration ändern müssen, gehen Sie zu Ihrem Serverkonfigurationsordner (z. B. **etc**), kopieren Sie `reward_shop.conf.dist` nach `reward_shop.conf` und bearbeiten Sie die Datei nach Ihren Wünschen.

# Zeigen Sie Ihre Wertschätzung
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=SBJFTAJKUNEXC)


