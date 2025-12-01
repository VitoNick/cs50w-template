CS50w Project

Setup
Windows (PowerShell):
    .\scripts\setup.ps1
    On Windows, run setup and activate the venv in PowerShell. Use Git Bash only for git commands if you prefer.
macOS / Linux:
    bash scripts/setup.sh

Run server:
    python manage.py runserver

Notes
- requirements.txt = runtime packages
- requirements-dev.txt = optional dev tools
- .venv is local and ignored by Git
- Git Bash activation (Windows):
    bash scripts/activate-bash.sh
