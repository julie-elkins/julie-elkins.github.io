# Julie Elkins — public site

This is the small, static personal site for Julie Elkins' public work on AI
evaluation, assurance, and learning.

The site is intentionally separate from project repositories. It is a public
index and explanation layer, not a replacement for the documentation in each
project.

## Why a static site

The first release has no database, server, analytics, or build framework. That
keeps the site inexpensive to host, easy for a learner to inspect, and easy to
deploy with GitHub Pages. A later hosted layer can add essays, research-paper
materials, and interactive demos without changing this public boundary.

## Local preview

From this directory, run a simple local web server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

The intended repository name is `julie-elkins.github.io`. GitHub Pages can serve
the repository root as the site. A custom domain can be added later by creating
a `CNAME` file containing the chosen domain and configuring the registrar's DNS
records.

## Public-content boundary

The site links only to public repositories and public channels and includes one
headshot supplied for this public site. It must not include private repositories,
employer-specific details, CERTI material, unpublished research, private paths,
internal screenshots, credentials, or internal logs.

