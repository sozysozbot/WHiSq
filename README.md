# WHiSq: Wicki–Hayden in Squares

An isomorphic keyboard layout easily realizable with a Launchpad Mini.

comes in two flavors: 

- plain WHiSq: intended for 12edo (12 equal temperament)  
- √2 WHiSq: intended for 17edo (17 equal temperament) 

## WHiSq: 12edo Wicki–Hayden in Squares; skip-fretting system 12 2 5

- Up = 5 semitones (perfect fifth)
- Left = 2 semitones (whole tone)

I like adopting the following color scheme in Launchpad Mini:

| pitch classes | rationale | color | RGB as shown in the Web interface |
|--|--|--|--|.
| C, D, E, G, A | C Major Pentatonic | White | #ffffff |
| C#, D#, F#, G#, A# | black keys on a piano | Green | #62cb47 |
| F, B | belongs to neither of the two | Green_blue | #75fbab |

I also chose to set the “On colour” to Deep_blue.

![](./Launchpad-WHiSq-colored.png)

### chord cheatsheets

[PNG](./WHiSq_chord_cheatsheet.png) [SVG](./WHiSq_chord_cheatsheet.svg)

![](./WHiSq_chord_cheatsheet.png)

## √2 WHiSq: skip-fretting system 17 3 7

First, note how the just-intonation perfect fifth and the Pythagorean whole tone work in 12edo and 17edo:

|   | just-intonation P5 | Pythagorean WT |
|----|-------------------|---------------|
| ratio | 3/2 | 9/8 |
| [monzo](https://en.xen.wiki/w/Monzo) |  [-1 1⟩  |  [-3 2⟩ |
| 12edo |  2  | 5 |
| 17edo | 3 | 7 |

√2 WHiSq is based on the following observations:

- 5 + 2 = 7
- 5 - 2 = 3

That is, the two orthogonal diagonals of a Launchpad Mini configured in 12edo WHiSq can be taken as the new axes representing the P5 and the whole tone in 17edo.

Thus, rotating the board by 45 degrees and playing the grids reachable by bishop's moves results in a (mirrored) WHiSq.
