# BelaLiveGranular

WIP on a 3/4 voice delay and pitch shifter based on Johannes Kriedler's live granular synthesis technique: http://www.pd-tutorial.com/english/ch03s07.html#id430983 (chapter 3.7.2.1)

Running this with the Katjav's vanilla implementation of freeverb: https://forum.pdpatchv'spo.info/topic/6247/freeverb-in-vanilla-pd 

There are two versions in progress:

The first is a 4 voice implementation, with each voice having producing it's own delay line for a total of 8 variable delays (4 left, 4 right).

The second is an attempt at a less CPU heavy 3 voice implementation with only 2 variable delays (1 left and 1 right), and each voice pitch shifting these.
