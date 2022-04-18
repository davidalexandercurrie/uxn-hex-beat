# uxn-hex-beat

Commands

Rhythm
`r 80838980` // rhythm created with hex number where the bytes correspond to steps e.g. 4 to the floor = `r 80808080`

Pitch
`n[60 50 40 30]` // midi note value 60 = middle c

Instrument
`i 3` // 0-8 are different waveforms. 6 is set to a random memory address in the program... often quite noisey! 8 is a kick drum sample

Bit shift the rhythm
`f` will shift the rhythm and then add it on top of the original. Generally adds more notes

`s` toggles console visualizer

Tempo
`t 80` sets the number of frames per cycle. Defaults to 0xc0 (192 in Decimal)
