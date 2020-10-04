# Input
This file contains notes on different input methods for different types of
data.

 - Text (Both Plain and Formatted, includes spreadsheet, number, date/time)
 - Music (Score)
 - Math (Expression)
 - Audio (Samples)
 - Video (Tracks)
 - Graphic (Both 2D/3D, Still and Animated, Vector and Raster)

## Reserved
These are the shortcuts that can't be used in internal input fields, because
they apply to the whole program.

 - `Ctr`+`q`: Close All Tabs
 - `Alt`+`q`: Internal Close All Tabs (App within app)
 - `Ctr`+`w`: Close One Tab
 - `Alt`+`w`: Internal Close One Tab (App within app)
 - `Ctr`+`e`: Move Tab Left
 - `Alt`+`e`: Internal Move Tab Left (App Within app)
 - `Ctr`+`r`: Move Tab Right
 - `Alt`+`r`: Internal Move Tab Right (App Within App)
 - `Ctr`+`t`: Open New Tab
 - `Alt`+`t`: Internal Open New Tab (App Within App)
 - `Ctr`+`s`: Share
 - `Alt`+`s`: Save A Copy
 - `Ctr`+`o`: Open
 - `Alt`+`o`: Open Recent
 - `Enter`/`Tab`: Next Input Field
 - `Shift`+`Tab`/`Shift`+`Enter`/`CapsLk`: Previous Input Field

## Text
 - `Escape`: Leave Insert Mode (Same as while holding `Ctr`, `Shift` for `Alt`).
 - `a`-`z`,`A`-`Z`,`0`-`9`,symbols: Insert grapheme
 - `Enter`: Insert newline / Next Row
 - `Tab`: Indent line, autocomplete / Next Column
 - `Shift`+`Tab`: Dedent line / Previous Column
 - `Backspace`: Remove previous grapheme
 - `Delete`: Remove next grapheme
 - `Insert`: Quick Clipboard
 - `Shift`+`Insert`: Quick Clipboard Replace
 - `Ctr`+`Insert`: Emoji
 - `Alt`+`Insert`: Compose
 - `Home`: Start of line
 - `End`: End of line
 - `CapsLk`: Previous Row
 - `Ctr`+`a`: Select all (Whole Document)
 - `Alt`+`a`: Select line
 - `Ctr`+`b`: Bold
 - `Ctr`+`d`: Delete line
 - `Alt`+`d`: Duplicate line
 - `Ctr`+`f`: Find (And Replace)
 - `Ctr`+`g`: Goto Line Number
 - `Ctr`+`i`: Italic
 - `Ctr`+`u`: Underline
 - `Ctr`+`y`/`Alt`+`z`: Redo
 - `Ctr`+`z`: Undo
 - `Alt`+`ArrowLeft`: Swap Word or Selection Left
 - `Alt`+`ArrowRight`: Swap Word or Selection Right

