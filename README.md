# prosody-syntax-interface-in-LFG

This perl script turns a speech signal (annotated with syllables in SAMPA) into a string which it parses with a computational LFG grammar. It analyses the speech signal in terms of pitch accents and prosodic phrase boundaries and uses this information to disambiguate the syntactically ambiguous structures. (More information will follow shortly)


Users need to install Praat, R, xfst, and XLE (all available for free)

Only one path has to be given: in the praat script in 1_extract_signal at the very bottom, the FULL path to the output file has to be provided. All other processes work locally through the 5 folders.

How to start in the shell: perl pipeline.pl

Select speech signal (when asked): the two exemplary speech signals are stored under 1_extract_signal/data/
--> select one of the .wav files

The script stops from time to time so the user has time to look through the data. Press "enter" to continue and type "exit" in XLE
