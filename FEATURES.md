# Built-in features for robo-grove-os

Purpose: robotics

1. **prepare a technical project** — run robo-grove-os-workspace. It creates ~/Documents/robo-grove-os-workspace/ with Design, Builds, Logs folders.
2. **plan a build or maintenance session** — run robo-grove-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/robo-grove-os-session-plans/.
3. **check technical change readiness** — run robo-grove-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/robo-grove-os-workspace features/robo-grove-os-plan features/robo-grove-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for robotics:

1. **KiCad** — org.kicad.KiCad
2. **Arduino IDE 2** — cc.arduino.IDE2
3. **Blender** — org.blender.Blender

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for robotics:

1. **FreeCAD** — design mechanical parts (org.freecadweb.FreeCAD)
2. **OpenSCAD** — model parametric 3D parts in code (org.openscad.OpenSCAD)
3. **PrusaSlicer** — prepare models for 3D printing (com.prusa3d.PrusaSlicer)
4. **DB Browser for SQLite** — inspect SQLite databases (org.sqlitebrowser.sqlitebrowser)
5. **Wireshark** — inspect network traffic (org.wireshark.Wireshark)
6. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
7. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
8. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
9. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
10. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
