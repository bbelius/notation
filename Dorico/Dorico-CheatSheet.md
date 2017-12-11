## Dorico 1.2 Key-Commands Cheat-Sheet (english) v0.3

- [Dorico 1.2 Key-Commands Cheat-Sheet (english) v0.3](#dorico-1-2-key-commands-cheat-sheet-english-v0-3)
    - [Write-Mode](#write-mode)
        - [Note Articulation](#note-articulation)
        - [Barline  ( `⇧` + `b` )](#barline-b)
        - [Clef  ( `⇧` + `c` )](#clef-c)
        - [Dynamic  ( `⇧` + `d` )](#dynamic-d)
        - [Hold / Pause  ( `⇧` + `h` )](#hold-pause-h)
        - [Key Signature  ( `⇧` + `k` )](#key-signature-k)
        - [Lyrics  ( `⇧` + `l` )](#lyrics-l)
        - [Ornament  ( `⇧` + `o` )](#ornament-o)
        - [Chord  ( `⇧` + `q` )](#chord-q)
        - [Tempo  ( `⇧` + `t` )](#tempo-t)
        - [Playing Technique  ( `⇧` + `p` )](#playing-technique-p)
        - [Other Popups](#other-popups)
        - [Note Duration](#note-duration)
        - [Input Modes and Actions during Input](#input-modes-and-actions-during-input)
    - [Setup Mode](#setup-mode)
    - [Play Mode](#play-mode)
    - [Global](#global)
- [Tokens](#tokens)
    - [Project Tokens](#project-tokens)
    - [Flow Tokens](#flow-tokens)
    - [Other Tokens](#other-tokens)


### Write-Mode

| Action                               | Shortcut                |
| ------------------------------------ | ----------------------- |
| Transpose Pitch Down / Up a Note     | `Alt` + `↓`/`↑`         |
| Transpose Pitch Octave Down / Up     | `Alt` + `Ctr` + `↓`/`↑` |
| Shorten/Lengthen Duration            | `⇧` + `Alt` + `←`/`→`   |
| Extend Selection Left / Right        | `⇧` + `←`/`→`           |
| Move Item (by Grid-Setting)          | `Ctr` + `Alt` + `←`/`→` |
| Paste Current Selection              | `Alt` + *left-click*    |
|                                      |                         |
| Goto Page View                       | `Ctr` + `Alt` + `1`     |
| Goto Galley  View                    | `Ctr` + `Alt` + `2`     |
|                                      |                         |
| Set Natural                          | `0`                     |
| Set Flat                             | `-`                     |
| Set Sharp                            | `=`                     |
|                                      |                         |
| Respell Note Name Above (enharmonic) | `Alt` + `=`             |
| Respell Note Name Below (enharmonic) | `Alt` + `-`             |
|                                      |                         |
| Cross-Staff Move Note Up / Down      | `n`/`m`                 |


#### Note Articulation

| Action                           | Shortcut |
| -------------------------------- | -------- |
| Accent Symbol                    | `[`      |
| Staccato Symbol                  | `]`      |
| Tenuto Symbol                    | `#`      |
| Set Staccato-Tenuto articulation | `~`      |
| Marcato Symbol                   | `'`      |
| Set Stress articulation          | `{`      |
| Staccatissimo Symbol             | `}`      |
| Unstress Symbol                  | `@`      |


#### Barline  ( `⇧` + `b` )

| Action                | Shortcut              |
| --------------------- | --------------------- |
| Create number of Bars | `+` + *number*        |
| Delete number of Bars | `-` + *number*        |
| Normal Barline        | &#x7c; ⟺ single       |
| Double Barline        | &#x7c;&#x7c; ⟺ double |
| Final Barline         | &#x7c;] ⟺ fin         |
| Dashed Barline        | : ⟺ dash              |
| Tick Barline          | ' ⟺ tick              |
| Short Barline         | , ⟺ short             |
| Start Repeat          | &#x7c;: ⟺ start       |
| End Repeat            | :&#x7c; ⟺ end         |
| Bidirectional Repeat  | :&#x7c;: ⟺ endstart   |


#### Clef  ( `⇧` + `c` )

| Action               | Shortcut     |
| -------------------- | ------------ |
| Treble G             | g ⟺ treble   |
| Bass F               | f ⟺ bass     |
| Tenor C              | ct ⟺ tenor   |
| Alto C               | ca ⟺ alto    |
| Treble G 8ba         | g8ba ⟺ g8d   |
| Treble G 15ba        | g15ba ⟺ g15d |
| Treble G 8va         | g8va ⟺ g8u   |
| Treble G 15va        | g15va ⟺ g15u |
| Bass F 8ba           | f8ba ⟺ f8d   |
| Bass F 15ba          | f15ba ⟺ f15d |
| Bass F 15va          | f15va ⟺ 15u  |
| Unpitched Percussion | perc         |
| 4-string Tablature   | tab4         |
| 6-string Tablature   | tab6         |
| Baritone bass        | baritonebass |
| Baritone             | baritone     |
| Mezzo soprano        | mezzo        |
| Soprano G            | soprano      |
| Sub-Bass             | subbass      |
| Invisible            | invisible    |


#### Dynamic  ( `⇧` + `d` )

| Action      | Shortcut         |
| ----------- | ---------------- |
| Dynamics    | pppppp to ffffff |
| Crescendo   | < ⟺ cresc.       |
| Diminduendo | > ⟺ dim.         |
|             | <>               |
|             | ><               |
|             | piu mp           |
| Sforzando   | sfz              |


#### Hold / Pause  ( `⇧` + `h` )

| Action              | Shortcut            |
| ------------------- | ------------------- |
| Fermata             | fermata             |
| Short Fermata       | shortfermata        |
| Very Short Fermata  | veryshortfermata    |
| Long Fermata        | longfermata         |
| Very Long Fermata   | verylongfermata     |
| Short Henze Fermata | shorthenzefermata   |
| Long Henze Fermata  | longhenzefermata    |
| Caesura             | // ⟺ caesura        |
| Thick Caesura       | caesurathick        |
| Curved Caesura      | caesuracurved       |
| Short Caesura       | caesurashort        |
| Breathmark          | , ⟺ breathmarkcomma |
| Tick Breathmark     | breathmarktick      |
| Salzedo Breathmark  | breathmarksalzedo   |
| Curlew              | curlew              |


#### Key Signature  ( `⇧` + `k` )

| Action                | Shortcut      |
| --------------------- | ------------- |
| Open / Atonal         | open ⟺ atonal |
| Major Keys            | C - B C# - Bb |
| Major Keys (number $) | $s ⟺ $#       |
| Minor Key             | c - h c# - bb |
| Minor Key (number $)  | $f ⟺ $b       |


#### Lyrics  ( `⇧` + `l` )

| Action                                  | Shortcut              |
| --------------------------------------- | --------------------- |
| Hard Space                              | `⇧` + `Alt` + `Space` |
| Switch From Lyric to Chorus/Translation | `Alt` + `↓`/`↑`       |
| Switch Vers                             | `↓`/`↑`               |
| Add Elision                             | `_`                   |
| Hyphen in Word                          | `Alt` + `-`           |


#### Ornament  ( `⇧` + `o` )

| Action                            | Shortcut |
| --------------------------------- | -------- |
| Mordent                           | mor      |
| Inverted Mordent                  | invmor   |
| Turn                              | turn     |
| Inverted Turn                     | invturn  |
| Trill                             | tr       |
| Glissando to Next Note (straight) | gliss    |
| Glissando to Next Note (wavy)     | glisswav |
| Arpeggio (up)                     | arp      |
| Arpeggio (down)                   | arpdown  |
| Bracket                           | bracket  |


#### Tempo  ( `⇧` + `t` )

| Action               | Shortcut        |
| -------------------- | --------------- |
| Tempo Name           | e.g. largo      |
| Tempo Speed          | e.g. q=50       |
| Tempo Name and Speed | e.g. largo q=50 |
| Ritenuto             | rit             |
| Accelerando          | accel           |


#### Chord  ( `⇧` + `q` )

| Action                                  | Shortcut          |
| --------------------------------------- | ----------------- |
| Move to next Bar                        | `Tab`             |
| Move to previous Bar                    | `⇧` + `Tab`       |
| Move to next Beat                       | `Space`           |
| Move to previous Beat                   | `⇧` + `Space`     |
| Move to next / previous Chord           | `⇧` + `←`/`→`     |
| Remove enharmonic spelling override     | `Alt` + `s`       |
| Remove all enharmonic spelling override | `⇧` + `Alt` + `s` |


#### Playing Technique  ( `⇧` + `p` )

| Action        | Shortcut |
| ------------- | -------- |
| Pedal         | ped      |
| End Pedal     | *        |
| Sostenuto     | sost     |
| End Sostenuto | s*       |
| Unacorda      | unacorda |
| End Unacorda  | u*       |
| Retake        | ^        |


#### Other Popups

| Action         | Shortcut  |
| -------------- | --------- |
| Time Signature | `⇧` + `m` |
|                |           |
| Text           | `⇧` + `x` |
|                |           |
| Fingering      | `⇧` + `f` |
|                |           |
| Cue            | `⇧` + `u` |
|                |           |
| Interval       | `⇧` + `i` |


#### Note Duration

| Action                  | Shortcut     |
| ----------------------- | ------------ |
| 128th-note duration     | *Numpad* `1` |
| 64th-note duration      | *Numpad* `2` |
| 32nd-note duration      | *Numpad* `3` |
| Sixteenth-note duration | *Numpad* `4` |
| Eighth-note duration    | *Numpad* `5` |
| Quarter-note duration   | *Numpad* `6` |
| Half-note duration      | *Numpad* `7` |
| Whole-note duration     | *Numpad* `8` |
| Breve note duration     | *Numpad* `9` |
| Dotted Note(s)          | `.`          |


#### Input Modes and Actions during Input

| Action                              | Shortcut                |
| ----------------------------------- | ----------------------- |
| Start Note Input                    | `Enter`                 |
| Start Note Input                    | `⇧` + `n`               |
| Caret/Cursor Advance                | `Space`                 |
| Move Cursor Left / Right            | `←`/`→`                 |
| Move Cursor Up/Down Staff           | `↑`/`↓`                 |
| Move Cursor Previous / Next Measure | `Ctr` + `←`/`→`         |
| Move Cursor to Top / Bottom Staff   | `Ctr` + `↑`/`↓`         |
| Delete Left                         | `Backspace`             |
| Delete Right                        | `Delete`                |
|                                     |                         |
| Extend Selection Left / Right       | `⇧` + `←`/`→`           |
| Repeat Item                         | `r`                     |
| Next Voice                          | `v`                     |
|                                     |                         |
| Toggle Note Input Mode              | `i`                     |
| Toggle Lock Note Duration           | `l`                     |
| Toggle Tie                          | `t`                     |
| Toggle Force Note Duration          | `o`                     |
| Toggle Chord Input (bottom up)      | `q`                     |
| Toggle Rests                        | `,`                     |
| Toggle Grace Note                   | `/`                     |
|                                     |                         |
| Start Slur                          | `s`                     |
| Stop Slur                           | `⇧` + `s`               |
| Tuplet Popup                        | `;`                     |
|                                     |                         |
| Enter Pitch A                       | `a`                     |
| Enter Pitch B                       | `b`                     |
| Enter Pitch C                       | `c`                     |
| Enter Pitch D                       | `d`                     |
| Enter Pitch E                       | `e`                     |
| Enter Pitch F                       | `f`                     |
| Enter Pitch G                       | `g`                     |
| Enter Pitch 8ve higher              | `⇧` + `Alt` + *Pitch*   |
| Enter Pitch 8ve lower               | `Ctr` + `Alt` + *Pitch* |
|                                     |                         |
| Rehearsal Mark                      | `⇧` + `a`               |
| Slur                                | `s`                     |
| Crescendo                           | `⇧` + `<`               |
| Diminuendo                          | `⇧` + `>`               |


### Setup Mode

| Action                           | Shortcut  |
| -------------------------------- | --------- |
| Add Instrument to Player         | `⇧` + `i` |
| New Flow                         | `⇧` + `f` |
| New Layout (Custom Score Layout) | `⇧` + `l` |
| New Player                       | `⇧` + `p` |


### Play Mode

| Action                    | Shortcut |
| ------------------------- | -------- |
| Set Draw Tool             | `d`      |
| Set Erase Tool            | `e`      |
| Set Object Selection Tool | `s`      |
| Zoom In / Out             | `z`/`x`  |


### Global

| Action                     | Shortcut                  |
| -------------------------- | ------------------------- |
| Dorico Help                | `F1`                      |
| Transport Window           | `F2`                      |
| Mixer Window               | `F3`                      |
| View Full Screen           | `F11`                     |
| Setup Mode                 | `Ctr` + `1`               |
| Goto Write Mode            | `Ctr` + `2`               |
| Engrave Mode               | `Ctr` + `3`               |
| Play Mode                  | `Ctr` + `4`               |
| Print Mode                 | `Ctr` + `5`               |
| Goto Toolbar               | `Ctr` + `6`               |
| Goto Left Panel            | `Ctr` + `7`               |
| Goto Bottom Panel          | `Ctr` + `8`               |
| Goto Right Panel           | `Ctr` + `9`               |
| Goto Bottom Pane           | `Alt` + `Enter`           |
| Run Last Script            | `Alt` + `Ctr` + `⇧` + `r` |
|                            |                           |
| Preferences                | `Ctr` + `,`               |
| Engraving Options          | `Ctr` + `⇧` + `e`         |
| Layout Options             | `Ctr` + `⇧` + `l`         |
| Playback Options           | `Ctr` + `⇧` + `p`         |
|                            |                           |
| Create Frame Break         | `Alt` + `Ctr` + `f`       |
| Create System Break        | `Alt` + `Ctr` + `s`       |
|                            |                           |
| Toggle Hand / Marquee Tool | `h`                       |
| Select None                | `Ctr` + `d`               |
|                            |                           |
| Start / Stop Playback      | `Space`                   |
| Zoom to Whole Page         | `Ctr` + `Alt` + `0`       |
| Zoom In / Out              | `Ctr` + `-`/`=`           |
|                            |                           |
| New                        | `Ctr` + `n`               |
| Open                       | `Ctr` + `o`               |
| Close Project              | `Ctr` + `⇧` + `w`         |
| New Window                 | `Ctr` + `⇧` + `t`         |
|                            |                           |
| Copy                       | `Ctr` + `c`               |
| Paste                      | `Ctr` + `v`               |
| Undo                       | `Ctr` + `z`               |
| Redo                       | `Ctr` + `y`               |
| Cut                        | `Ctr` + `x`               |
| Delete                     | `Delete`                  |


## Tokens

### Project Tokens

| Fieldname         | Token                        |
| ----------------- | ---------------------------- |
| Title             | `{@projecttitle@}`           |
| Subtitle          | `{@projectsubtitle@}`        |
| Dediction         | `{@projectdedication@}`      |
| Composer          | `{@projectcomposer@}`        |
| Arranger          | `{@projectarranger@}`        |
| Lyricist          | `{@projectlyricist@}`        |
| Artist            | `{@projectartist@}`          |
| Copyist           | `{@projectcopyist@}`         |
| Publisher         | `{@projectpublisher@}`       |
| Editor            | `{@projecteditor@}`          |
| Copyright         | `{@projectcopyright@}`       |
| Work Number       | `{@projectworknumber@}`      |
| Composer Dates    | `{@projectcomposerdates@}`   |
| Composition Year  | `{@projectcompositionyear@}` |
| Other Information | `{@projectotherinfo@}`       |
| Layout Name       | `{@layoutname@}`             |


### Flow Tokens

| Fieldname         | Token                      |
| ----------------- | -------------------------- |
| Title             | `{@flow%title@}`           |
| Subtitle          | `{@flow%subtitle@}`        |
| Dediction         | `{@flow%dedication@}`      |
| Composer          | `{@flow%composer@}`        |
| Arranger          | `{@flow%arranger@}`        |
| Lyricist          | `{@flow%lyricist@}`        |
| Artist            | `{@flow%artist@}`          |
| Copyist           | `{@flow%copyist@}`         |
| Publisher         | `{@flow%publisher@}`       |
| Editor            | `{@flow%editor@}`          |
| Copyright         | `{@flow%copyright@}`       |
| Work Number       | `{@flow%worknumber@}`      |
| Composer Dates    | `{@flow%composerdates@}`   |
| Composition Year  | `{@flow%compositionyear@}` |
| Other Information | `{@flow%otherinfo@}`       |

Note: `%` inbetween the tokens is a placeholder for flow-number (ex. `{@flow3title@}` is the title of the third flow). Also you can write `{@flowtitle@}`.

### Other Tokens

| Fieldname    | Token             |
| ------------ | ----------------- |
| Page-number  | `{@page@}`        |
| Layout-name  | `{@layoutname@}`  |
| Player-names | `{@playernames@}` |
| Player-list  | `{@playerlist@}`  |
