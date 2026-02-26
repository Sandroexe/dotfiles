# 💻 [SYSTEM_CONFIG] // dotfiles

![OS](https://img.shields.io/badge/OS-CachyOS%20(Arch)-0b3b44?style=flat-square&logo=archlinux)
![Shell](https://img.shields.io/badge/Shell-Fish-4CAF50?style=flat-square&logo=gnu-bash&logoColor=white)
![Manager](https://img.shields.io/badge/Managed_by-GNU_Stow-blue?style=flat-square)

> **"There is no place like `~/`"** 🏠

Willkommen in meinem persönlichen Dotfiles-Repository. Hier speichere und verwalte ich meine Systemkonfigurationen, Scripte und Terminal-Anpassungen. 

Dieses Setup ist auf maximale Effizienz, ein sauberes Dark-Mode/Neon-UI und einen reibungslosen Workflow ausgelegt.

## 🖥️ System Specs (Current Status)

| Komponente | Setup |
| :--- | :--- |
| **OS** | CachyOS x86_64 (Arch-based) |
| **DE / WM** | GNOME 49.4 (Wayland) / Mutter |
| **Shell** | fish 4.5.0 🐟 |
| **Theme** | Adwaita [GTK2/3] |

## 📂 Repository Struktur

Aktuell verlinkte und gesicherte Konfigurationen:

```text
.dotfiles/
└── fish/                 # Angepasste Fish-Shell Config & Variablen
```

## ⚙️ Deployment & Installation

Das Klonen und Anwenden dieser Konfiguration ist dank **GNU Stow** in Sekunden erledigt. Stow erstellt automatische Symlinks in die jeweiligen `~/.config/`-Verzeichnisse.

```bash
# 1. Repository in das Home-Verzeichnis klonen
git clone [https://github.com/Sandroexe/dotfiles.git](https://github.com/Sandroexe/dotfiles.git) ~/.dotfiles
cd ~/.dotfiles

# 2. GNU Stow installieren (falls nicht vorhanden)
sudo pacman -S stow

# 3. Konfigurationen aktivieren (Symlinks setzen)
stow fish
```

---
*Gebaut mit Leidenschaft, viel Kaffee und Arch Linux / CachyOS. 🐧*
*Zurück zum Hauptquartier: [exemail.at](https://exemail.at)*
