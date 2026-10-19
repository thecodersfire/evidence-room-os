# Built-in features for evidence-room-os

Purpose: digital forensics learning

1. **prepare study and research files** — run evidence-room-os-workspace. It creates ~/Documents/evidence-room-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run evidence-room-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/evidence-room-os-session-plans/.
3. **check study and source readiness** — run evidence-room-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/evidence-room-os-workspace features/evidence-room-os-plan features/evidence-room-os-check "$HOME/.local/bin/"
