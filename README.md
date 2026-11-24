# dgpaci.org

Sito personale, Hugo ≥ 0.158.

```bash
hugo server        # anteprima su http://localhost:1313
hugo --gc --minify # build in public/
```

Nuovo contenuto: `hugo new note/titolo.md` (o `cinema/`). Il push su `main` pubblica su GitHub
Pages.

Prima pubblicazione: creare il repo `dgpaci/dgpaci.org`, attivare Pages con sorgente
"GitHub Actions", puntare il DNS di `dgpaci.org` a GitHub Pages (record A/AAAA dell'apex e
`www` CNAME verso `dgpaci.github.io`) e spuntare "Enforce HTTPS".
