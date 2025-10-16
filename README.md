
this repo demonstrates how it is used to generate phoneme timings.

it supports two modes which we call _text based_ and _textless_.

in the _text based_ mode, the program is given an audio file and a text transcript
of the audio file and trys to generate phoneme and word timings **(alignments)**.

in the _textless_ mode, the program is given only the audio file. It
will use ASR to generate word and phoneme timings. 

the output is printed to the console. 
