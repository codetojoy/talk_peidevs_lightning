# Nothing New Under the Sun
*A 7-minute lightning talk in three movements: paint, guitar, code*

**Thesis:** Purely new ideas are rare, and they may not matter. What matters is how you take a shared form (the box) and add your own note to it.

---

## Time budget

| Section | Time | Length |
|---|---|---|
| 1. Intro (cold open) | 0:00 – 0:20 | 20s |
| 2. Still-life paintings | 0:20 – 1:50 | 90s |
| 3. Guitar licks | 1:50 – 3:50 | 2:00 |
| 4. Tech examples | 3:50 – 6:20 | 2:30 |
| 5. Closing | 6:20 – 6:40 | 20s |
| Buffer (laughs, applause, fumbles) | 6:40 – 7:00 | 20s |

---

## 1. Intro (0:00 – 0:20)

- Walk on with the guitar already strapped on. **Don't mention it.** Let the audience wonder.
- Open with the phrase "nothing new under the sun" and the question: *if nothing is new, where does originality come from?*
- Promise the answer in three tables: a painter's table, a guitarist's fretboard, and a developer's desk.

---

## 2. Still-life paintings (0:20 – 1:50)

Same subject throughout: **a table with fruit and vessels.** Each artist keeps the form and changes one thing.

