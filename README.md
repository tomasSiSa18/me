# me

Personal repository: my CV, my landing page, and whatever else I end up needing a home for.

## Contents

- `cv/` — CV in LaTeX (Awesome-CV template), one folder per language.
  - `cv/en/cv.tex` — English
  - `cv/es/cv.tex` — Spanish

More (landing page, etc.) to come.

## Building the CV

Requires `xelatex` (uses `xeCJK` for Japanese text).

```
cd cv/en   # or cv/es
xelatex cv.tex
```
