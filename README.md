# 30-compliance_agent

Outil de recherche de conformité réglementaire européenne. Un agent IA (recherche web restreinte à eur-lex.europa.eu et ec.europa.eu) analyse quelles réglementations UE (RGPD, AI Act, CSRD, marquage CE...) s'appliquent à une entreprise/un secteur donné, puis convertit l'analyse en rapport Word (.docx) mis en forme (page de titre, titres, listes, pied de page).

## Tech stack

agno (Agent, Groq, ExaTools, ReasoningTools), python-docx, python-dotenv

## Lancer le projet

```bash
pip install agno python-docx python-dotenv
```

Créer un `.env` avec `GROQ_API_KEY=...` (et optionnellement `EXA_API_KEY=...`)

```bash
python main.py
```
