# scenes/

Scene configuration files (*.scfg) store saved object positions for each room.

## Format

Each `.scfg` file is JSON:

```json
{
  "room": "mezzanine",
  "version": 1,
  "objects": [
    { "name": "painting-collabdays-portugal", "x": 25.687, "y": 4.851, "z": 38.22 },
    { "name": "desk-group",                   "x": 42.6,   "y": 0.0,   "z": 57.6 }
  ]
}
```

## Usage

1. In the browser press `?mezzR&edit` (append to the URL).
2. **Right-click drag** to look around.
3. **Left-click** an object to grab it; move the mouse to drag it on its plane; **left-click** again to drop.
4. Press **`0`** to save — the browser downloads `mezzanine.scfg`.
5. Place the downloaded file in this folder (`public/scenes/`).

The game loads the `.scfg` automatically on next visit.
