# Rad Bio Q&A Practice

Static, encrypted question-bank app for GitHub Pages.

## Contents

- `index.html`: self-contained interactive app with encrypted question data
- `validation.json`: extraction and answer-key validation summary
- `.nojekyll`: keeps GitHub Pages from applying Jekyll processing

## Use

Open `index.html` in a browser, or serve this folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy To GitHub Pages

1. Create a new GitHub repository.
2. Upload these files to the repository root.
3. In repository settings, enable GitHub Pages from the default branch root.

The password is not stored in this project. Keep the separately generated password private.

## Validation

- Questions: 337
- Answer-key rows: 337
- PDF explanations: 337
- Blocking validation issues: 0
- Recorded source corrections: 4

Static GitHub Pages cannot provide server-side access control. This app encrypts the payload client-side, so the question text is not readable from page source without the password.
