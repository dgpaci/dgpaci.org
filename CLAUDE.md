# dgpaci.org

Sito personale di Davide Paci, fatto con Hugo (nessun tema esterno: layout in `layouts/`, CSS in
`static/css/style.css`). Tono scherzoso ma professionale: niente CV online.

Vincoli (gli stessi di pasamedia): **nessun cookie e nessuna risorsa di terzi** (solo font di
sistema, niente analytics, embed o CDN). Telefono e indirizzo non compaiono da nessuna parte; il
cliente principale non va nominato.

- **Maintainer**: Davide Paci (`dgpaci`).
- **Branch**: `main`, push diretti senza pull request (progetto personale, un solo autore).
- **Lingua**: italiano per testi, commenti, issue e PR; identificatori e commit in inglese.
- **Forge**: GitHub, `dgpaci/dgpaci.org`, CLI `gh`. Deploy con GitHub Actions su GitHub Pages
  (`.github/workflows/hugo.yml`), dominio in `static/CNAME`.

Contenuti: `content/cammino/` sono i post del Camino de Santiago (agosto 2026) recuperati da
Facebook, testo originale; la riflessione finale di ogni giorno sta nello shortcode `lezione`.
Foto: da aggiungere dagli originali, in `static/img/cammino/`.
