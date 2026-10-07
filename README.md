# Promethean

![Heinrich Friedrich Füger, Prometheus Brings Fire to Mankind, 1817](prometheus-brings-fire.jpg)

> **"Prometheus Brings Fire to Mankind"**, Heinrich Friedrich Füger, 1817. The torch is lit, the finger is at the lips, and the man on the left has not been switched on yet. Everything that follows this painting is the manual.

Long texts that made the world, the way they were meant to be read.

**[Enter the series ↗](https://promethean.nfnto.com/)**

---

## Why this exists

Every load-bearing idea you live inside arrived as a long text first. The railway timetable, the broadcast, the index fund and the model you asked something this morning were each argued into existence by someone with a desk and a problem, and most of that prose now survives as a scanned PDF with a coffee ring on page forty, opened by eleven graduate students a year.

The internet is very good at turning these works into quotes. A quote is the sign with its referent cut away, a sentence that travels well because it has stopped carrying the argument it came from. Promethean runs the other direction. It takes the whole text, sets it with the care a good print house would give it, and builds a reading apparatus around it so a modern reader can stay inside a hundred pages without drowning.

The name is the premise. Prometheus stole fire from Olympus, handed it to a species made of mud, and was chained to a rock in the Caucasus while an eagle ate his liver, which grew back every night so it could be eaten again in the morning. The Greeks meant it as a warning. We took the fire anyway, every generation, with a consistency that deserves to be honoured somewhere.

This is somewhere. Some of the works here celebrate the fire. Some keep a careful inventory of the burns. Both are written about the same animal.

---

## The series

| N° | Work | Author | Year | Length |
|:--:|------|--------|:----:|--------|
| 01 | [**The World as Phantom and as Matrix**](https://jcgaal.github.io/promethean/the-world-as-phantom-and-as-matrix/) | Günther Anders | 1956 | 5 chapters · 28 sections · 58 notes · about three hours |
| 02 | *In the forge* | | | |

### N° 01 · The World as Phantom and as Matrix

*Philosophical considerations on radio and television*, from the first volume of *Die Antiquiertheit des Menschen*, The Obsolescence of Man. Anders' argument, compressed past the point of fairness: once the world is delivered to your home, you stop going out to meet it, and the delivery starts deciding what the world is. He sets the whole trap in the epigraph, with a king who gives his wandering son a carriage and horses.

> "Now you do not need to walk", were his words. What they meant was: "You are no longer allowed to walk." The effective reality: "You can no longer walk."

He was writing about the television. You will probably read it on a phone.

---

## How a Promethean reading works

Each work is one self-contained HTML page. No framework, no build step, no account, no tracking. Open it and read.

What the page does while you read (subject to change on each publication):

- **The spine.** A rail down the left edge maps every chapter and marks where you are inside it. The series name at its foot takes you back to the contents.
- **The lectern** (`S`). Text size, typeface (Cormorant or EB Garamond), measure, leading, the Void and Vellum surfaces, a focus line that dims everything except the paragraph you are on, an ambient flame behind the text, and paragraph numbers for citing.
- **The index** (`I`, or `/` to search). Every section listed with its thesis, plus full-text search across the work.
- **The apparatus.** Notes gather in the side panel as their section scrolls into view, so a footnote stops being an errand to the bottom of the page.
- **Transmit** (`L`). Copies a link to the exact section you are reading, or opens the share sheet on a phone. Quote with the address attached.
- **Memory.** The page remembers where you stopped and offers to take you back. That bookmark lives in your browser and goes nowhere else.

`J` and `K` move between sections. `+` and `−` change the size. `F` toggles the focus line.

---

## Reading it locally

```bash
git clone https://github.com/jcgaal/Promethean.git
cd Promethean
python3 -m http.server 8000
```

Then open [localhost:8000](http://localhost:8000). Any static server works; the server matters because the works link to each other through folders, and a browser opening files straight off the disk will show you a directory listing where the contents should be.

The live site is GitHub Pages serving the root of `main`. There is nothing to compile, so what is in the repository is what is on the site.

---

## Structure

```
Promethean/
├── index.html                              The contents: name, premise, every work in the series
├── prometheus-brings-fire.jpg              Füger, 1817
└── the-world-as-phantom-and-as-matrix/     N° 01
    ├── index.html                          The whole reading, apparatus included
    └── assets/
        └── anders.jpg                      Pl. I, the subject
```

---

## House rules

The texts belong to their authors, their translators and their estates. Promethean sets them and owns none of them. Every work carries its provenance on the page: who wrote it, who translated it, from which edition. If you hold the rights to something published here and want it gone, [open an issue](https://github.com/jcgaal/Promethean/issues) and it goes, no argument.

Read slowly. The whole site is built on the assumption that you will.

---

## License

The code, meaning the pages, the styles and the scripts, is MIT. See [LICENSE](LICENSE). The texts remain under the rights of their authors and translators, as noted on each work.

Copyright (c) 2026 JC Gaal ([@jcgaal](https://github.com/jcgaal)).
