# Assetto Corsa controls (known-good)

Saved 2026-11-14 from `Documents\Assetto Corsa\cfg`.

- `controls.ini` is the active file (`cfg\controls.ini`).
- `default-preset.ini` is the preset (`cfg\controllers\savedsetups\default.ini`).

## Device numbers (JOY)

| JOY | Device |
|---|---|
| 7 | SimHub Control Mapper controller 1 |
| 8 | SimHub Control Mapper controller 2 |
| 5 | Forte Wheelbase (steering axis) |

The three "SimHub Controller Remapper Bridge" devices share the same name and USB IDs, so Content Manager can collapse them all onto JOY=3. If the bridge bindings in `controls.ini` show `JOY=3`, restore this file. Starting the game with `acs.exe` directly avoids the rewrite.
