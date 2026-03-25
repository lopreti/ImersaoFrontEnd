# Copilot Instructions for aluraProjeto

## 1. Project snapshot
- Single-page front-end prototype in `index.html`.
- Portuguese locale (`lang="pt-br"`, heading `Quem está assistindo?`).
- No JS/CSS assets in repo yet; HTML currently structure-only.

## 2. What to change
- Keep semantic HTML. Add new elements to `<main>`.
- Avoid introducing frameworks unless asked; project looks intended for vanilla practice.

## 3. Naming style & conventions
- Use Portuguese labels in UI text to match existing locale.
- Title currently set to "Netflix" so maintain consistent theming when adding features.

## 4. Additions expected in this repository
- New files should be at root (`style.css`, `app.js`) unless features require folders.
- Update `README.md` with simple instructions (serve with live server or open directly).

## 5. Developer workflow (discovered)
- No build/test scripts present.
- Local run: open `index.html` or use `Live Server` extension in VS Code.

## 6. Integration & data-flow hints
- There are no API calls currently. If adding dynamic behavior, local data arrays in `app.js` are recommended.

## 7. AI behavior in repo context
- Prefer minimal incremental changes for this simple scaffold.
- Include reasoning in PR-style comments: e.g., "Adiciona cards de perfil no main para comportar múltiplos usuários".

## 8. No-op guard
- If the user asks for tests/build steps, explain the project contains no tooling yet and suggest adding a `package.json` + `npm` scripts.

## 9. Ask for feedback
- After applying changes, verify indices and run in browser.
- Ask the maintainer if they want to expand to a modular app (common in Alura Front-end immersion).