| Role | Painting | What changes | Link |
|---|---|---|---|
| **The box** (Chuck Berry) | Willem Claesz. Heda, *Still Life with a Gilt Cup*, 1635, Rijksmuseum | Nothing. This is the form: realism, one viewpoint, perfect illusion | [Rijksmuseum](https://www.rijksmuseum.nl/en/stories/one-hundred-masterpieces/story/still-life-gilt-cup) |
| **Rhoads** (one note outside) | Paul Cézanne, *The Basket of Apples*, c. 1893, Art Institute of Chicago | Perspective. The table edge doesn't line up, the bottle tilts, the plate leans toward you | [Art Institute of Chicago](https://www.artic.edu/artworks/111436/the-basket-of-apples) |
| **SRV** (more tension) | Henri Matisse, *The Dessert: Harmony in Red*, 1908, Hermitage Museum | Color and pattern. The tablecloth and wall share one pattern, so the table dissolves into the room | [Wikipedia](https://en.wikipedia.org/wiki/The_Dessert:_Harmony_in_Red_%28The_Red_Room%29) |
| **EVH** (new technique) | Roy Lichtenstein, *Still Life with Crystal Bowl*, 1972, Whitney Museum | Technique. A fruit bowl rendered in comic-book outlines and printing dots | [Whitney Museum](https://whitney.org/collection/works/1501) |

**Talking point for Matisse:** he first exhibited this painting as *Harmony in Blue*, then repainted the background red. Same composition, new tone, much like switching amp settings on the same lick.

**Progression in one line:** realism (1635) → shifting viewpoints (1893) → flattened color (1908) → mass-print technique (1972).

---

## 3. Guitar licks (1:50 – 3:50)

### The Chuck Berry lick: the box itself
Play the Berry lick, then the reveal: the "Johnny B. Goode" intro is closely modeled on Carl Hogan's guitar intro to Louis Jordan's *Ain't That Just Like a Woman* (1946). **Even the original wasn't original.**

### Fretboard key

```
-A--   note inside the A minor pentatonic box
[F]-   note outside the box (the player's "color tone")
(E)-   tapped note
```

### The box: A minor pentatonic, 5th position

```
    3    4    5    6    7    8    9    10   11   12
e |----|----|-A--|----|----|-C--|----|----|----|----|
B |----|----|-E--|----|----|-G--|----|----|----|----|
G |----|----|-C--|----|-D--|----|----|----|----|----|
D |----|----|-G--|----|-A--|----|----|----|----|----|
A |----|----|-D--|----|-E--|----|----|----|----|----|
E |----|----|-A--|----|----|-C--|----|----|----|----|
```

### Randy Rhoads: add the ♭6 (F)
A neoclassical, Aeolian flavor. One dark note just outside the box.

```
    3    4    5    6    7    8    9    10   11   12
e |----|----|-A--|----|----|-C--|----|----|----|----|
B |----|----|-E--|[F]-|----|-G--|----|----|----|----|
G |----|----|-C--|----|-D--|----|----|----|----|----|
D |----|----|-G--|----|-A--|----|----|----|----|----|
A |----|----|-D--|----|-E--|[F]-|----|----|----|----|
E |----|----|-A--|----|----|-C--|----|----|----|----|
```

### Stevie Ray Vaughan: add the ♭9 (B♭)
Chromatic tension that resolves to the root.

```
    3    4    5    6    7    8    9    10   11   12
e |----|----|-A--|[Bb]|----|-C--|----|----|----|----|
B |----|----|-E--|----|----|-G--|----|----|----|----|
G |[Bb]|----|-C--|----|-D--|----|----|----|----|----|
D |----|----|-G--|----|-A--|[Bb]|----|----|----|----|
A |----|----|-D--|----|-E--|----|----|----|----|----|
E |----|----|-A--|----|----|-C--|----|----|----|----|
```

> If you meant the natural 9 (B) rather than the ♭9, the B notes near the box are at e-7, G-4, and D-9.

### Eddie Van Halen: two-handed tapping
**The punchline:** the tapped E at fret 12 is *already in the scale*. Eddie doesn't add a new note. He adds a new technique, just like Lichtenstein's printing dots.

```
    3    4    5    6    7    8    9    10   11   12
e |----|----|-A--|----|----|-C--|----|----|----|(E)-|
       tap 12 → pull-off to 5 → hammer-on to 8 → repeat
B |----|----|-E--|----|----|-G--|----|----|----|----|
G |----|----|-C--|----|-D--|----|----|----|----|----|
D |----|----|-G--|----|-A--|----|----|----|----|----|
A |----|----|-D--|----|-E--|----|----|----|----|----|
E |----|----|-A--|----|----|-C--|----|----|----|----|
```

**Progression in one line:** Rhoads and SRV bend the rules inside the position. EVH leaves the room and comes back.

---

## 4. Tech examples (3:50 – 6:20)

Same pattern: **a familiar box, plus one added note.** Reuse the box-and-colored-dot visuals from the guitar slides so the audience connects them without being told.

| Product | The box (what already existed) | The added note |
|---|---|---|
| **Google** | Keyword search engines: AltaVista, Excite, Yahoo | **PageRank**, links counted as votes. Borrowed from academic citation analysis, which is the Carl Hogan moment again |
| **iPhone** | Smartphones: BlackBerry, Palm, Windows Mobile | **Capacitive multitouch plus a real web browser.** The multitouch came partly from Apple acquiring FingerWorks |
| **Git** | Version control: CVS, Subversion, BitKeeper | **Fully distributed, fast, snapshot-based history.** Written in 2005 after Linux lost free use of BitKeeper |

**Takeaway slide:** *You don't need a new box. You need your note.*

---

## 5. Closing (6:20 – 6:40)

Close on the second-mouse line, with a twist that ties it back to the thesis:

> *"The second mouse gets the cheese."*
> **The first mouse proves there's cheese. The second mouse makes it their own.**

Optional: one last short lick as the exit.

---

## Practical checklist

- **Tone:** set up a clean/crunch preset or one footswitch, or commit to a single crunch tone.
- **Tuning:** play all excerpts in standard tuning, with no retuning on stage.
- **Slides:** use a pocket clicker, foot pedal, or auto-advance during the guitar section.
- **Sound:** confirm a DI or amp with the venue, and tell the sound tech in advance.
- **Licks:** keep each under 5 seconds and pick ones you can nail cold with adrenaline.

## Image rights note

Heda and Cézanne are public domain, with free high-resolution images from the Rijksmuseum and the Art Institute of Chicago. Matisse's 1908 painting is generally treated as public domain in Canada and the US. Lichtenstein is still under copyright (© Estate of Roy Lichtenstein). Brief use in a live talk for commentary is common, but if the event records and publishes talks, check their guidelines on third-party images.
