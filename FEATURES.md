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
