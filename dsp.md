# DSP effects and the why/how?

# Effects

## Gate

Gate lets signal of a certain dB through. (shout "let me in!" too softly and the guard doesnt open the gate. Yell super loud, and they do.). Dude in Act V intro stopping Baal was "the Gate".
If you dont shout loud enough, you still cant come in, even though the gates open. 

All the mic hiss, noise floor, and other shit has to stay outside. 

## Compressor

The too-drunk-guy-at-the-party. "Bro, simmer, you're too much right now."

## Glue Compressor

"Now kiss..." but for like, multiple track channels.

## Limiter

The bouncer. The compressor didn't catch you, so now I'm gonna MAKE you settle down. 

## EQ

The hype-man, esentially. Also like a conductor. You turn down, you turn up. It's all good. 

## Multiband Dynamics

Splits the signal into 3 bands to deal with. Each signal band can stand on its own. Like a filter splitter. The gym teacher who splits you into groups. 

## Noise Filter

Can be used as like a firewall to phase high-end bullshit. The higher the freq. the more chance of collision, so if you over-populate that range, you can tame some hard to catch rogue waves.

## Delay

TODO: This section needs some love. 

I kinda treat the delay as a signal repeater. All the coloring is delayed and sent on the same channels as the o.g. signal. It's beneficial cause it adds depth without adding additional coloration. The VHS cover of that Michael Keaton Multiplicity movie.

## Verb

Convo verb: Concreate, real space. (Think like, a big ol' venue)
Regular verb: Abstract space reflections. (Think like, a satin water wave in a dream or something)

## Echo

Echo is fucking cool. The source signal is concentrated, so the waves amplify each other (in phase). The environment is a conical shape or whatever that prevents phase cancellation, unlike verb. 
It's kinda like if someone shouted from a moving car "Hey your significant other is HHOOOOOTtttttt...." and the car's gone so we cant do anything about it (like shout back). If we all were in the same room, we could fight it out potentially (aka phase cancellation). 

I thought it's cool cones/bevels cause waves to reflect at diff angles. 

## Saturation

Adds harmonics.

## Overdrive

Overdrive's add harmonics depending on the underlying DSP algo. The clipping adds harmonics. This is (I think) akin to a brickwall EQ (around each clipping harm) where there's distortion at unity. _I THINK_.
Hard clip makes tried-and-true square waves from sine. 
Soft clip adds lerp between to soften the slope of the square clip. This modulates the tonality differently than a hard clip. 


## Mid/Side vs L/R Stereo

Mid/Side is the **SUM** of the ch. (Mid) and the diff of the ch. (Side)
L/R Stereo is mono of **ALL** **signals** sent to that channel. 

Modulating the DIFF is the key to taming shit in the high end/resonant hz.


# Other Funky things

## Sibilance and pops

Sibilance usually 2-10k ish. Pops sub 500. They're kinda opposites. Ish. 
De-essers are targeting the tones that make those SSSsss sounds. Still unsure which algo is used for that. 



