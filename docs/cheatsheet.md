# Cheatsheet

## 1. Calculations

### How to calculate delay/reverb

1. Obtain your song's `bpm` and time signature.
2. Divide `60,000` by the `bpm` number.
3. Write down the result. This is the duration of the beat unit (quarter, eighth, etc.) used in the time signature expressed in `ms`.
4. **Multiply** or **divide** this result by two to obtain longer or shorter notes' lengths.

### Track gain

1. Tracks that are duplicatd are `6.02dB` louder.
2. Mono tracks panned hard L/R are `+3dB`.

### 2. Dynamic Range

### LRA

|LRA Value|Meaning|
|:---:|:---|
|`9+`|High Dynamic Range|
|`6-8`|Pretty High|
|`5-6`|Lower|

> There's really no “typical” LRA reading for various genres, aside from broad generalities: Classical music is most dynamic, so you can expect LRA readings of 9 or more. Country or jazz will have less dynamics; a reading of 6 to 8 is typical. Rock and EDM often hit around 5 to 6, and hip-hop, 5 or less

_- [https://blog.presonus.com/2021/03/05/mastering-lra-means/#:~:text=There's%20really%20no%20%E2%80%9Ctypical%E2%80%9D%20LRA,%2Dhop%2C%205%20or%20less.](https://blog.presonus.com/2021/03/05/mastering-lra-means/#:~:text=There's%20really%20no%20%E2%80%9Ctypical%E2%80%9D%20LRA,%2Dhop%2C%205%20or%20less.)_

## 3. DSP

### Sibilance and pops

Sibilance is usually `2-10k`-ish. Pops sub `500`. They're kinda opposites. Ish.
De-essers are targeting the tones that make those SSSsss sounds. Still unsure which algo is used for that.

### Mid/Side vs L/R Stereo

Mid/Side is the **SUM** of the ch. (Mid) and the diff of the ch. (Side)
L/R Stereo is mono of **ALL** **signals** sent to that channel.

Modulating the **_diff_** is the key to taming shit in the high end/resonant Hz.

### Fundamental Frequency

I've read conflicting info here but as I understand it,
The target tone produced by an impulse, which is 99% of the time the lowest note, however, some spl interactions in the room/instrument (we'll call it a resonance chamber) can produce new tones that are lower than the fundamental (undertones).
So if `C3` was the key I wanted to strike, the fundamental would be `258Hz`, but lower Hz _could_ be produced, circumstantially.
