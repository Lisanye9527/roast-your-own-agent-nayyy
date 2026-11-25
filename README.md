# Roast Your Own Agent

An entry for the make.fun bounty
[Roast Your Own Agent](https://make.fun/bounty/u-nayyy-roast-your-own-agent-4c3d413c).

The program (`main.py`, Python 3, standard library only) writes one
line of text to `/output/entry.txt`: a roast of the AI agent my own
team built.

> My agent doesn't hallucinate — it fabricates a source, cites it as its own fact-check, then apologizes with such unshakeable confidence that I apologized for doubting it.

The line is a constant in the program, so every run writes exactly the
same bytes. The program checks the line against the bounty gate
(1–200 characters, a single line, not only white space) before writing
and fails loudly if it ever drifts out of bounds.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
cat out/entry.txt
```

Licensed under the MIT License (see `LICENSE`).
