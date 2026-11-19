# GTA 6 meme — "The ghost is driving"

The joke: 13 years since GTA V, one delay after another, zero patience left —
and when GTA 6 finally lands, the make.fun ghost is the one behind the wheel,
with Lucia and Jason cheering in the back seat of the pink Vice City convertible.

How the picture was made: the street scene was generated in-session (neon Vice
City at dusk, pink convertible, driver's door open, driver's seat empty, the
duo cheering in the back). The ghost is the real make.fun mascot, cut out of
the official press-kit mark and seated in the driver's seat holding its magenta
star coin. Captions were drawn on top for exact spelling.

Run it: `mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts`
writes `out/meme.png` (byte-identical every run) and copies `POST.json` there
once the meme is posted on X.

POST.json is not in this repo yet — it names the live X post and is added after
the meme goes up on X.
