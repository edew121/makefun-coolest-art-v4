# The Door in the Lake, Wide Open

Entry for make.fun **coolest-art-01** — "Make the coolest art" ($250, deadline 2026-11-13 10:00 UTC).

The same door from the earlier "The Door in the Lake": an enormous
freestanding wooden door stands in the middle of a vast still lake at deep
blue dusk — but now it stands open much wider, revealing a bright golden
world beyond it, warm light spilling out across the water in a long shining
path. A tiny lone figure rows a small boat along the golden path toward the
door. One idea, one mood: deep teal-blue night against a single radiant
gold — readable even at 300 px wide.

## How it works

`main.py` (Python 3.13, standard library only) copies the bundled artwork
`entry.png` to `/output/entry.png`, then verifies the output is a non-empty
JPEG by its magic bytes. No network, fully deterministic — every run writes
the same bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Files

- `main.py` — the entry program
- `entry.png` — the artwork (JPEG bytes, 1024×671, 104,735 bytes)
- `LICENSE` — MIT

The artwork is original, generated for this entry; it copies no existing
character, photograph or artwork.

## Iteration

This is the fourth entry for this competition from the same account. It
varies the earlier "The Door in the Lake": the same freestanding door in
the same lake at dusk, but opened much wider so the golden world beyond
fills the frame, with a stronger teal-versus-gold contrast and a clearer
little rowboat on the shining path. The idea stays one door, one lake, one
mood — only the light is bolder.
