# Codex port

Based on Jakeschincariol/instagram-agent-skill, commit d03c56bb598be770c60b201f94237e5d1a4268a6 (MIT). The original license, attribution, scripts and reference data are retained. The Claude plugin manifests are retained for provenance, not used by Codex. Install only the 13 individual directories under skills/ as siblings in the intended Codex .agents/skills directory. Invoke explicitly with $ig-…; each has allow_implicit_invocation: false.

This port uses draft-only engagement, no authenticated browsing or downloads, user-supplied examples for ig-viral, and opt-in project-local files only. Python helpers were not run. English heuristics and limited treatment of accented text affect PT-BR; upstream hook validation is weak (reported AUC 0.56). Judge suggestions as drafts, not as predictions. The ig-viral helper optionally reads the adjacent ig-reel hook definitions/scorer.
