# Cheatsheet



## 1. Calculations

### How to calculate delay/reverb

1. Obtain your song's `bpm` and time signature.
2. Divide `60,000` by the `bpm` number.
3. Write down the result. This is the duration of the beat unit (quarter, eighth, etc.) used in the time signature expressed in `ms`.
4. **Multiply** or **divide** this result by two to obtain longer or shorter notes' lengths.

### Track gain 

1. Tracks that are duplicatd are 6.02dB louder.
2. Mono tracks panned hard L/R are +3db.

## Dynamic Range

### LRA

|LRA Value|Meaning|
|:---:|:---|
|`9+`|High Dynamic Range| 
|`6-8`|Pretty High|
|`5-6`|Lower|

> There's really no “typical” LRA reading for various genres, aside from broad generalities: Classical music is most dynamic, so you can expect LRA readings of 9 or more. Country or jazz will have less dynamics; a reading of 6 to 8 is typical. Rock and EDM often hit around 5 to 6, and hip-hop, 5 or less

_- [https://blog.presonus.com/2021/03/05/mastering-lra-means/#:~:text=There's%20really%20no%20%E2%80%9Ctypical%E2%80%9D%20LRA,%2Dhop%2C%205%20or%20less.](https://blog.presonus.com/2021/03/05/mastering-lra-means/#:~:text=There's%20really%20no%20%E2%80%9Ctypical%E2%80%9D%20LRA,%2Dhop%2C%205%20or%20less.)_

## 2. Ableton

### Clip automation

Automation envelopes in the **Clip View** are dependent on the warping algo used (Beats, tones, texture, etc.)

### Grouping

Grouped tracks use a single CPU thread. Ungrouped tracks use a thread-per-track. 

### Unpack `.als` files to `.xml`

Haven't found an easy way to convert back and have it still be usable, but you can `git commit` the `.xml` file and diff the changes, if need be for whatever reason using the following:
`gzip -cd MySong.als > MySong.xml`


