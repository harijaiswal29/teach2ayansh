# teach2ayansh

Learning games for Ayansh, made from his school books. Each game is a single HTML file: open it in any browser (phone, tablet or laptop) and play. Progress is saved in that browser.

## How the repo is organised

One folder per subject, then one folder per topic. Each topic folder holds the game, a short README, and (for games built from a book chapter) `book-notes.md` with page-by-page notes and answers.

```
maths/
  multiplication/   Times Quest, Multiplication Fair (Chapter 9)
  time/             Tick-Tock Town (Chapter 10)
  subtraction/      Take-Away Bazaar (Chapter 8)
  patterns/         Rangoli Lane (Chapter 6)
  skip-counting/    Skip-Hop Park (Chapter 4)
english/
  the-rainbow/      Rainbow Bridge (Chapter 1)
  the-letter/       Snail Mail Trail (Chapter 4)
evs/
  growing-world-of-plants/  Little Seed's Journey (Chapter 4)
  world-of-animals/         Jungle Safari Trail (Chapter 5)
  rural-and-urban/          Village–City Express (Chapter 7)
  seasons-and-lifestyle/    Season Quilt Trail (Chapter 8)
  transport/                Ricky's Road Trip (Chapter 9)
```

See [maths/README.md](maths/README.md), [english/README.md](english/README.md) and [evs/README.md](evs/README.md) for the full lists.

## Games

| Subject | Topic | Game | Book chapter |
|---|---|---|---|
| Maths | Skip counting | [Skip-Hop Park](maths/skip-counting/) | Ch 4, pp. 7–23 |
| Maths | Patterns | [Rangoli Lane](maths/patterns/) | Ch 6, pp. 47–53 |
| Maths | Subtraction | [Take-Away Bazaar](maths/subtraction/) | Ch 8, pp. 7–27 |
| Maths | Multiplication | [Multiplication Fair](maths/multiplication/) | Ch 9, pp. 28–57 |
| Maths | Multiplication | [Times Quest](maths/multiplication/) | (not from the book) |
| Maths | Time | [Tick-Tock Town](maths/time/) | Ch 10, pp. 58–76 |
| English | The Rainbow | [Rainbow Bridge](english/the-rainbow/) | Ch 1, pp. 7–32 |
| English | The Letter | [Snail Mail Trail](english/the-letter/) | Ch 4, pp. 34–54 |
| EVS | The Growing World of Plants | [Little Seed's Journey](evs/growing-world-of-plants/) | Ch 4, pp. 7–22 |
| EVS | The Amazing World of Animals | [Jungle Safari Trail](evs/world-of-animals/) | Ch 5, pp. 22–38 |
| EVS | Rural and Urban Communities | [Village–City Express](evs/rural-and-urban/) | Ch 7, pp. 7–28 |
| EVS | Seasons and Lifestyle | [Season Quilt Trail](evs/seasons-and-lifestyle/) | Ch 8, pp. 29–44 |
| EVS | Transport | [Ricky's Road Trip](evs/transport/) | Ch 9, pp. 45–56 |

## Adding a new game

- New topic in an existing subject: make `<subject>/<topic>/`, add the game HTML, a README and `book-notes.md`, then add a row to the subject README and the table above.
- New subject (for example `science/`, like `evs/`): make the subject folder with its own README listing its topics, then follow the same pattern.

Every chapter game follows the same style: stops in book order using the book's own examples, up to 3 stars per stop, a Grand Review with a certificate at the end, and a "For grown-ups" section with tips.
