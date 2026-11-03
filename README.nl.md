# IRIS

**Identity, Roles & Integrated Sessions.** Een demo van geautomatiseerd gebruikersbeheer voor de systemen uit de XENA-demo's: van het personeelsdossier tot het besluit op een stuk, zonder handwerk per systeem. De naam verwijst naar Iris, de boodschapper van de Griekse goden.

IRIS hoort bij XENA, naast de demo over opslag, MIRA (de assistent in het kantoorpakket), TINA (het zoekportaal voor inwoners), ELSA (e-mailarchivering), MAIA (chatarchivering) en VERA (waarmerken). De demo is bedoeld voor IT-beheer, security en architecten.

> Een demo, geen product. Personen, stukken en aantallen zijn verzonnen.

English version: [README.md](README.md)

## Wat de demo laat zien

| Weergave | Wat je ziet |
|---|---|
| **Levenscyclus** | In dienst, interne overstap, extra bevoegdheid, uit dienst en samenwerking met een andere gemeente. Stap voor stap, nu met de hand per systeem en straks geautomatiseerd, met wat er achterblijft. |
| **Toegang** | Kies een persoon, een stuk en een handeling. Het besluit van nu (rollen en ACL's per toepassing) staat naast dat van een beleidsbeslispunt, met de AuthZEN-vraag en het antwoord. |
| **Architectuur** | De lagen: HR, Saviynt voor identity governance, Entra ID als identiteitsbron, Keycloak voor sessies en tokens, een beslispunt voor de besluiten en de toepassingen als handhavingspunt. Met de stappen bij aanmelden, handelen namens de medewerker, een toegangsbeslissing, uit dienst, hercertificering en een inwoner bij TINA. |
| **Techniek** | Componenten, de koppeling per systeem uit de demo's, de modellen van RBAC tot beleid, ontwerpregels en standaarden. |
| **Groeipad** | Acht stappen, beginnend met een rolcatalogus voor de demo-systemen. |
| **Help** | Weergaven, veelgestelde vragen en begrippen. |

## Gebruiken

Open `index.html` in een browser. De taal kies je rechtsboven, of met `#de`, `#en` of `#fr` achter de URL.

## Samenstellen

```
python3 build.py [JJJJ-MM-DD]
```

De bron staat in `src/demo.html`, de vertalingen in `i18n/`. Het versienummer staat in `VERSION`; wijzigingen in `CHANGELOG.md`.

## Licentie

European Union Public Licence (EUPL) 1.2. © 2026 Gemeente Haarlem.
