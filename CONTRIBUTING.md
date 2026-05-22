# Guia de Contribució (Normes del Projecte)

Per assegurar un correcte manteniment del codi, la traçabilitat i l'eficiència digital, tots els membres del grup han de seguir les següents directrius:

## 🔒 Seguretat i Gestió de Secrets
- **PROHIBIT fer hardcoding de l'API Key:** Sota cap concepte es pot escriure la clau de l'API directament en el codi font públic.
- S'ha de fer servir obligatòriament el mòdul `userdata` de Google Colab: `userdata.get("GOOGLE_API_KEY")`.

## 🔄 Estàndard de Commits (Conventional Commits)
Quan pugis canvis a GitHub, utilitza els següents prefixos per saber exactament què s'ha modificat:
- `feat:` Per a noves funcionalitats (Exemple: `feat: Disseny inicial de l'assistent virtual`)
- `fix:` Per a correcció d'errors (Exemple: `fix: Correcció de filtre buit a l'input`)
- `docs:` Per a actualitzacions de documentació (Exemple: `docs: Actualització del README`)

## 🌿 Bones Pràctiques de Programació
- Cada línia de codi suggerida per la IA com a copilot ha de ser compresa, revisada i justificada de forma crítica per l'equip abans de ser integrada.
- S'ha d'utilitzar `.strip()` a les entrades de text de l'usuari per evitar errors de caràcters buits.
- Totes les crides de l'API han d'anar dins d'un bloc `try/except` per gestionar correctament possibles fallades de xarxa o quota.
