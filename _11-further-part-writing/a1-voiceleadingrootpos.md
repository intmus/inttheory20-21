---
layout: chapter
title: Lesson 11a - Voice-leading for Root Position Triads and Seventh Chords
abc: true
---

We can view the voicing rules (i.e. spacing, range, doubling, and voice-crossing) as our guidelines for creating the vertical aspect of this style of music, and our voice-leading rules (i.e. tendency tones, conjunct lines, and avoiding part-writing errors) as guidelines for creating the horizontal aspect of this style of music. By combining these ideas with a general knowledge of diatonic chord progressions, we can begin composing our first attempts at chorale-style music.

Before beginning, please remember that when composing in this style, you occasionally will need to bend, or even break, these rules to accommodate other musical goals. There is not a "right" or "wrong" hierarchy for the conventional rules of part-writing. For example, you might choose to accept parallel perfect 5ths if you are trying to create a particular melodic line that emphasizes stepwise motion. Or, you might decide to use voice-crossing of the inner voices to change the timbre and texture of a passage. Regardless, be aware that even the cleverest of composers may choose to eschew convention if it does not align with their musical goals.

## Building the process

In [Unit 10a]({{ site.baseurl }}/10-intro-part-writing/a1-funds-of-part-writing.html), we outlined a method for harmonizing a melody.
1. Identify the key
2. Determine your phrase
3. Choose a cadence to complete your phrase.
4. Create the rest of the diatonic progression beginning on tonic and ending with your cadence.
5. Compose a bass line based on your harmonization.
6. Fill in the alto and tenor voices.

Now that we have studied the stylistic guidelines for this style, we can improve our attempts greatly by:
- following the standard harmonic progressions outlined by circle-of-fifths progressions.
- correctly using cadences.
- using functions such as tonic, dominant, and pre-dominant logically.
- employing the smoothest possible voice-leading for each line.
    - The bass can be slightly more disjunct than the upper parts, particularly when using root-position chords.
- not crossing voices.
- avoiding spacing or range errors.
- avoiding incorrect doubling.
- resolving tendency tones correctly.
- avoiding unacceptable part-writing such as parallel perfect 5ths/8ves, contrary perfect 5ths/8ves, similar 5ths/8ves, and unequal 5ths.

Remember that circle-of-fifths progressions work because the voice-leading taps into the primary functions of diatonic harmony. If you review [Unit 7a]({{ site.baseurl }}/07-harmonic-functions/a1-diaprogcirclefifths.html), you will remember that we created the harmonic flow chart by simply following good voice-leading between chords that have roots separated by a descending P5/ascending P4. Admittedly, long strings of root-position chords create unmelodic bass lines, but they still represent the strongest voicing for many sonorities. 

## Getting started

We will now flip the starting point and try to compose a four-part chorale given the harmonies rather than the melody. Try to create a clean and simple texture from the following example. Write the soprano line from the given first pitch, and then fill in the inner voices following the guidelines above.

{% capture ex1 %}X:1
T:Circle-of-fifths triadic progression
M:4/4
L:1
K:C
V:1
c| x| x| x| x|]
V:2 clef=bass
[C,]| [A,,]|[D,]| [G,,]| [C,]|]
w:C:I vi ii V I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

**Now that you have completed a harmonization, make sure to double-check it for part-writing errors. If you successfully completed it, try changing your melody and trying again.**

## Adding the seventh

**As a theory teacher, I often feel that I spend more time talking about the exceptions to rules than the actual rule itself. Luckily, turning a triad into a seventh chord creates one of the least broken rules: *Typically, the seventh of a chord resolves down by step.* There will be instances where you are forced to break this rule (e.g. pre-determined melodies, sequences, etc.), but generally, it will hold true. Try adding the following two seventh chords to the basic circle-of-fifths progression while following this rule.**

