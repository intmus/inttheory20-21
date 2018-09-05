---
layout: chapter
title: Lesson 3a - Seventh Chords
abc: true
---

Seventh chords are most easily thought of as an extension of triads, and our labeling system reflects this. In the same that we create a triad by inserting a 3rd into a 5th, we create a seventh chord by adding a 3rd on *top* of a triad. They are called seventh chords becuase this new note creates an interval of a 7th between the chordal root and the new pitch.

{% capture ex1 %}X:1
%%staffsep 100%
T:Diatonic Seventh Chords in the Major Scale
M:C
L:1/2
K:C
[CEGB] [DFAc]| [EGBd] [FAce]| [GBdf] [Aceg]| [Bdfa] [cegb]||
w:MM mm mm MM Mm mm dm{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

Because they are stacked thirds, seventh chords are still considered tertian harmony. They are prevalent in almost all styles of Western music, and we have developed many systems to describe how they *function* harmonically. Again though, we must first be able to classify and label them in an structural manner that does not rely on key-based functions. We name the chord members by the distance above the bottom pitch **when the chord is stacked in thirds**:
- the lowest pitch is called the *root* of the chord
- the pitch that is a 3rd above the root is called the *chordal third*
- the pitch that is a 5th above the root is called the *chordal fifth*
- the pitch that is a 7th above the root is called the *chordal seventh*

### Seventh chord inversions

All seventh chords have exactly four notes, although certain chord members can occasionally be omitted (and therefore implied) depending on the context. With four pitches, there are four possible configurations that depend on which note of the triad is in the lowest voice. Like triads, we call these *inversions*, and we use the same shorthand system to label inversions that we used with triads.

## Goals for this topic

Using the examples below:
- determine what role each chordal member (e.g. root, third, fifth, etc.) plays in determining the quality of a seventh chord
    - How does this relate to triads?
- find all six intervals between the chordal members of a root-position seventh chord for each of the following chord qualities:
    - *major seventh, minor seventh, dominant seventh, half-diminished, fully-diminished*
- explain what each part of the the alternate names for each seventh chord
    - *Major major* (MM), *major minor* (Mm), *minor minor* (mm), *diminished minor* (dm), and *diminished diminshed* (dd)
- find the following interval sizes between chordal members of a seventh chord (Hint: This may involve moving some chord members up or down an octave)
    - seconds (1)
    - thirds (3)
    - fourths (2)
    - fifths (2)
    - sixths (3)
    - sevenths (1)
- relate these intervals to our system for labeling seventh-chord inversions
    - provide inversion figures for root-position, first-inversion, second-inversion, and third-inversion seventh chords
- be able to explain how to turn any inverted and/or open-voiced seventh chord into a root-position seventh chord in a closed voicing

### Seventh chord qualities

{% capture ex2 %}X:2
T:Seventh chord qualities
M:2/4
L:1/2
K:C
"Major seventh (MM)"[D^FA^c]| "Dominant seventh (Mm)"[D^FAc]| "Minor seventh (mm)"[DFAc]| "half-diminished (dm)"[DF_Ac]| "fully-diminished (dd)"[DF_A_c]||{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

### Seventh chord inversions

Because ABC notation is not capable of using superscript, the inversion figures in the next example are notated as fractions. If you were to write these by hand or use custom notation software, you would notate all inversion figures using superscript. For example, a dominant seventh chord would be written as Mm<sup>7</sup>

{% capture ex3 %}X:3
T:Seventh chord inversions
T:1) Inversion names are listed above the staff
T:2) Inversion figures are listed below the staff
T:---------
M:2/4
L:1/2
K:C
"Root position"[D^FAc]| "First-inversion"[d^FAc]| "Second-inversion"[d^fAc]| "Third-inversion"[D^FAC]||
w:7~(7/5/3) 6/5~(6/5/3) 4/3~(6/4/3) 4/2~(6/4/2){% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

### Seventh chord voicings

{% capture ex4 %}X:4
T:Seventh chord voicings
M:2/4
L:1/2
K:C
V:1
"Closed"[dFAc]| "Closed"[Ac]| "Open"[dF]| "Open"[dFAC]|
V:2 clef=bass
z| [DF]| [A,,C]| [D,,D,]|{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## Conclusions

A seventh chord is a diatonic chord containing four pitches, each separated by a 3rd. 

There are 5 types of seventh chords, and we will be using both of the common terms for them:
- *Major major* (abbreviated `MM`) or *major seventh chord*
- *Major minor* (abbreviated `Mm`) or *dominant seventh chord*
- *Minor minor* (abbreviated `mm`) or *minor seventh chord*
- *Diminished minor (abbreviated `dm`) or *half-diminished seventh chord* 
- *Diminished diminished* (abbreviated `dd`) or *fully-diminished seventh chord*

These terms are interchangeable but they are typically used in different circles. We will refer to them as the pedagogical name (e.g. major major, etc.) and common name (e.g. major seventh chord, etc.).

The pedagogical names are useful in illustrating the structure of a seventh chord and is unsurprisingly often used by theory teachers. I asked the class to explain what the two words in "major major" meant, and the first suggestion was, "The first word is the triad quality (major triad on bottom), and the second word is the chord quality between the root and the 7th. This is close, but did not quite explain the true nature of the second word. The pedagogical naming system for seventh chords mixes a chord quality with an interval quality. The first word always describes the triad (the bottom three pitches) while the second word describes the *interval quality* between the root and the seventh chordal member. This interval is always a 7th.

- Major major (major seventh chord): major triad + M7
- Major minor (dominant seventh chord): major triad + m7
- Minor minor (minor seventh chord): minor triad +m7
- Diminished minor (half-diminished seventh chord): diminished triad + m7
- Diminished diminished (fully-diminished seventh chord): diminished triad + d7

Because the class had already been through a similar exercise for triads, they were able to quickly identifty the inversion figures as they relate to the intervals above the *bass*, not the *root* of the chord.

- Root position: 7 (7/5/3)
- First Inversion: 6/5 (6/5/3)
- Second Inversion: 4/3 (6/4/3)
- Third Inversion: 4/2 (6/4/2)

As a reminder, we will be using the term *inversion figure* to discuss this shorthand method of identifying inversions. Other systems refer to these same superscript numbers as figured bass, bass position Symbols, or figures, but we need not argue about which name is better. As long as the student understands the difference between *inversion figures*, true *figured bass* (i.e. Baroque system for writing keyboard harmonies), and the shorthand used in *leadsheet notation*, it does not actually matter which term is used. 