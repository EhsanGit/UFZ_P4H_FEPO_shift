# Northward shift of the predicted sandfly populations of the Iberian Peninsula (Climatic Change)

Manuscript for **Climatic Change** (Springer Nature), https://link.springer.com/journal/10584

- **Analysis and figures:** `git.ufz.de/planet4health/fepo_shift` (`src/`), plan of the study in `docs/PLAN.md` there
- **FEPO runs:** `git.ufz.de/climos/climos-recovery` (`scripts/fepo_run/run_year.sh`), FEPO branch `eve-ehsan-run`
- **FEPO method:** Soheili et al. (2025), Research Square, doi:10.21203/rs.3.rs-7852217/v1

The draft is written with the FEPO version of the CLIMOS runs; figures and numbers are replaced by the revised version
once it is ready. Placeholders are red (`\todo{...}`).

## Files

- `main.tex`: manuscript (Springer Nature template `sn-jnl`, option `sn-basic`: author-year references)
- `references.bib`: bibliography (entries marked `CHECK` still need their details)
- `figures/`: figures, copied from `fepo_shift/figures` (`fig_change_maps`, `fig_shift_trajectory_apr_oct`, ...)
- `sn-jnl.cls`, `sn-basic.bst`: Springer Nature style files (do not edit)

## Compile

```bash
latexmk -pdf main.tex
```

In Overleaf: main document `main.tex`, compiler pdfLaTeX.

Template source: https://www.springernature.com/gp/authors/campaigns/latex-author-support

---

Ehsan Modiri -- UFZ, 04.11.2026
