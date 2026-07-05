# Mochaboard QMK Target

This keyboard folder was derived from the PCB fabrication outputs in this repo.

Electrical mapping:

- Rows: `GP0`, `GP1`, `GP2`, `GP3`, `GP4`
- Columns: `GP5` through `GP18`
- Diodes: `COL2ROW`

Build with:

```sh
qmk compile -kb mochaboard -km default
```
