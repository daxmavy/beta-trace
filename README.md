# beta-trace

A single static page showing how the pre-registered coefficient on summary stance
(and its 95% interval) moves as participants accumulate in the RQ6 persuasion study.

**Aggregate estimates only.** No participant identifiers, responses or free text are
published here; `beta_trace.json` contains nothing but `{n, trials, beta, se, lo, hi, p}`
per fit. The data itself lives elsewhere and is not part of this repository.

Regenerated and pushed by `analysis/persuasion_study/refresh_beta_site.sh` in the
thesis repo. Served at https://beta.maxdavy.com
