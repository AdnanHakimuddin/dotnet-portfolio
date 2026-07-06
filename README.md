# Adnan Hakimuddin — Senior .NET Developer Portfolio

Single-file portfolio (index.html) built from my resume: C#, .NET Core, ASP.NET Web API, SQL Server, Azure DevOps, CI/CD, Azure, AWS.

## Publish on GitHub Pages (as a second site)

You can host this alongside your other portfolio — each repo gets its own URL.

1. Go to https://github.com/new and create a repo, e.g. `dotnet-portfolio`.
2. Upload `index.html` (drag and drop → "Add file" → "Upload files") and commit.
3. **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
4. Live in 1–2 minutes at: `https://YOUR-USERNAME.github.io/dotnet-portfolio/`

If you'd rather make THIS your main site at `https://adnanhakimuddin.github.io`,
put this index.html in the `adnanhakimuddin.github.io` repo instead and move the
other portfolio to its own repo (e.g. `web-fixes`).

## Command line alternative

```bash
git init
git add index.html README.md
git commit -m "Senior .NET Developer portfolio"
git branch -M main
git remote add origin https://github.com/adnanhakimuddin/dotnet-portfolio.git
git push -u origin main
```

Then enable Pages as in step 3 above.

## Content notes

- Contact details (email, phone, LinkedIn) are already filled in from the resume.
- The hero shows an animated `GET /api/v1/engineers/adnan-hakimuddin` → `200 OK` JSON response.
- Add project links or a resume-download button anytime — just ask.