{% capture ex2 %}X:2
T:Root-position part-writing with
T:seventh chords and root movement by P4/P5
M:4/4
L:1
K:C
V:1
c| x| x| x| x|]
V:2 clef=bass
[C,]| [A,,]|[D,]| [G,,]| [C,]|]
w:C:I vi7 ii V7 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

## Exploring options

**Of course, there are multiple chords in our circle-of-fifths progressions that have root movement by intervals other than 4ths and 5ths. Try harmonizing the following short chord progressions while observing our guidelines. Keep track of what types of root movement create the most issues while developing at least two possibilities for each of the progressions**

{% capture ex3 %}X:3
T:Short chord progressions
T:Treat each measure as a separate progression
M:4/4
L:1/4
K:C
V:1
cxxx|| cxxx|| cxxx|| cxxx|]
V:2 clef=bass
[C,] [F,,] [G,,] [C,]|| [C,] [F,,] [G,,] [A,,]|| [C,] [D,] [F,] [G,]|| [C,] [D,] [G,,] [C,]|]
w:C:I IV V7 I I IV V vi I ii IV V I ii7 V7 I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## Function over form (Part 1)

**When you were harmonizing these short chord progressions, which chord progression presented the most issues? For most, it will likely be when the progressions that have root-movement by 2nd, particularly a progression IV-V-vi. Let's start by isolating a common example of this movement, V moving to vi. In this progression, the V is acting according to its standard dominant function, but the vi chord has replaced the I chord in the position where a tonic function should occur. This progression represents a *functional substitution* in which vi is now acting as the tonic function. (This concept has application within the dominant and pre-dominant functions as well, but we need to explore first-inversion chords in the next topic, 11b, before we are ready for that discussion):**
- When V goes to vi, the vi chord is replacing the tonic function and therefore functions as a I<sup>sub6</sup>

**From a practical perspective, a *functional substitution* can inform your voice-leading. When a root-position V chord precedes a root-position vi chord, we must choose to prioritize either our *doubling* conventions or our *part-writing conventions*. With this in mind, harmonize the following two progressions; first with the standard tonic function (i.e. V to I) and then with the functional substitution (i.e. V to vi.) How does the standard function influence your decision on which conventions to employ on the function substitution.**

{% capture ex4 %}X:4
T:Using a functional substitution for a deceptive cadence
M:3/4
L:1/4
Q:1/4=60
K:C
V:1
[cE][B][c]| ] [cE][B][c]|]
V:2 clef=bass
[C,G,] [G,,] [C,]| [C,G,] [G,,] [A,,]|]
w:C:I V I I V vi{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

**Because the vi chord acts as a replacement for a I chord, we double the scale degree that works best for a I chord, `do`, rather than the standard doubling of the root, `la` or fifth, `mi`. In this progression, it is correct to break standard convention and double the chordal third of the vi chord.**

## Root movement by 2nd

**The other difficult resolution in the previous example was when the root position IV chord moved to the V chord. We do not have a *functional substitution* to provide a doubling exception here, so instead you must be careful about how you resolve the voices. Harmonize the following progression without altering the given pitches, and pay particular attention to the direction that the upper voices resolve as you avoid part-writing errors.**

{% capture ex5 %}X:5
T:Root movement by 2nd
M:4/4
L:1/4
K:C
V:1
[cE] [c] xx|]
V:2 clef=bass
[C,G,] [F,,] [G,,] [C,]|]
w:C:I IV V I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

## Common exceptions

**There are some commonly used exceptions to our general part-writing conventions. For example, when a chord progression has a root that moves down by P5, we expect the chordal third to resolve up by step to the root of the following chord. However, if you need to change the texture of your part-writing to be more or less compact, you may choose to have the chordal third leap to the following chordal third which changes the entire voicing possibilities of the two chords. (Note that you can only use this on the leading tone if it is in an inner voice.) Use this method to fill in the inner voices in the following example to change the voicing of the final chord.**

