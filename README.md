# LED Studio Plugins

Katalog der Plugins, die [LED Studio](https://github.com/Knirpslarsi/LED-Studio) unter **Plugins → Plugins entdecken**
anzeigt.

## Eigenes Plugin eintragen

1. Plugin bauen und als öffentliches GitHub-Repo veröffentlichen – Anleitung:
   [docs/plugins.md](https://github.com/Knirpslarsi/LED-Studio/blob/main/docs/plugins.md).
2. Pull Request auf diese `plugins.json` mit einem Eintrag:

```json
{"repo": "dein-name/mein-plugin", "name": "Meine Effekte", "author": "Dein Name", "description": "Kurz, was es kann."}
```

Plugins können nur Effekte (abgeschottetes JavaScript) und Vorlagen enthalten.
