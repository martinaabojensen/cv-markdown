# Markdown CV & Cover Letters

Keep a base CV in Markdown and create role-specific branches for tailored applications. Edit in VS Code, track with Git, and export HTML/DOCX locally or via GitHub Actions.

## Structure
- `cv/base.md` — your main CV
- `cover-letters/template.md` — reusable cover letter template
- `certifications/certs.md` — running certification list
- `scripts/build.sh` — builds HTML/DOCX with pandoc
- `.github/workflows/build.yml` — CI build (optional)

## Branch workflow
Create role branches like `role/vp-sales`, make tweaks, and push:
```bash
git checkout -b role/vp-sales
git commit -am "Tailor CV for VP Sales"
git push -u origin role/vp-sales
