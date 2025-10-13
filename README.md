# 📄 Joe Neglia — LaTeX Résumé Repository

This repository contains my LaTeX résumé along with archived versions automatically maintained through GitHub Actions.

Whenever I update `current/resume.tex` and push to the `main` branch, an automated workflow:

1. Builds a new PDF from the latest LaTeX source.
2. Moves the previous `resume.pdf` into the `archive/` directory with a timestamp.
3. Commits both the updated and archived files back to the repository.
