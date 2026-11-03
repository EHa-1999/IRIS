# IRIS

**Identity, Roles & Integrated Sessions.** A demo of automated user management for the systems in the XENA demos: from the HR record to the decision on a document, without manual work per system. The name refers to Iris, messenger of the Greek gods.

IRIS belongs to XENA, alongside the storage demo, MIRA (the assistant in the office suite), TINA (the search portal for residents), ELSA (e-mail archiving), MAIA (chat archiving) and VERA (sealing). It is aimed at IT operations, security and architects.

> A demo, not a product. People, documents and numbers are invented.

Nederlandse versie: [README.nl.md](README.nl.md)

## What the demo shows

| View | What you see |
|---|---|
| **Lifecycle** | Joining, internal move, extra authority, leaving and collaboration with another municipality. Step by step, today by hand per system and later automated, with what is left behind. |
| **Access** | Pick a person, a document and an action. Today's decision (roles and ACLs per application) next to that of a policy decision point, with the AuthZEN request and response. |
| **Architecture** | The layers: HR, Saviynt for identity governance, Entra ID as identity source, Keycloak for sessions and tokens, a decision point for decisions and the applications as enforcement points. With the steps for signing in, acting on behalf of the employee, an access decision, leaving, recertification and a resident on TINA. |
| **Technology** | Components, the integration per system in the demos, the models from RBAC to policy, design rules and standards. |
| **Growth path** | Eight steps, starting with a role catalogue for the demo systems. |
| **Help** | Views, frequently asked questions and terms. |

## Use

Open `index.html` in a browser. Pick the language at the top right, or add `#de`, `#en` or `#fr` to the URL.

## Build

```
python3 build.py [YYYY-MM-DD]
```

The source is in `src/demo.html`, translations in `i18n/`. The version number is in `VERSION`; changes in `CHANGELOG.md`.

## Licence

European Union Public Licence (EUPL) 1.2. © 2026 Gemeente Haarlem.
