# Music theory 101

## References

- [Music Theory Tier List](https://www.youtube.com/watch?v=ItsMmqTOgKo)

  ![image-20240318185437005](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240318185437005.png?raw=true)

- [Music Theory for the 21st-Century Classroom](https://musictheory.pugetsound.edu/mt21c)

- [Download Musescore](https://musescore.org/en)



## 0. Basics

**Topics**: Temperament, Harmonic series, Clefs, Rhyme, Articulations, Dynamics

### 0.1 Temperament

The frequency of the sound produced by a string is determined by the length, tension and density of the string:

![7e738f3975fc8ac6028f328bc3e64bc93789a827](https://github.com/minth1468/music-theory-101/blob/main/assets/7e738f3975fc8ac6028f328bc3e64bc93789a827.svg?raw=true)

Double frequency: Same pitch of higher octave.

3/2 frequency: A new pitch which sounds well with the original pitch. (Perfect fifth)

**Concert pitch**: [A = 440Hz](https://onlinetonegenerator.com/?freq=440)

- [History on the pitch standard](https://youtu.be/EKTZ151yLnk?t=363)

**Pythagorean tuning**: Obtaining possible pitches between 440Hz and 880Hz by applying 2/3 string length (3/2 frequency)

- Recurrence Equation: If $f_n\times1.5>=880$ , $f_{n+1}=f_n\times 0.75$
  - Else: $f_{n+1}=f_n\times 1.5$

**Table. Pythagorean tuning starting with A440**

| Frequency/Hz | Note Name | Frequency (In Order)/Hz | Note Name |
| ------------ | --------- | ----------------------- | --------- |
| 440.00       | A         | 440.00                  | A         |
| 660.00       | E         | 469.86                  | Bb        |
| 495.00       | B         | 495.00                  | B         |
| 742.50       | Gb        | 528.60                  | C         |
| 556.88       | Db        | 556.88                  | Db        |
| 835.31       | Ab        | 594.67                  | D         |
| 626.48       | Eb        | 626.48                  | Eb        |
| 469.86       | Bb        | 660.00                  | E         |
| 704.79       | F         | 704.79                  | F         |
| 528.60       | C         | 742.50                  | Gb        |
| 792.89       | G         | 792.89                  | G         |
| 594.67       | D         | 835.31                  | Ab        |
| 446.00       | ~A        | 446.00                  | ~A        |

A 446Hz is obtained after 12 iterations and is close enough to the starting frequency (440Hz), thus an Octave can be divided into 12 pitches.

However, the distance of the 12 pitches are not equal. To obtain a equal temperament, the Recurrence Equation should be $f_{n+1}=f_n\times2^{1/12}$ .

**Table. 12 tone equal temperament (12 TET) frequency table**

| Note Name | Frequency/Hz |
| --------- | ------------ |
| A         | 440.00       |
| Bb        | 466.16       |
| B         | 493.88       |
| C         | 523.25       |
| Db        | 554.37       |
| D         | 587.33       |
| Eb        | 622.25       |
| E         | 659.26       |
| F         | 698.46       |
| Gb        | 739.99       |
| G         | 783.99       |
| Ab        | 830.61       |
| A         | 880.00       |

The hearing range of human ear is 20Hz - 20000Hz, thus all audible As can be obtained. The pitches are denoted from A0 to A9.

**Table. Audible frequency table of note A**

| Note Name | Frequency/Hz |
| --------- | ------------ |
| A0        | 27.5         |
| A1        | 55           |
| A2        | 110          |
| A3        | 220          |
| A4        | 440          |
| A5        | 880          |
| A6        | 1760         |
| A7        | 3520         |
| A8        | 7040         |
| A9        | 14080        |

Combining 12 TET and all the A frequencies above, all 88 frequencies of the piano can be obtained.

- Piano sound range: A0-C8

### 0.2 Harmonic series

A piano can be differentiated from a violin because they consists of different overtone (harmonic composition).

The nth harmonics of a fundamental frequency $f_1$ is $f_n=n\times f_1$

[Sound synthesis](https://youtu.be/Y7TesKMSE74?t=416): synthesize sounds of any instrument/voice with sine wave oscillators.

The **Harmonic Serie**s is the harmonics equation above expressed in the form of musical notation. (Notice the frequencies of the notes equal the multiples of 55Hz)

![image-20240319151707899](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240319151707899.png?raw=true)

### 0.3 Names of clefs

G clef, F clef, and C clef: name implies note name at the starting stroke of the corresponding clef.

- e.g. G clef, F clef, and C clef

![image-20240319142835164](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240319142835164.png?raw=true)

### 0.4 Musical notations

Rhyme, Articulations, Dynamics

tbc.

## 1. Scales and Keys

**Topics**: Major, Minor, Key signatures, Circle of fifth

### 1.1 Scales

**Major**: WWH-WWWH, or denoted 1234567 (which is a standard reference of all other scales). 

- Note: W and H stand for Whole step and Half step respectively. (A half step equals 1/12 of an octave and a whole step equals two half steps)

- e.g. C major

![image-20240319143813191](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240319143813191.png?raw=true)

**Minor**: 12 b3 45 b6 b7 or 6712345

- e.g. c minor

![image-20240319143930169](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240319143930169.png?raw=true)

- harmonic minor: 12 b3 45 b6 7 or 671234 #5
  - e.g. c harmonic minor

![image-20240319214826489](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240319214826489.png?raw=true)

- melodic minor: 12 b3 4567(ascending) , b7 b6 54 b3 21(descending) 
  - or 67123 #4 #5(ascending) , 5432176(descending) 
  - e.g. c melodic minor

![image-20240319214836379](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240319214836379.png?raw=true)

**Relative key**: scales sharing the same notes

- e.g. C major and a minor

**Parallel key**: scales with the  starting note

- e.g. C major and c minor

Scale degree names

![scale-degree-names](https://github.com/minth1468/music-theory-101/blob/main/assets/scale-degree-names.svg?raw=true)

![scale-degrees-names-above-and-below](https://github.com/minth1468/music-theory-101/blob/main/assets/scale-degrees-names-above-and-below.svg?raw=true)

### 1.2 Key signatures

Recurrence Equation: For any major,

- sharp fourth degree -> obtain new major starting from fifth degree.
  - e.g. #F in C major to get G major.
- flat seventh degree -> obtain new major starting from fourth degree.
  - e.g. bB in C major to get F major.


### 1.3 Circle of fifth

![600px-Circle_of_fifths_deluxe_4.svg](https://github.com/minth1468/music-theory-101/blob/main/assets/600px-Circle_of_fifths_deluxe_4.svg.png?raw=true)

- How to remember COF: CF+b(BEADG)+BEADG
- The sequence of sharp(#) notes: FCGDAEB or (fa do so re la mi ti)
  - sequence of flat(b) notes: BEADGCF



## 2. Intervals

**Topics**: Intervals, Pentatonic scale, Blues scale

### 2.1 Intervals

**Interval** measures distance between pitches. 

- Numeric size (nth) + Quality (diminished, minor, major, augmented) or (diminished, perfect, augmented)
- Numeric size means how much two notes apart in a given context scale.
- Diminished, minor, major, augmented: 2nd, 3rd, 6th, 7th
- Diminished, perfect, augmented: 1(unison), 4th, 5th, 8ve

Shorthand notation for intervals: 

- e.g. m2=minor second, M3=major third, aug4=augmented fourth, dim5=diminished fifth, P5=perfect fifth, tri=tritone

**Table. Interval size vs. number of half steps**

| 1H   | 2H   | 3H   | 4H   | 5H   | 6H   | 7H   | 8H   | 9H   | 10H  | 11H  | 12H  |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| m2   | M2   | A2   |      |      |      |      |      |      |      |      |      |
|      | d3   | m3   | M3   | A3   |      |      |      |      |      |      |      |
|      |      |      | d4   | p4   | tri  |      |      |      |      |      |      |
|      |      |      |      |      | tri  | p5   | A5   |      |      |      |      |
|      |      |      |      |      |      |      | m6   | M6   | A6   |      |      |
|      |      |      |      |      |      |      |      | d7   | m7   | M7   |      |
|      |      |      |      |      |      |      |      |      |      |      | P8   |

A **diatonic interval** is formed by notes in a diatonic scale. 

**Table. Diatonic intervals in the major scale: (number in the brackets denotes the starting degree of the interval)**

| Numeric | Interval1            | Interval2            |
| ------- | -------------------- | -------------------- |
| 2nd     | m2(3, 7)             | M2(1, 2, 4, 5, 6)    |
| 3rd     | m3(2, 3, 6, 7)       | M3(1, 4, 5)          |
| 4th     | p4(1, 2, 3, 5, 6, 7) | tri(4)               |
| 5th     | tri(7)               | p5(1, 2, 3, 4, 5, 6) |
| 6th     | m6(3, 6, 7)          | M6(1, 2, 4, 5)       |
| 7th     | m7(2, 3, 5, 6, 7)    | M7(1, 4)             |

**Inversion** of intervals follows the following rules.

![image-20240325225246300](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240325225246300.png?raw=true)

### 2.2 Pentatonic scale, Blues scale

**Major pentatonic scale**: 12356. 

- e.g. C major pentatonic scale

![image-20240319222558412](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240319222558412.png?raw=true)

**Minor pentatonic scale**: 1 b3 45 b7. or 61235 

- e.g. c minor pentatonic scale

![image-20240319222633152](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240319222633152.png?raw=true)

(Minor) **blues scale**: 1 b3 4 #4 5 b7. or 612 #2 35 

- e.g. c blues scale

![image-20240319222738266](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240319222738266.png?raw=true)

- The #2 is called the blue note, and is usually performed lower than standard pitch.
- Major blues scale is less used in morden context and is most often used in ragtime and blues music.

## 3. Triads and Simple Tonal Musical Analysis

**Topics**: Triads, Roman numerals, Inversions, Voicing, Song structure, Cadences

### 3.1 Triads

A **chord** follows the Tertian rule(i.e. constructed from the intervals of thirds)

A **triad** is a three note chord consisting of root+fifth+third

- The **root note** of a chord is the tonic note in the chord
  - the lowest note in the chord is the **bass note**

| Upper Interval | Lower Interval | Chord Symbol (Modern) | Chord Symbol (Classical) | 
| -------------- | -------------- | --------------------- | ------------------------ |
| m3             | M3             | C                     | C                        |
| M3             | m3             | Cm                    | c                        |
| m3             | m3             | Cdim/C-               | C°                       |
| M3             | M3             | Caug                  | C+                       |

### 3.2 Diatonic chords and Roman numerals

Chords found in scales are called **diatonic chords**.

The roman numeral is a way to denote diatonic  chords in a scale. (compare with 1234567 in major)

- e.g. Roman numeral of C major

![Roman-numerals-dia-chords-in-major](https://github.com/minth1468/music-theory-101/blob/main/assets/Roman-numerals-dia-chords-in-major.svg?raw=true)

Any scale can be defined with three characteristic triads.

- Major: I, IV, V
- Minor: i, vi, v

### 3.3 Inversion

- e.g. Inversions of a C major triad in C major
  - C6: first inversion, C is the sixth note above E (thus 6)
  - C64: second inversion, E, C are the sixth and fourth note above E (thus 64)
  - C/E: C chord with root note of E (called **Slash Chords**, modern symbol)

![image-20240324220704044](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240324220704044.png?raw=true)

### 3.4 Voicing

**Voicing**: placement of notes in a chord structure.

- Open position: notes with spacing >P4
- Close position: notes with spacing <=P4
- Doubling: a note that is duplicated in different octaves

Rule of thumb:

- Double the bass notes
- Use open position in the lower register
- Use close position in the higher register
  - e.g. Voicing of an F major triad

![image-20240326131015956](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240326131015956.png?raw=true)

### 3.5 Song structure

[Every type of Song Structure EXPLAINED](https://www.youtube.com/watch?v=SDJwg1JoPtY)

Common song structures: **Verse-chorus form** ,  **AABA form**, and **12 bar blues**

Components of a verse-chorus song: Into + Verse + Bridge(Pre-chorus or Transition) + Chorus(Refrain) + Interlude + Verse + Bridge + Chorus + Outro

- The chorus is the highlight of the song
- Verse is often less tense than the chorus
- Bridge comes before the chorus and usually serves as a energy build-up

- Interlude may be replaced/consists of: solo and/or a second bridge

AABA form is a basic form of music, often seen in classic and folk music.
- Commonly expanded to AABAABA
- Has other forms such as ABAC, ABAB', etc. 
- e.g. [A Las Barricadas](https://www.youtube.com/watch?v=7_Pk6VjZlho) (AA'BA'A'BA'A')

12 bar blues progression: songs that follow the following progression (sometimes with a ii-V-I turnaround at the end)

| I    | I    | I    | I    |
| ---- | ---- | ---- | ---- |
| IV   | IV   | I    | I    |
| V    | IV   | I    | I    |

- e.g. [The Lazy Girl Blues](https://www.youtube.com/watch?v=wwMvbW0R8Uo)

- e.g. [バカはバカのごとく現れる](https://www.youtube.com/watch?v=NPY4sd9HtZI)

### 3.6 Cadence

A **cadence** marks the end of a musical section. (e.g. at the end of a verse/chorus)

- Authentic Cadence (AC): V7-I
- Plagal Cadence (PC): IV-I
  - Often used in religious context
  - e.g. [Blue Archive OST 136. Kyrie Eleison](https://www.youtube.com/watch?v=90gEXwoPS9U)
- Deceptive Cadence (DC): V-vi
  - e.g. [Comparison between DC and AC](https://www.bilibili.com/video/BV1Hr4y127dF?t=54.7) 
- Half Cadence (HC): V
- Cadential 64 (K64): I64-V-I
  - Bass note: 5-1, highest note: 3-2-1
  - Used in classical music
  - e.g. K64 in C major

![image-20240326143319429](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240326143319429.png?raw=true)

## 4. Seventh chords and Tonal Musical Analysis

**Topics**: Seventh chords, Resolution, Voice leading,  Functional harmony

### 4.1 Seventh chords

Seventh chord: triad+seventh

| Triad | 7th Interval | Chord Symbol                | Chord Name          |
| ----- | ------------ | --------------------------- | ------------------- |
| M     | M7           | Cmaj7/CM7                   | major 7th           |
| M     | m7           | C7                          | dominant 7th        |
| m     | m7           | Cm7/C-7                     | minor 7th           |
| dim   | m7           | Cø7/Cm7b5                   | half-diminished 7th |
| m     | M7           | CmM7                        | minor major 7th     |
| dim   | dim7         | C°7/Cm(b7)b5                | diminished 7th      |
| Aug   | M7           | Caug$^{\text{maj7}}$ / C+M7 | augmented major 7th |

### 4.2 Diatonic seventh chords

- e.g. Diatonic seventh chords of C major

![image-20240326140447757](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240326140447757.png?raw=true)

- e.g. Diatonic seventh chords of C minor (not commonly used)
  - Notice the fifth degree of C minor is a Gm7 instead of a G7, which renders the V7-i progression impossible

![image-20240326140736387](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240326140736387.png?raw=true)

- e.g. Diatonic seventh chords of C (partially) harmonic minor (commonly used)

  - In the G7 chord and  Bm(b7)b5 chord the 7th degree is raised
  - The 7th degree stays the same in the rest of the chords (thus partially) 

![image-20240326141241157](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240326141241157.png?raw=true)

### 4.3 Inversion of 7th chords

- e.g. Inversions of a C major 7th in C major

![image-20240326225118242](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240326225118242.png?raw=true)

[Every possible Chord Symbol EXPLAINED](https://www.youtube.com/watch?v=aMLdWrZqwLg)

### 4.4 Resolution

**Resolution** is the move of a note or chord from dissonance to a consonance

- Tension -> release, unstable -> stable
- Dissonance: usually refers to half step or tritone

Resolution of intervals:

- Augmented intervals are resolved by moving outwards

- Diminished intervals are resolved by moving inwards

  - e.g. resolution of A4 and d5 intervals (both of which are tritones)

![image-20240326152132924](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240326152132924.png?raw=true)

Resolution of dominant 7ths

- The 3rd and 7th degree of the dominant 7th forms a dim5 interval -> resolved by moving inwards
- Resolution of a V7 chord leads to a I tonic triad (V7-I)
  - e.g. resolution of G7 (B->C, F->E)

![image-20240326152521437](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240326152521437.png?raw=true)

Resolution of half-diminished 7ths

- The root and 3th degree of the half-diminished 7th forms a dim5 interval -> resolved by moving inwards
- Resolution of a viim7b5 chord leads to a I tonic triad (viim7b5-I)
  - e.g. resolution of Bm7b5 (B->C, F->E, )

![image-20240326152934971](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240326152934971.png?raw=true)

### 4.5 Voice leading

**Voice leading** is a technique of connecting chord progression with individual melodic lines (instead of chords themselves)

Principles of voice leading:

- Move each voice the shortest distance possible
- Avoid voice crossing
- Avoid parallel fifths and octaves
  - e.g. Voice leading of a IV-V-iii-vi progression in C major

![image-20240326165847953](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240326165847953.png?raw=true)

- Note 1: the fifth of a triad/7th can be omitted in voice leading as it does not imply the characteristic of the chord
- Note 2: a common 4 part voicing structure is a SATB choir. (S-soprano, A-alto, T-tenor and B-bass)

[How to Harmonize a Melody (Modern 4 part voice leading)](https://www.youtube.com/watch?v=TTNhx2ZdWdI)

**Counterpoint** exists before voice leading and is the relationship between two or more musical lines. (i.e. note against note)

- The permitted intervals between the lines are: m2/M2, m3/M3, P5, m6/M6, unison/8ve
- The line should move as little as possible (<=p4), counter move M2 after big jump 
- [Other rules to consider](https://en.wikipedia.org/wiki/Counterpoint#Considerations_for_all_species)
  - e.g. [An example of third species counterpoint](https://en.wikipedia.org/wiki/Counterpoint#Third_species)

![6wlnlm82](https://github.com/minth1468/music-theory-101/blob/main/assets/6wlnlm82.png?raw=true)

  - e.g. [An example of fourth species counterpoint](https://en.wikipedia.org/wiki/Counterpoint#Fourth_species) (Permitted dissonance if caused by suspended notes and resolved immediately)

![azgcb4rk](https://github.com/minth1468/music-theory-101/blob/main/assets/azgcb4rk.png?raw=true)

Suspended chord (or **sus chord**) is related to the fourth species counterpoint.
- The third of the chord is omitted and replaced with a P4 or a M2, denoted sus4 and sus2.
  - e.g. Csus4 and Csus2 chord

    ![image-20240326180835542](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240326180835542.png?raw=true)

  - e.g. A suspended V7-I resolution with a Isus4 chord
  
  ![image-20240326181235537](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240326181235537.png?raw=true)

- Modern usage of suspended chords (in Jazz/Pop, etc.  music) does not necessarily involve suspended resolution (i.e. sus chords are used to add color to chords) 
  - e.g. In popular music the IV/5 chord (or V9sus4) often substitutes the V7 chord
  
  ![image-20240329140049357](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240329140049357.png?raw=true)


[Example of voice leading in pop music](https://www.bilibili.com/video/BV1Hr4y127dF?t=59.6).

### 4.6 Functional harmony

In functional harmony, every chord serves a tonality function.

**Table. Harmonic function in Major and minor**

| Function        | Major Degree | Minor Degree     |
| --------------- | ------------ | ---------------- |
| T (tonic)       | I, iii, vi   | i, (VII-)III, VI |
| S (subdominant) | ii, IV       | ii°, iv          |
| D (Dominant)    | V7, vii°     | V7, vii°         |

Harmonic progression usually follows the sequence of **T-S-D-T**

- Duplication of function is allowed (e.g. T-T, S-S, D-D)
- Omission in the sequence is allowed (e.g. T-S-T, T-D-T)

**Table. Typical progression loops**

| Progression                         | Functional Harmony Analysis |
| ----------------------------------- | --------------------------- |
| COF progression (1-4-7-3-6-2-5-1)   | T-S-D-T-T-S-D-T             |
| Canon progression (1-5-6-3-4-1-4-5) | T-D-T-T-S-T-S-D             |
| 4-5-3-6                             | S-D-T-T                     |
| 4-5-3-4                             | S-D-T-S                     |
| 1-6-4-5                             | T-T-S-D                     |
| 4-5-6 (6-7-1 in minor)              | T-D-T                       |
| 4-5-3-6-2-5-1                       | S-D-T-T-S-D-T               |

Harmonic flowchart (another presentation of the T-S-D-T rule)

![harmony-function-diagram-major](https://github.com/minth1468/music-theory-101/blob/main/assets/harmony-function-diagram-major.svg?raw=true)

![harmony-function-diagram-minor](https://github.com/minth1468/music-theory-101/blob/main/assets/harmony-function-diagram-minor.svg?raw=true)

[Song examples with different chord progressions](https://www.youtube.com/playlist?list=PLlx2eo2tD6KpfGmE-MXwcIRQh21neAKsK)

## 5. Chromatic Musical Analysis (Part I)

**Topics**: Modes, Modal interchange, Tritone substitution, Secondary dominant/diminished chords, Modulation

### 5.1 Modes

**Diatonic mode**: any scale that

- has seven notes
- follows a step sequence of WWH-WWWH

There are seven diatonic modes.

**Table. Diatonic modes and scales**

| Name       | Property      | Scale                         |
| ---------- | ------------- | ----------------------------- |
| Ionian     | Major         | 1234567                       |
| Dorian     | Aeolian #6    | 12 b3 456 b7  or 2345671      |
| Phrygian   | Aeolian b2    | 1 b2 b3 45 b6 b7 or 3456712   |
| Lydian     | Ionian #4     | 123 #4 567 or 4567123         |
| Mixolydian | Ionian b7     | 123456 b7 or 5671234          |
| Aeolian    | Minor         | 12 b3 45 b6 b7 or 6712345     |
| Locrian    | Aeolian b2 b5 | 1 b2 b3 4 b5 b6 b7 or 7123456 |

e.g. [7 modes on 1 Beatles song](https://www.youtube.com/watch?v=roFVo0ePOZw)

- D Dorian has the same notes as C major, but has different tonal center.
  - D Dorian resolves to D while C major resolves to C.

- Bright to Darkest:
  - Lydian - Ionian - Mixolydian - Dorian - Aeolian - Phrygian - Locrian
  - Lydian, Ionian, and Mixolydian are considered as major scales with a major tonic triad
  - Mixolydian, Dorian, Aeolian, and Phrygian are are considered as minor scales with a minor tonic triad
  - Locrian has a diminished tonic triad

### 5.2 Modal interchange

**[Modal interchange](https://www.youtube.com/watch?v=1dRA28cdt5c)**: borrowing of chords from parallel modes.

**Table. Possible chords of all parallel modes of C major**

| Mode         | I     | II     | III    | IV     | V      | VI     | VII    |
| ------------ | ----- | ------ | ------ | ------ | ------ | ------ | ------ |
| C Ionian     | Cmaj7 | Dm7    | Em7    | Fmaj7  | G7     | Am7    | Bm7b5  |
| C Dorian     | Cm7   | Dm7    | bEmaj7 | F7     | Gm7    | Am7b5  | bBmaj7 |
| C Phrygian   | Cm7   | bDmaj7 | bE7    | Fm7    | Gm7b5  | bAmaj7 | bBm7   |
| C Lydian     | Cmaj7 | D7     | Em7    | #Fm7b5 | Gmaj7  | Am7    | Bm7    |
| C Mixolydian | C7    | Dm7    | Em7b5  | Fmaj7  | Gm7    | Am7    | bBmaj7 |
| C Aeolian    | Cm7   | Dm7b5  | bEmaj7 | Fm7    | Gm7    | bAmaj7 | bB7    |
| C Locrian    | Cm7b5 | bDmaj7 | bEm7   | Fm7    | bGmaj7 | bA7    | bBm7   |

**Mario cadence**: bVI-bVII-I progression with bVI and bVII borrowed from parallel Aeolian

- e.g. [Super Mario Bros. Music - Level Complete](https://www.youtube.com/watch?v=3BsBXp6VkvU)
- e.g. [Butter-Fly (guitar cover with chords)](https://www.youtube.com/watch?v=M0puITrUCms)

**Picardy third** or Picardy cadence: a major tonic chord borrowed at the end of a musical section that is either modal or in a minor key.

- e.g. Raise third in Am to obtain A (in a minor)
- e.g. [ライアーダンサー](https://www.youtube.com/watch?v=UHbmkxv-874)
- e.g. [アヤノの幸福理論](https://www.youtube.com/watch?v=pLYKKC-EpjA) (Picardy third + DC)

**Neapolitan six**

- A bIIM7 chord borrowed from parallel Phrygian scale
- Usually used in first inversion (denoted N6)
- Usage 1: substitute ii in ii-V-I progression (N6-V-I)
  - e.g. N6 in C major

   ![image-20240328155122869](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240328155122869.png?raw=true)

- Usage 2: modulate down half step

### 5.3 Tritone substitution

**[Tritone substitution](https://www.youtube.com/watch?v=aLdqLjA0NHE)**: substituting the V7 chord in a V7-I progression with a bII7 chord.

- The core of V7-1 progression is the resolution of the tritone existing in V7 (e.g. F, B in G7)
- The inversion of tritone is still a tritone (e.g. F, B and B, F)
- Thus a new dominant 7th based on the inverted tritone (bII7) has the same tension as V7 (e.g. bD7 and G7)
- Denoted bII7 or bV7/V
  - e.g. Tritone substitution in C major (notice the highlighted tritones)

![image-20240327131055487](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240327131055487.png?raw=true)

**Italian 6th**/ **German 6th**/ **French 6th**: tritone substitution is usually notated as augmented 6th in classical music context.

- Italian sixth (It+6) enharmonically = bD7 without 5th
- German sixth (Gr+6) enharmonically = bD7
- French sixth (Fr+6) enharmonically = bD7b5

![image-20240327133729165](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240327133729165.png?raw=true)

**Related ii chords**: in a ii7-V7-I progression

- V7 can be substituted with bII7
- ii7 can be substituted with bvi7 (related ii7 chord of bII7)

### 5.4 Secondary dominant/diminished chords

Tonicization:  treat any chord like a tonic by applying a V7-I progression.

**Secondary dominant**: a V or V7 chord that resolves to a tonicized chord.

- e.g. When Am7 in C major is tonicized, E7 is a secondary dominant chord
- Denoted V7/vi, the progression is written as V7/vi-vi
- vii° and ii° are not tonicized since they are diminished
- e.g. Secondary dominant 7th chords in C major and c minor

![image-20240327181403620](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240327181403620.png?raw=true)

![image-20240327181413998](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240327181413998.png?raw=true)

**Secondary diminished**: a (half) diminished chord that resolves to a tonicized chord.

- e.g. When Am7 in C major is tonicized, #G°7 is a secondary diminished chord
- Note that the secondary diminished of a minor chord is a diminished chord, that of a major chord can be either half diminished or diminished 
- vii°/III enharmonically = ii° but resolves differently (vii°/III-III, ii°-V-i)
- e.g. Secondary diminished chords in C major and c minor

![sec-dim-dim7ths-in-major](https://github.com/minth1468/music-theory-101/blob/main/assets/sec-dim-dim7ths-in-major.svg?raw=true)

![sec-dim-dim7ths-in-minor](https://github.com/minth1468/music-theory-101/blob/main/assets/sec-dim-dim7ths-in-minor.svg?raw=true)

  - e.g. [Secondary dominant and diminished example](https://www.youtube.com/watch?v=PqD6R8RzZ3o)

  - e.g. [光の中へ](https://www.youtube.com/watch?v=29t3pJd75XU)

### 5.5 Diminished 7th Chords

[Resolution of diminished 7th chord](https://www.youtube.com/watch?v=L6UArCYBHLc): diminished 7th chord can resolve into any major or minor chord.

- All inversions of diminished 7th chord are enharmonically equal
- diminished 7th chord can resolve either half-step up (common), half-step down or to chord with same root note (auxiliary diminished 7th chord)

### 5.6 Modulation

[**Modulation**](https://en.wikipedia.org/wiki/Modulation_(music)): key change

- Common-chord modulation: key change connected with a shared chord
  - e.g. bA in c minor and bA major
  - e.g. Chopin, Prelude in C minor, Op. 28, No. 20.

![1920px-Chopin_-_Prelude_in_C_minor_opening_modulation](https://github.com/minth1468/music-theory-101/blob/main/assets/1920px-Chopin_-_Prelude_in_C_minor_opening_modulation.png?raw=true)

- Enharmonic modulation: key change connected with enharmonically equal chords (usually related to tritone substitution)
  - e.g. Schubert, String Quartet No. 13 Op.29, I


![1920px-Schubert_-_op._29,_D.804,_I,_mm.144-49_enharmonic_modulation](https://github.com/minth1468/music-theory-101/blob/main/assets/1920px-Schubert_-_op._29,_D.804,_I,_mm.144-49_enharmonic_modulation.png?raw=true)

- Common-tone modulation: key change connected with sustained or repeated shared pitch
  - e.g. Mozart, Fantasia in C minor, K. 475

![Common_tone_modulation_between_chromatic_mediants_in_Mozart_K_475](https://github.com/minth1468/music-theory-101/blob/main/assets/Common_tone_modulation_between_chromatic_mediants_in_Mozart_K_475.png?raw=true)

- Phrase modulation: key change with one phrase ends with a cadence in the original key, and the next phrase begins in the destination key without any transition material linking the two keys
- Chain modulation: distant key change connected with close related key changes
  - e.g.  C major - G major - D major
  - e.g. C major - C minor - bE major
- Chromatic modulation: key change connected with chromatic progression

  - e.g. [リセット](https://youtu.be/4oenZkqzdW4?t=79 )
  - e.g. [光の中へ](https://www.youtube.com/watch?v=29t3pJd75XU)

## 6. Chromatic Musical Analysis (Part II) and Others

**Topics**: Upper chord extensions, Altered chords, Exotic scales, Negative harmony

### 6.1 Upper chord extensions and altered chords

[Chord extensions and alterations](https://www.learnjazzstandards.com/blog/learning-jazz/jazz-theory/chord-extensions-alterations/)

**Extended chords** add color tones in addition to the basic chord tones (triads and 7th chords) with 9th, 11th, and 13th notes. (following the Tertian rule)

- For a chord to be called extended chord it must have a 3rd and 7th tone;
- The root establishes the chord tonality (CMaj7 vs DMaj7);
- The 3rd & 7th (Guide Tones) establish the chord quality (CMaj7 vs C7 vs Cm7);
- The 5th establishes whether the chord is diminished or augmented (Co vs Cø vs C+7). [Source](https://www.thejazzpianosite.com/jazz-piano-lessons/jazz-chords/extensions-alterations)

| Chord | Property | Extensions       |
| ----- | -------- | ---------------- |
| M7    | Major    | 9th, #11th, 13th |
| m7    | Minor    | 9th, 11th, 13th  |
| 7     | Dominant | 9th, #11th, 13th |

Note: 

1. 13th chords usually do not include the 11th in the chord.
2. Extended chords are usually used as Major, minor, or Dominant only.

- e.g. C Major chord extensions

![major-chord-extension](https://cdn.pianogroove.com/wp-content/uploads/2022/03/1-C-Major-Extensions.jpg?raw=true)

- e.g. C Dominant chord extensions

![dom-chord-extension](https://cdn.pianogroove.com/wp-content/uploads/2022/03/7-C7-Chord-Voicings.jpg?raw=true)

**Altered chords**: one or more notes in the diatonic chord are altered to a chromatic note (e.g. raised or lowered a semitone)， usually used to replace the dominant chord.

- Borrowed chords (modal interchange), secondary dominant chords, and substituted dominant chords (tritone substitution) can all be seen as altered chords.
- Often seen in Jazz context
- Alt dominant chord: root (I) + 3rd + b5 and/or #5 (b5 is often written as #11) + b7 + b9 and/or #9, and b13.
- An altered C7 chord is denoted as C7alt (the altered notes are usually not specified and can change according to context)
- e.g. examples of C7alt chord

![altered dominant chords](https://hellomusictheory.com/wp-content/uploads/2020/11/altered-chords-2-1536x270.png?raw=true)

**Table. Upper chord alterations**

| Chord Proterty | Alterations           |
| -------------- | --------------------- |
| Major          | b9, #9, #11, b13, #13 |
| Minor          | b9, b11, #11, b13     |
| Dominant       | b9, #9, #11, b13      |

Dominant 7#9 chord: known as the **Hendrix Chord**, used widely in funk, blues, jazz and rock.

- The #9 note can be seen as a minor 3rd stacked on the major 3rd of the dominant chord. (consider C7#9 as a C blues scale played over a C7 chord)

Dominant 7b9 chord: widely used in funk music (funk guitar strumming).

- A dominant 7b9 chord can be seen as a diminished 7th chord stacked on the root note.
  - e.g. A C7b9 chord is enharmonically equal to Edim7/C.
  - Recall that the diminished 7th chord can be resolved into any note: the diminished chord can be played over any note (serving as root note).
  - This leads to the funk guitar strumming style: the same diminished 7th chord can be played throughout the whole chord progression.

A b5 note is enharmonically equal to #11, and a #5 note is enharmonically equal to b13.

**Resolution of altered Chords**: Altered chords solves to a major/minor chord 5th below (Valt-I/i), or a major chord a semitone below (bIIalt-I, tritone substitution).

**Altered chord and scale**: Chords are viewed as scales rearranged vertically in jazz music. (Altered Chord = Altered Scale)

- e.g. C7b9b13 = 1 b2(b9) 345 b6(b13) b7 =  C Phrygian dominant (see section 6.2)

[Music Theory Minute #1: Chord Extensions and Alterations]([https://www.youtube.com/watch?v=fzgYxTcaGGo](https://www.youtube.com/watch?v=yc7udUxD7eU&list=PL-ZQIvQFPv4JFew7HeFetA0VbnKgWzbAf&index=1))

**69 chord**

tbc

### 6.2 Exotic scales

**Harmonic minor**

- e.g. Diatonic 7th chords of C harmonic minor

![image-20240328164409558](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240328164409558.png?raw=true)

**Table. Modes of harmonic minor**

| Name                      | Scale                |
| ------------------------- | -------------------- |
| Harmonic minor            | 12 b3 45 b6 7        |
| Locrian ♮6                | 1 b2 b3 4 b5 6 b7    |
| Ionian Augmented(#5)      | 1234 #5 67           |
| Dorian #4                 | 12 b3 #4 56 b7       |
| **Phrygian dominant(#3)** | 1 b2 345 b6 b7       |
| Lydian  #2                | 1 #2 3 #4 567        |
| Super Locrian bb7         | 1 b2 b3 b4 b5 b6 bb7 |

- e.g. [純白トロイメライ](https://www.youtube.com/watch?v=OnEs0dT9g8Q)

**Phrygian dominant mode** is widely used in metal and jazz music (exotic, foreign flavor)

- e.g. Diatonic 7th chords of C Phrygian dominant

![image-20240328173644558](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240328173644558.png?raw=true)

- e.g. [Dream Theater - Scene Six: Home](https://www.youtube.com/watch?v=GqHSrJ2mLo0)
- e.g. [Dream Theater - In the Name of God](https://youtu.be/MSI3KSo9DjM?t=29)
- **Andalusian cadence**: i–VII–VI–V7 chord progression from a modulation between Phrygian scale (i, VI, VII) and Phrygian dominant scale (V7)
  - Associated with Spanish music (V7 is the tonic center in this context)
  - e.g. [El pueblo unido jamàs serà vencido](https://www.youtube.com/watch?v=NwiML8pCB7E) (Andalusian cadence + COF progression)
  - e.g. [デビルマン theme](https://www.youtube.com/watch?v=XRmzkAT3bLI)

**Melodic minor**

[What are the Melodic Minor Modes](https://www.youtube.com/watch?v=E_mto_Dkpo0)

- e.g. Diatonic 7th chords of C melodic minor

![image-20240328165356504](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240328165356504.png?raw=true)

**Table. Modes of melodic minor**

| Name                               | Scale               |
| ---------------------------------- | ------------------- |
| Melodic minor (Jazz minor)         | 12 b3 4567          |
| Dorian b9                          | 1 b2 b3 456 b7      |
| Lydian Augmented(#5)               | 123 #4 #5 67        |
| Lydian dominant(b7)/overtone scale | 123 #4 56 b7        |
| Mixolydian b13(b6)                 | 12345 b6 b7         |
| Locrian #2                         | 12 b3 4 b5 b6 b7    |
| Super(b4) Locrian                  | 1 b2 b3 b4 b5 b6 b7 |

**Harmonic major**

- Mimics the A2 in harmonic minor
- e.g. Diatonic 7th chords of C harmonic major

![image-20240328170302443](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240328170302443.png?raw=true)

**Table. Modes of harmonic major** 

| Name                              | Scale               |
| --------------------------------- | ------------------- |
| Harmonic major                    | 12345 b6 7          |
| Dorian b5                         | 12 b3 4 b5 6 b7     |
| Phrygian b4                       | 1 b2 b3 b4 5 b6 b7  |
| Melodic minor #4                  | 12 b3 #4 567        |
| Mixolydian b2                     | 1 b2 3456 b7        |
| Lydian Augmented(#5) #2           | 1 #2 3 #4 #5 67     |
| Locrian bb7 (Diminished Blues b9) | 1 b2 b3 4 b5 b6 bb7 |

**Double harmonic major**

- Also named Byzantine scale or Arabic scale
- Inherent tritone substitution (bII7: b2-4-b6-7)
- Have iii and III simultaneously
- Inherent V7b9 
- Symmetry (same as Dorian)
- e.g. Diatonic 7th chords of C  double harmonic major

![image-20240328201125863](https://github.com/minth1468/music-theory-101/blob/main/assets/image-20240328201125863.png?raw=true)

**Table. Modes of double harmonic major** 

| Name                      | Scale                |
| ------------------------- | -------------------- |
| Harmonic major            | 1 b2 345 b6 7        |
| Lydian #2 #6              | 1 #2 3 #4 5 #6 7     |
| Ultra Phrygian            | 1 b2 b3 b4 5 b6 bb7  |
| Double(#4) harmonic minor | 12 b3 #4 5 b6 7      |
| Oriental                  | 1 b2 34 b5 6 b7      |
| Ionian #2 #5              | 1 #2 34 #5 67        |
| Locrian bb3 bb7           | 1 b2 bb3 4 b5 b6 bb7 |

- e.g. [Miserlou](https://www.youtube.com/watch?v=mKpsuGMeqHI) (Double harmonic major - Phrygian dominant)
- **Double harmonic minor** is also called Hungarian minor scale or Gypsy minor scale

Figure. Characteristic chords of scales

![tsse2mrtipic1](https://github.com/minth1468/music-theory-101/blob/main/assets/tsse2mrtipic1.jpg)

### 6.3 Negative harmony

tbc.