## Music
 - `0`: Set Duration To 128th Note
 - `)`: Tie
 - `1`: Set Duration To 64th Note
 - `!`: Stacatissimo
 - `2`: Set Duration To 32nd Note
 - `@`: Toggle Flat (Before Inserting Note)
 - `3`: Set Duration To 16th Note
 - `#`: Toggle Sharp (Before Inserting Note)
 - `4`: Set Duration To 8th Note
 - `$`: Toggle Alternate Note Spelling
 - `5`: Set Duration To Quarter Note
 - `%`: Measure Repeat
 - `6`: Set Duration TO Half Note
 - `^`: Marcato
 - `7`: Set Duration To Whole Note
 - `&`: Accent
 - `8`: Set Duration To Breve (Double Whole)
 - `*`: Staccato
 - `9`: Set Duration To Longa (Quadruple Whole)
 - `(`: Slur
 - `-`: Glissando
 - `_`: Tenuto
 - `=`: Open Mute
 - `+`: Close Mute
 - `a`: Insert Note, Pitch A Down (Flat, Sharp or Natural Depending on Key)
 - `A`: Insert Note, Pitch A Up (Flat, Sharp or Natural Depending on Key)
 - `b`: Insert Note, Pitch B Down (Flat, Sharp or Natural Depending on Key)
 - `B`: Insert Note, Pitch B Up (Flat, Sharp or Natural Depending on Key)
 - `c`: Insert Note, Pitch C Down (Flat, Sharp or Natural Depending on Key)
 - `C`: Insert Note, Pitch C Up (Flat, Sharp or Natural Depending on Key)
 - `d`: Insert Note, Pitch D Down (Flat, Sharp or Natural Depending on Key)
 - `D`: Insert Note, Pitch D Up (Flat, Sharp or Natural Depending on Key)
 - `e`: Insert Note, Pitch E Down (Flat, Sharp or Natural Depending on Key)
 - `E`: Insert Note, Pitch E Up (Flat, Sharp or Natural Depending on Key)
 - `f`: Insert Note, Pitch F Down (Flat, Sharp or Natural Depending on Key)
 - `F`: Insert Note, Pitch F Up (Flat, Sharp or Natural Depending on Key)
 - `g`: Insert Note, Pitch G Down (Flat, Sharp or Natural Depending on Key)
 - `G`: Insert Note, Pitch G Up (Flat, Sharp or Natural Depending on Key)
 - `h`: Note Left
 - `H`: Select Left
 - `i`: Transpose By Arbitrary Interval Down
 - `I`: Transpose By Arbitrary Interval Up
 - `j`: Step Down (Within Key)
 - `J`: Select Down
 - `k`: Step Up (Within Key)
 - `K`: Select Up
 - `l`: Note Right
 - `L`: Select Right
 - `m`: Insert Turn
 - `M`: Insert Inverted Turn
 - `n`: Skip Rests To Next Note
 - `N`: Skip Rests To Note Backwards
 - `o`: Octave Down
 - `O`: Octave Up
 - `p`: Down Arpeggio
 - `P`: Up Arpeggio
 - `q`: Quarter-Tone Down
 - `Q`: Quarter-Tone Up
 - `r`: Insert Rest
 - `R`: Add Rehearsal Marker, Repeat or Jump
 - `s`: Change Key Signature
 - `S`: Change Time Signature
 - `t`: Text: Tempo (Type a Number), Mute, Arco, etc. 
 - `T`: Add Lyrics
 - `u`: Tuplet 
 - `U`: Unstress 
 - `v`: Standard Vibrato
 - `V`: Vibrato Shape
 - `w`: Three-Quarter-Tone Down
 - `W`: Three-Quarter-Tone Up
 - `x`: Insert Fingering/Position Marking
 - `X`: Toggle Double Sharp 
 - `y`: Insert Dynamic
 - `Y`: Toggle Double Flat
 - `z`: Buzz Roll
 - `Z`: Change Clef
 - `<`: Crescendo
 - `>`: Decrescendo
 - `,`: Remove Dot
 - `.`: Add Dot
 - `/`: Tremolo
 - `?`: Fermata
 - `\`: Pedal Angled Hook Start/End
 - `|`: Pedal Straight Hook Start/End
 - `'`: Breath Mark
 - `"`: Caesura
 - `;`: Insert Grace Note Before
 - `:`: Insert Grace Note After
 - `~`: Insert Ornament (Turn, Inverted Turn, Trill, etc.)
 - `[`: Repeat Open
 - `]`: Repeat Close
 - `{`: Additional Ending Open
 - `}`: Additional Ending Close
 - `Backtick`: Stress
 - `Space`: Play/Pause 
 - `Enter`: Next Stave
 - `Tab`: Next Measure
 - `Shift`+`Tab`: Previous Measure
 - `CapsLk`/`Shift`+`Enter`: Previous Stave
 - `Insert`: Quick Clipboard
 - `Shift`+`Insert`: Quick Clipboard Replace
 - `ArrowUp`: Step Up (Within Key)
 - `ArrowDown`: Step Down (Within Key)
 - `ArrowLeft`: Note Left
 - `ArrowRight`: Note Right
 - `PageUp`: Previous Rehearsal Marker
 - `PageDown`: Next Rehearsal Marker
 - `Home`: Start of Stave
 - `End`: End of Stave
 - `Ctr`+`a`: Select All (Whole Movement)
 - `Alt`+`a`: Select Rehearsal Section (All Shown Staves)
 - `Ctr`+`d`: Delete Measure All Staves
 - `Alt`+`d`: Duplicate Measure All Staves
 - `Ctr`+`f`: Find Notes (And Replace)
 - `Alt`+`f`: Find Lyrics (And Replace)
 - `Ctr`+`g`: Go to Measure Number
 - `Ctr`+`y`/`Alt`+`z`: Redo
 - `Ctr`+`z`: Undo
 - `Alt`+`ArrowLeft`: Swap Note or Selection Left
 - `Alt`+`ArrowRight`: Swap Note or Selection Right

# Math & Logic Expressions
 - `v`: Logical OR Symbol
 - `^`: Logical AND Symbol
 - `~`/`!`: Logical NOT Symbol
 - `+`: +
 - `-`: -
 - `*`: ×
 - `/`: ÷
 - `.`: Decimal Point
 - `0`-`9`: Number
 - `b`: Base
 - `m`: µ
 - `Alt`+`ArrowLeft`: Swap operand left
 - `Alt`+`ArrowRight`: Swap operand right

# Audio Buffer
 - 

# Video Buffer
 - 

# Graphic
 - 