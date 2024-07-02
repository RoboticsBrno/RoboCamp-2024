# Jak na dokumentaci

## Instalace nástrojů
Budeme potřebovat:
- `git`
- `python3` + `pip` (na Windows doporučuji z Win storu)
- [nodejs](https://nodejs.org/en/download) + `npm` (je součástí instalace)

## Repo
Naklonujeme si repozitář:

```bash
git clone https://github.com/RoboticsBrno/RoboCamp-2024.git
```

## Konfigurace

Otevři projekt a v terminálu spusť:

```bash
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r requirements.txt
npm install
```

## Práce s dokumentací

Lokální spuštění dokumentace:
```
mkdocs serve
```

případně:
```
python3 -m mkdocs serve
```