{% capture ex6 %}X:6
T:Chordal third to chordal third
M:4/4
L:1/4
K:C
V:1
[eG] [d] [c2]|]
V:2 clef=bass
[C,C] [G,,] [C,2]|]
w:C:I V I{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

**Another common exception is called the *frustrated leading tone*. While it is not ideal, if the leading-tone is in an inner voice, you can choose to have it resolve by skipping downward to the root of the tonic chord. This can solve doubling issues if you are trying to fix an incomplete triad by adding the chordal fifth. Try it in the tenor voice on the following two progressions. Notice that this allows you to create a deceptive cadence without having to double the chordal third of the vi chord.**

{% capture ex7 %}X:7
T:Frustrating a leading tone
M:3/4
L:1/4
Q:1/4=60
K:C
V:1
[eG] [d] [c]|| [eG] [d] [c]|]
V:2 clef=bass
[C,C] [G,,] [C,]|| [C,C] [G,,] [A,,]|]
w:C:I V7 I I V7 vi{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}

## Conclusions

Before we started our first attempts at part-writing, I asked the class to review the guidelines listed at the top of Example 11a. They were:

In your early part writing, you should strive for a simple, clean texture that:
- follows the standard harmonic progressions outlined by circle-of-fifths progressions
    - correctly uses cadences as well as tonic, dominant, and pre-dominant functions
- has the smoothest possible voice-leading for each line
    - the bass can be slightly more disjunct than the upper parts, particularly when using root-position chords
- does not cross voices
- has no spacing or range errors
- avoids incorrect doubling
- resolves tendency tones correctly
- does not create unacceptable part-writing such as consecutive perfect 5ths/8ves or similar 5ths/8ves

The first question was, "What constitutes "smooth" voice-leading?" *The simple answer is that stepwise (or even static) motion is preferred.* When you are creating a line for a particular voice (i.e. soprano, alto, tenor, bass), you will have few options when choosing what the next pitch will be. It must be a chord-tone, and you must also consider the notes that are already fixed. (Bass lines and melodies are often written first and are therefore unchangeable.) When you add in doubling and range limitations, you will usually have one or possibly two options for smooth (conjunct) voice-leading. 

The other question was "Is there a general rule for the correct for resolution of tendency tones?" Unfortunately, there is no simple answer for this. At its most basic, `ti` resolves up by step, and `fa` resolves down by step. When part-writing, however, this is too simplistic a view. For example, `fa` often moves upward by step to `sol`, either as part of an ascending scalar melodic line or in the bass line when a root-position IV chord moves to a root-position V chord. The next level of thinking would be to say that `ti` and `fa` are tendency tones when they are part of a V<sup>7</sup> chord, so therefore, the rule for tendency tones should be that *chordal thirds* resolve up by step and *chordal sevenths* resolve down by step. This is a better rule, but it also falls apart when we leave circle-of-fifths progressions (chords with roots separated by a descending P5). When a IV chord moves to a V chord, it is impossible for the third to move *up by step* to the root of the V chord. For now, the easiest rule for tendency tones is:
- *Chordal thirds* resolve up by step and *chordal sevenths* resolve down by step *when part of a circle-of-fifths progression*.

## Part-writing

Using our guidelines as a framework for part-writing, we discussed the best order for the process of composing our SATB examples.

If given a melody:
- **Choose a cadence** for the end.
    - Refer to Unit 7c to review the types of cadences.
- **Create the rest of the diatonic progression** that begins on tonic and ends with your cadence. (If not already provided.)
    - This will establish your key center. Refer to Unit 6b for a review of the three primary harmonic functions: tonic, dominant, and pre-dominant.
- **Compose a bass line** based on your harmonization.
    - This will resemble 1:1 counterpoint, so refer to Unit 5b.
    - Contrary motion against the soprano line is preferred.
- **Fill in the alto and tenor voices.**
    - Refer to the rules for voicing, range, and doubling in Unit 6b.
- When writing your parts, always **strive to have voice-leading that is as smooth as possible** by emphasizing stepwise motion.
    - Bass lines are the exception and will often have more leaps, especially when using root-position chords.

