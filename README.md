# om3-enso

Exploratory, single-author work on the **ENSO response of the equatorial Pacific** in forced
ACCESS-OM3 runs, with ACCESS-OM2 as a benchmark.

This is a working sandbox, not a paper repo. Anything that becomes a figure for the ACCESS-OM3
description paper gets ported as a clean notebook to
[access-om3-paper-1](https://github.com/ACCESS-Community-Hub/access-om3-paper-1).
The discussion happens in [access-om3-paper-1#220](https://github.com/ACCESS-Community-Hub/access-om3-paper-1/issues/220).

**Status:** early and exploratory. Results here are preliminary and unreviewed.

## Runs

- OM3 `MC_25km_jra_iaf+wombatlite-test5.1-8f50b769`
- OM3 `MC_25km_jra_iaf+wombatlite-test4-d28e0359`
- OM2 `025deg_jra55_iaf_omip2_cycle1`

All three are forced by JRA55-do. The data is on NCI Gadi.

## Layout

- `notebooks/`: one notebook per diagnostic. Each calls functions from a flat module, one per cell.
- `docs/`: notes and the pipeline diagram (once there is a pipeline).

## Environment

```bash
module use /g/data/xp65/public/modules
module load conda/analysis3-26.08
```
