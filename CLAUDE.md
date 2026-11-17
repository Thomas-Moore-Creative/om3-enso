# om3-enso — project context

Project-level instructions (layer 2): committed with this repo, changes over weeks.
Where this conflicts with my user-level CLAUDE.md, this file wins.
Task-by-task detail belongs in `scope/TASK-SCOPE-XX.md`, not here.

## Purpose
- Solo exploratory work on the ENSO response of the equatorial Pacific in forced ACCESS-OM3 runs
  (test4, test5.1), with ACCESS-OM2 0.25° as a benchmark. Discussed in
  ACCESS-Community-Hub/access-om3-paper-1#220.
- Outputs are for me and interested colleagues. Paper figures get ported to the paper repo
  (`../access-om3-paper-1`) as clean notebooks from its template, not developed there.

## Data
- OM3 test5.1: `/g/data/ol01/outputs/access-om3-25km/MC_25km_jra_iaf+wombatlite-test5.1-8f50b769/datastore.json`
- OM3 test4: `/g/data/ol01/outputs/access-om3-25km/MC_25km_jra_iaf+wombatlite-test4-d28e0359/datastore.json`
- OM2: `025deg_jra55_iaf_omip2_cycle1` via `intake.cat.access_nri`.
- Obs: see the inventory in the scope handover. Open and check names before use.
- Outputs: not decided. Keep data and figures out of git.

## Conventions
- Environment: `module use /g/data/xp65/public/modules; module load conda/analysis3-26.08`
- How to run: notebooks in ARE/JupyterLab. Login node is for light work only.
- Layout: flat module(s) at repo root or beside notebooks; notebooks in `notebooks/` call them one
  per cell.
- Pipeline diagram: none yet (`docs/` when there is a pipeline).
- Mode: interactive
- Job budget: none
- Repo rules that differ from my defaults:
  - **Public repo** under my account: no unreleased results or colleagues' unpublished comments
    in commit messages or README without checking with me. Results here are preliminary.
  - Single-author: pushing to `main` is fine once I say so.
  - Commit notebooks with outputs cleared.

## Current status
- Working: repo scaffold only.
- In progress: issue #220 posted (paper repo); next is the data inventory.
- Open questions / known issues: see scope task file.
- Last updated: 2026-11-17

## Current task
@scope/TASK-SCOPE-ENSO.md
