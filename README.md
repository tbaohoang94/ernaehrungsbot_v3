# Projekt: vorlagen

## Struktur
- **infra/** → Infrastruktur, Docker-Configs, Deploy-Skripte
- **app/** → Lokale Dateien, n8n Workflows
- **ops/** → Monitoring, Policies

## Nutzung
Lokal starten:
```
cd infra
make up
```

Production starten:
```
cd infra
make prod-up
```