If given a harmonic progression (and likely a bass line):
- **Compose a melody** and then check it against your bass line for part-writing errors.
    - This will resemble 1:1 counterpoint, so refer to Unit 5b.
    - Contrary motion against the soprano line is preferred.
- **Fill in the alto and tenor voices.**
    - Refer to the rules for voicing, range, and doubling in Unit 6b.
- When writing your parts, always strive to have voice-leading that is as smooth as possible by emphasizing stepwise motion.
    - Bass lines are the exception and will often have more leaps.

With this in mind, I asked them to harmonize the first example from the previous page, and they came up with the following answer:

{% capture ex8 %}X:8
T:Circle-of-fifths triadic progression
M:4/4
L:1
K:C
V:1
[cE]| [cE]| [dF]| [dG]| [eG]|]
V:2 clef=bass
[C,G,]| [A,,A,]|[D,A,]| [G,,B,]| [C,C]|]
w:C:I vi ii V I{% endcapture %}
{% include abc-example.html number="8" abc=ex8 %}

The students were surprised by two things:
- How similar almost every groups answer was.
- That this is not as difficult as it first seems.

Because the chord progession provides a vertical framework and smooth voice-leading provides a horizontal framework, most of the work is simply following the pattern correctly. This example is admittedly straightforward because it relies entirely on root-position triads in a circle-of-fifths progression. I next asked them to add two seventh chords along with the rule that the *chordal seventh should resolve down by step*.

{% capture ex9 %}X:9
T:Root-position part-writing with
T:seventh chords and root movement by P4/P5
M:4/4
L:1
K:C
V:1
c| x| x| x| x|]
V:2 clef=bass
[C,]| [A,,]|[D,]| [G,,]| [C,]|]
w:C:I vi7 ii V7 I{% endcapture %}
{% include abc-example.html number="9" abc=ex9 %}

This single new wrinkle created considerably more issues. The first arose between the second and third chords. By placing a chordal seventh in the tenor voice on the vi<sup>7</sup> chord, it locked the voice-leading of that voice into resolving downard by step to the third of the following chord. Because we did not want to double the third on that chord, we could only choose to move to the closest D or A in the alto voice. If we were to move to the A, that would create parallel perfect 5ths with the bass voice, so we could only choose the D for the alto voice.

Example: "Short Chord Progressions"

1a. Key: C

Bass: C3 - F2 - G2 - C3

Roman Numerals: I - IV - V7 - I

- potential problems: the parallel motion from the IV to V7 in root position
  - the V7 can make that problem easier to solve by keeping the F static
  - whenever you have stepwise motion in the bass, parallel motion can be a problem
- functional substitution: when the vi chord substitutes for the I chord

1b. Key: C

Soprano: C5 - D5 - C5 - C5 - B4 - C5

Alto: E4 - G4 - E4 - E4 - D4 - C4

Tenor: G3 - B3 - C4 - G3 - G3 - E3

Bass (given): C3 - G2 - C3 - C3 - G2 - A2

Roman Numerals: I - V - I - I - V - vi (Isub6)

Isub6 means that you take a I chord, put a 6 on top, and the 6 substitutes the nearest chord tone. 
This creates a vi chord. 

2. Key: C

Bass (given): C3 - F2 - G2 - A2

Roman Numerals: I - IV - V - vi 

3. Key: C

Bass (given): C3 - D3 - F4 - G4

Roman Numerals: I - ii - IV - V

Chordal Third to Chordal Third:
- moving from third to third between chords can avoid ppart writing errors
- using open to closed voiceing (or vice versa) to change the texture
    - this cannot be applied to outer voices

Frustrated leading tone:
- when the leading tone does not resolve to the tonic
    - can only be done in the alto or tenor voices
    - Ti resolves to Sol (and sometimes La) instead of Do

Deceptive cadences apply the frustrated leading tone by resolving Ti to La instead of Sol. 