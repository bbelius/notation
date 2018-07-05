# Dorico 2.0 Key-Commands Cheat-Sheet (english) v0.5

- [Dorico 2.0 Key-Commands Cheat-Sheet (english) v0.5](#dorico-20-key-commands-cheat-sheet-english-v05)
        - [Write-Mode](#write-mode)
                        - [Input Modes and Actions during Input](#input-modes-and-actions-during-input)
                        - [Note Articulation](#note-articulation)
                        - [Barline ( `⇧` + `b` )](#barline--%E2%87%A7--b)
                        - [Clef ( `⇧` + `c` )](#clef--%E2%87%A7--c)
                        - [Dynamic ( `⇧` + `d` )](#dynamic--%E2%87%A7--d)
                        - [Hold / Pause ( `⇧` + `h` )](#hold--pause--%E2%87%A7--h)
                        - [Key Signature ( `⇧` + `k` )](#key-signature--%E2%87%A7--k)
                        - [Lyrics ( `⇧` + `l` )](#lyrics--%E2%87%A7--l)
                        - [Ornament ( `⇧` + `o` )](#ornament--%E2%87%A7--o)
                        - [Tempo ( `⇧` + `t` )](#tempo--%E2%87%A7--t)
                        - [Chord ( `⇧` + `q` )](#chord--%E2%87%A7--q)
                        - [Playing Technique ( `⇧` + `p` )](#playing-technique--%E2%87%A7--p)
                        - [Repeats ( `⇧` + `r` )](#repeats--%E2%87%A7--r)
                        - [Other Popups](#other-popups)
                        - [Note Duration](#note-duration)
        - [Mixer](#mixer)
        - [Setup Mode](#setup-mode)
        - [Play Mode](#play-mode)
        - [Engrave Mode](#engrave-mode)
        - [Global](#global)
        - [Tokens](#tokens)
                        - [Project Tokens](#project-tokens)
                        - [Flow Tokens](#flow-tokens)
                        - [DateTime Tokens](#datetime-tokens)
                        - [Other Tokens](#other-tokens)

`$` is a placeholder for a valid number.

## Write-Mode

| Action                                 | Shortcut                |
| -------------------------------------- | ----------------------- |
| Cut (Scissors)                         | `u`                     |
| Extend Selection                       | `⇧` + *Arrow*           |
| Extend Selection L/R to Prev/Next Bar  | `Ctr` + `⇧` + `←`/`→`   |
| Move Item (by Grid-Setting)            | `Ctr` + `Alt` + `←`/`→` |
| Paste Current Selection                | `Alt` + *left-click*    |
| Shorten / Lengthen Duration            | `⇧` + `Alt` + `←`/`→`   |
| Transpose Pitch Down / Up a Note       | `Alt` + `↓`/`↑`         |
| Transpose Pitch Octave Down / Up       | `Alt` + `Ctr` + `↓`/`↑` |
|                                        |                         |
| Goto Galley  View                      | `Ctr` + `Alt` + `2`     |
| Goto Page View                         | `Ctr` + `Alt` + `1`     |
|                                        |                         |
| Set Flat                               | `-`                     |
| Set Natural                            | `0`                     |
| Set Sharp                              | `=`                     |
|                                        |                         |
| Respell Note Name Above (enharmonic)   | `Alt` + `=`             |
| Respell Note Name Below (enharmonic)   | `Alt` + `-`             |
|                                        |                         |
| Create Marker                          | `Alt` + `⇧` + `m`       |
| Cross-Staff Move Note Up / Down        | `n`/`m`                 |
| De-/Increase Rythmic Grid Resolution   | `Alt` + `[`/`]`         |
| Lengthen / Shorten Duration by Grid    | `Alt` + `⇧` + `←`/`→`   |
| Lower / Higher Pitch by Chromatic Step | `Alt` + `⇧` + `↓`/`↑`   |
| Move Left / Right                      | `Alt` + `←`/`→`         |
| Move by Grid                           | `Alt` + `Ctr` + *Arrow* |
| Navigate Up / Down Next Stave          | `Ctr` + `↓`/`↑`         |


#### Input Modes and Actions during Input

| Action                              | Shortcut                |
| ----------------------------------- | ----------------------- |
| Caret / Cursor Advance              | `Space`                 |
| Delete Left                         | `Backspace`             |
| Delete Right                        | `Delete`                |
| Move Cursor Left / Right            | `←`/`→`                 |
| Move Cursor Previous / Next Measure | `Ctr` + `←`/`→`         |
| Move Cursor Up/Down Staff           | `↑`/`↓`                 |
| Move Cursor to Top / Bottom Staff   | `Ctr` + `↑`/`↓`         |
| Start Note Input                    | `Enter`                 |
| Start Note Input                    | `⇧` + `n`               |
| Input unpitched notes, rests        | `y`                     |
|                                     |                         |
| Extend Selection Left / Right       | `⇧` + `←`/`→`           |
| Next Voice                          | `v`                     |
| Repeat Item                         | `r`                     |
|                                     |                         |
| Toggle Chord Input (bottom up)      | `q`                     |
| Toggle Force Note Duration          | `o`                     |
| Toggle Grace Note                   | `/`                     |
| Toggle Grace Note Slash             | `Alt` + `/`             |
| Toggle Lock Note Duration           | `l`                     |
| Toggle Note Input Mode              | `i`                     |
| Toggle Rests                        | `,`                     |
| Toggle Tie                          | `t`                     |
|                                     |                         |
| Start Slur                          | `s`                     |
| Stop Slur                           | `⇧` + `s`               |
| Tuplet Popup / End Tuplet Input     | `;`                     |
|                                     |                         |
| Enter Pitch A                       | `a`                     |
| Enter Pitch B                       | `b`                     |
| Enter Pitch C                       | `c`                     |
| Enter Pitch D                       | `d`                     |
| Enter Pitch E                       | `e`                     |
| Enter Pitch F                       | `f`                     |
| Enter Pitch G                       | `g`                     |
| Enter Pitch X                       | `x`                     |
| Enter Pitch 8ve higher              | `⇧` + `Alt` + *Pitch*   |
| Enter Pitch 8ve lower               | `Ctr` + `Alt` + *Pitch* |
| Lock Note Durations                 | `l`                     |
|                                     |                         |
| Create Grace Note                   | `/`                     |
| Create Slash Voice                  | `⇧` + `Alt` + `v`       |
| Create Voice                        | `⇧` + `v`               |
| Crescendo                           | `⇧` + `<`               |
| Diminuendo                          | `⇧` + `>`               |
| Move Music to Staff Above / Below   | `Alt` + `n`/`m`         |
| Next Voice                          | `v`                     |
| Rehearsal Mark                      | `⇧` + `a`               |
| Slur                                | `s`                     |


#### Note Articulation

| Action                           | Shortcut |
| -------------------------------- | -------- |
| Accent Symbol                    | `[`      |
| Marcato Symbol                   | `'`      |
| Set Staccato-Tenuto articulation | `~`      |
| Set Stress articulation          | `{`      |
| Staccatissimo Symbol             | `}`      |
| Staccato Symbol                  | `]`      |
| Tenuto Symbol                    | `#`      |
| Unstress Symbol                  | `@`      |


#### Barline  ( `⇧` + `b` )

| Action                | Shortcut                  |
| --------------------- | ------------------------- |
| Bidirectional Repeat  | `:|:` ⟺ `endstart`        |
| Create number of Bars | `+` + *number* ⟺ *number* |
| Dashed Barline        | `:` ⟺ `dash`              |
| Delete number of Bars | `-` + *number*            |
| Double Barline        | `||` ⟺ `double`           |
| End Repeat            | `:|` ⟺ `end`              |
| Final Barline         | `|]` ⟺ `fin`              |
| Normal Barline        | `|` ⟺ `single`            |
| Short Barline         | `,` ⟺ `short`             |
| Start Repeat          | `|:` ⟺ `start`            |
| Tick Barline          | `'` ⟺ `tick`              |


#### Clef  ( `⇧` + `c` )

| Action               | Shortcut         |
| -------------------- | ---------------- |
| 4-string Tablature   | `tab4`           |
| 6-string Tablature   | `tab6`           |
| Alto C               | `ca` ⟺ `alto`    |
| Baritone             | `baritone`       |
| Baritone bass        | `baritonebass`   |
| Bass F               | `f` ⟺ `bass`     |
| Bass F 15ba          | `f15ba` ⟺ `f15d` |
| Bass F 15va          | `f15va` ⟺ `15u`  |
| Bass F 8ba           | `f8ba` ⟺ `f8d`   |
| Invisible            | `invisible`      |
| Mezzo soprano        | `mezzo`          |
| Soprano G            | `soprano`        |
| Sub-Bass             | `subbass`        |
| Tenor C              | `ct` ⟺ `tenor`   |
| Treble G             | `g` ⟺ `treble`   |
| Treble G 15ba        | `g15ba` ⟺ `g15d` |
| Treble G 15va        | `g15va` ⟺ `g15u` |
| Treble G 8ba         | `g8ba` ⟺ `g8d`   |
| Treble G 8va         | `g8va` ⟺ `g8u`   |
| Unpitched Percussion | `perc`           |


#### Dynamic  ( `⇧` + `d` )

| Action      | Shortcut             |
| ----------- | -------------------- |
| Dynamics    | `pppppp` to `ffffff` |
| Crescendo   | `<` ⟺ `cresc.`       |
| Diminduendo | `>` ⟺ `dim.`         |
|             | `<>`                 |
|             | `><`                 |
|             | `piu mp`             |
| Sforzando   | `sfz`                |


#### Hold / Pause  ( `⇧` + `h` )

| Action              | Shortcut                |
| ------------------- | ----------------------- |
| Breathmark          | `,` ⟺ `breathmarkcomma` |
| Caesura             | `//` ⟺ `caesura`        |
| Curlew              | `curlew`                |
| Curved Caesura      | `caesuracurved`         |
| Fermata             | `fermata` ⟺ `fer`       |
| Long Fermata        | `longfermata`           |
| Long Henze Fermata  | `longhenzefermata`      |
| Salzedo Breathmark  | `breathmarksalzedo`     |
| Short Caesura       | `caesurashort`          |
| Short Fermata       | `shortfermata`          |
| Short Henze Fermata | `shorthenzefermata`     |
| Thick Caesura       | `caesurathick`          |
| Tick Breathmark     | `breathmarktick`        |
| Very Long Fermata   | `verylongfermata`       |
| Very Short Fermata  | `veryshortfermata`      |


#### Key Signature  ( `⇧` + `k` )

| Action                  | Shortcut              |
| ----------------------- | --------------------- |
| Major Keys              | `C` - `B` `C#` - `Bb` |
| Major Keys (number `$`) | `$s` ⟺ `$#`           |
| Minor Key               | `c` - `h` `c#` - `bb` |
| Minor Key (number `$`)  | `$f` ⟺ `$b`           |
| Open / Atonal           | `open` ⟺ `atonal`     |


#### Lyrics  ( `⇧` + `l` )

| Action                                  | Shortcut              |
| --------------------------------------- | --------------------- |
| Add Elision                             | `_`                   |
| Hard Space                              | `⇧` + `Alt` + `Space` |
| Hyphen in Word                          | `Alt` + `-`           |
| Switch From Lyric to Chorus/Translation | `Alt` + `↓`/`↑`       |
| Switch Vers                             | `↓`/`↑`               |


#### Ornament  ( `⇧` + `o` )

| Action                            | Shortcut   |
| --------------------------------- | ---------- |
| Arpeggio (down)                   | `arpdown`  |
| Arpeggio (up)                     | `arp`      |
| Bracket                           | `bracket`  |
| Glissando to Next Note (straight) | `gliss`    |
| Glissando to Next Note (wavy)     | `glisswav` |
| Inverted Mordent                  | `invmor`   |
| Inverted Turn                     | `invturn`  |
| Mordent                           | `mor`      |
| Trill                             | `tr`       |
| Turn                              | `turn`     |


#### Tempo  ( `⇧` + `t` )

| Action               | Shortcut          |
| -------------------- | ----------------- |
| Accelerando          | `accel`           |
| Ritenuto             | `rit`             |
| Tempo Name           | e.g. `largo`      |
| Tempo Name and Speed | e.g. `largo q=50` |
| Tempo Speed          | e.g. `q=50`       |


#### Chord  ( `⇧` + `q` )

| Action                                  | Shortcut          |
| --------------------------------------- | ----------------- |
| Move to next / previous Chord           | `⇧` + `←`/`→`     |
| Move to next Bar                        | `Tab`             |
| Move to next Beat                       | `Space`           |
| Move to previous Bar                    | `⇧` + `Tab`       |
| Move to previous Beat                   | `⇧` + `Space`     |
| Remove all enharmonic spelling override | `⇧` + `Alt` + `s` |
| Remove enharmonic spelling override     | `Alt` + `s`       |


#### Playing Technique  ( `⇧` + `p` )

| Action        | Shortcut   |
| ------------- | ---------- |
| End Pedal     | `*`        |
| End Sostenuto | `s*`       |
| End Unacorda  | `u*`       |
| Pedal         | `ped`      |
| Retake        | `^`        |
| Sostenuto     | `sost`     |
| Unacorda      | `unacorda` |


#### Repeats  ( `⇧` + `r` )

| Action                  | Shortcut        |
| ----------------------- | --------------- |
| Repeat Bars             | `%$,$`          |
| Repeat Bars (count `$`) | `%$`            |
| Slash Region            | `slash`         |
| Temolo Z                | `z`             |
| Tremolos                | `/` to `////`   |
| Tremolos between Notes  | `/2` to `////2` |
| Tremolos Clear          | `0`             |


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
| Multi-Dotted Note       | `Alt` + `.`  |


## Mixer

| Action                     | Shortcut          |
| -------------------------- | ----------------- |
| Deactivate All Mute States | `Alt` + `u`       |
| Deactivate All Solo States | `Alt` + `⇧` + `s` |
| Mixer Window               | `F3`              |


## Setup Mode

| Action                           | Shortcut  |
| -------------------------------- | --------- |
| Add Instrument to Player         | `⇧` + `i` |
| New Flow                         | `⇧` + `f` |
| New Layout (Custom Score Layout) | `⇧` + `l` |
| New Player                       | `⇧` + `p` |


## Play Mode

| Action                    | Shortcut        |
| ------------------------- | --------------- |
| Navigate                  | `Ctr` + `[`/`]` |
| Set Draw Tool             | `d`             |
| Set Erase Tool            | `e`             |
| Set Object Selection Tool | `s`             |
| Zoom In / Out             | `z`/`x`         |


## Engrave Mode

| Action                             | Shortcut                |
| ---------------------------------- | ----------------------- |
| Frame Break                        | `⇧` + `f`               |
| Navigate to next Frame             | `Tab`                   |
| Navigate to previous Frame         | `⇧` + `Tab`             |
| Nudge (a little) alternative Mode  | `Alt` + `h`/`j`/`k`/`l` |
| Nudge (add `Ctr` for a lot amount) | `Alt` + *Arrow*         |
| System Break                       | `⇧` + `s`               |


## Global

| Action                     | Shortcut                  |
| -------------------------- | ------------------------- |
| Dorico Help                | `F1`                      |
| Engrave Mode               | `Ctr` + `3`               |
| Goto Bar                   | `Ctr` + `g`               |
| Goto Bottom Pane           | `Alt` + `Enter`           |
| Goto Bottom Panel          | `Ctr` + `8`               |
| Goto Left Panel            | `Ctr` + `7`               |
| Goto Right Panel           | `Ctr` + `9`               |
| Goto Toolbar               | `Ctr` + `6`               |
| Goto Write Mode            | `Ctr` + `2`               |
| Mixer Window               | `F3`                      |
| Play Mode                  | `Ctr` + `4`               |
| Print Mode                 | `Ctr` + `5`               |
| Run Last Script            | `Alt` + `Ctr` + `⇧` + `r` |
| Setup Mode                 | `Ctr` + `1`               |
| Transport Window           | `F2`                      |
| View Full Screen           | `F11`                     |
|                            |                           |
| Counterpart Layout         | `w`                       |
| Hide All Panels            | `Ctr` + `0`               |
|                            |                           |
| Engraving Options          | `Ctr` + `⇧` + `e`         |
| Layout Options             | `Ctr` + `⇧` + `l`         |
| Playback Options           | `Ctr` + `⇧` + `p`         |
| Preferences                | `Ctr` + `,`               |
|                            |                           |
| Create Frame Break         | `Alt` + `Ctr` + `f`       |
| Create System Break        | `Alt` + `Ctr` + `s`       |
|                            |                           |
| Select None                | `Ctr` + `d`               |
| Toggle Hand / Marquee Tool | `h`                       |
|                            |                           |
| Custom Zoom                | `Alt` + `z`               |
| Start / Stop Playback      | `Space`                   |
| Zoom In / Out              | `Ctr` + `-`/`=`           |
| Zoom to Whole Page         | `Ctr` + `Alt` + `0`       |
|                            |                           |
| Close Project              | `Ctr` + `⇧` + `w`         |
| New                        | `Ctr` + `n`               |
| New Window                 | `Ctr` + `⇧` + `t`         |
| Open                       | `Ctr` + `o`               |
|                            |                           |
| Copy                       | `Ctr` + `c`               |
| Cut                        | `Ctr` + `x`               |
| Delete                     | `Delete`                  |
| Paste                      | `Ctr` + `v`               |
| Redo                       | `Ctr` + `y`               |
| Undo                       | `Ctr` + `z`               |


## Tokens

#### Project Tokens

| Fieldname         | Token                        |
| ----------------- | ---------------------------- |
| Arranger          | `{@projectarranger@}`        |
| Artist            | `{@projectartist@}`          |
| Composer          | `{@projectcomposer@}`        |
| Composer Dates    | `{@projectcomposerdates@}`   |
| Composition Year  | `{@projectcompositionyear@}` |
| Copyist           | `{@projectcopyist@}`         |
| Copyright         | `{@projectcopyright@}`       |
| Dediction         | `{@projectdedication@}`      |
| Editor            | `{@projecteditor@}`          |
| Lyricist          | `{@projectlyricist@}`        |
| Other Information | `{@projectotherinfo@}`       |
| Publisher         | `{@projectpublisher@}`       |
| Subtitle          | `{@projectsubtitle@}`        |
| Title             | `{@projecttitle@}`           |
| Work Number       | `{@projectworknumber@}`      |


#### Flow Tokens

| Fieldname           | Token                      |
| ------------------- | -------------------------- |
| Arranger            | `{@flow%arranger@}`        |
| Artist              | `{@flow%artist@}`          |
| Composer            | `{@flow%composer@}`        |
| Composer Dates      | `{@flow%composerdates@}`   |
| Composition Year    | `{@flow%compositionyear@}` |
| Copyist             | `{@flow%copyist@}`         |
| Copyright           | `{@flow%copyright@}`       |
| Dediction           | `{@flow%dedication@}`      |
| Editor              | `{@flow%editor@}`          |
| Flow Page Count     | `{@flowPageCount@}`        |
| Flow Page Number    | `{@flowPage@}`             |
| Flow `%` First Page | `{@flow%FirstPage@}`       |
| Lyricist            | `{@flow%lyricist@}`        |
| Other Information   | `{@flow%otherinfo@}`       |
| Publisher           | `{@flow%publisher@}`       |
| Subtitle            | `{@flow%subtitle@}`        |
| Title               | `{@flow%title@}`           |
| Work Number         | `{@flow%worknumber@}`      |

Note: `%` inbetween the tokens is a placeholder for flow-number (ex. `{@flow3title@}` is the title of the third flow). Also you can write `{@flowtitle@}`.


#### DateTime Tokens

Note: If you insert `project`, the tokens will display the DateTime at which the project was last saved.

| Fieldname        | Token                |
| ---------------- | -------------------- |
| Date             | `{@date@}`           |
| Year             | `{@dateyear@}`       |
| Year Short       | `{@dateyearshort@}`  |
| Month Name       | `{@datemonth@}`      |
| Month Short Name | `{@datemonthshort@}` |
| Month Number     | `{@datemonthnum@}`   |
| Day Name         | `{@dateday@}`        |
| Day Short Name   | `{@datedayshort@}`   |
| Day Number       | `{@datedaynum@}`     |
| Date (ISO8601)   | `{@dateymd@}`        |
| Month Day, Year  | `{@datemdy@}`        |
| Day Month Year   | `{@datedmy@}`        |
| Local Time       | `{@datetime@}`       |
| Time HHMM        | `{@datetimeHHMM@}`   |
| Time HHMMSS      | `{@datetimeHHMMSS@}` |
| Hour (24-hour)   | `{@datetimehour24@}` |
| Hour (12-hour)   | `{@datetimehour12@}` |
| Minute           | `{@datetimeminute@}` |
| Second           | `{@datetimesecond@}` |


#### Other Tokens

| Fieldname    | Token             |
| ------------ | ----------------- |
| Layout-name  | `{@layoutname@}`  |
| Page-number  | `{@page@}`        |
| Player-list  | `{@playerlist@}`  |
| Player-names | `{@playernames@}` |
| Layout Name  | `{@layoutname@}`  |
| Page Count   | `{@pageCount@}`   |