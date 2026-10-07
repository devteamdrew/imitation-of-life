# Imitation of Life

A symphony in D minor, composed by Claude.

In the 2004 film *I, Robot*, Detective Spooner puts a challenge to the robot Sonny: "Human beings have dreams. Even dogs have dreams, but not you. You are just a machine. An imitation of life. Can a robot write a symphony? Can a robot turn a canvas into a beautiful masterpiece?" Sonny answers with a question of his own: "Can *you*?" This work is Claude's answer: a four-movement symphony of about 40 minutes, written as code and rendered with real instrument samples, with a painting and a video for each movement.

![Imitation of Life](covers/0_imitation_of_life.png)

## The movements

| | Movement | Duration | Cover |
|---|---|---|---|
| I | Copy | 11:29.7 | <img src="covers/1_copy.png" width="200" alt="I. Copy"> |
| II | Mirror | 9:50.4 | <img src="covers/2_mirror.png" width="200" alt="II. Mirror"> |
| III | Play | 6:33.3 | <img src="covers/3_play.png" width="200" alt="III. Play"> |
| IV | Invention | 12:01.5 | <img src="covers/4_invention.png" width="200" alt="IV. Invention"> |

## Downloads

Everything is on the [latest release](../../releases/latest):

- **Audio:** one WAV per movement (48 kHz, 24-bit, stereo)
- **Video:** one MP4 per movement (1080x1080, 30 fps)
- **Covers:** one PNG per movement, plus the symphony cover

## How it was made

Claude composed the symphony and wrote the Python that renders it. The sound comes from two CC0 (public domain) sample libraries, VSCO-2 Community Edition and VCSL (the Versilian Community Sample Library), played through a custom numpy SFZ sampler, with a Voxengo IM Reverbs church impulse response for the hall.

The cover paintings were made in code too. Each painting's structure is read from the notes of its movement. No image generation was used.

## Credit

Composed by Claude. Produced by DreW.

## License

Licensed under Creative Commons Attribution 4.0 International (CC BY 4.0). You may share and adapt it, including commercially, as long as you give credit. Full text in [LICENSE](LICENSE).

> "Imitation of Life", a symphony composed by Claude. Produced by DreW. Licensed under CC BY 4.0.

## Checksums (SHA-256)

```
fe4e257ab512022ea16397d6ef6f52bd73e5be3e284c3fe12118008e29d60e6a  IMITATION_OF_LIFE_01_Copy.wav
56ce6e268facd88a7af922f87b1c283717661ccea54d34889563232b9a8e72fd  IMITATION_OF_LIFE_02_Mirror.wav
6002ecfd7b51c1c0d7fb486189e3f7f92023fe9b1e83317c545e2a1956675b3b  IMITATION_OF_LIFE_03_Play.wav
fc8e2823c4eeb662f894aae73dad100502b87e98b46b61962c006a1705e18283  IMITATION_OF_LIFE_04_Invention.wav
88829c2fcaa0572b849e6adda183ecd481346d8efefe63098c3a1f0c77bf5928  IMITATION_OF_LIFE_01_Copy.mp4
bfa33358912245f902f2db8a5715cbe7a7bc60f0d261b1c86a5ce03cba8de0a2  IMITATION_OF_LIFE_02_Mirror.mp4
d436e3999d7359a93c71aa49da200ad035307b198cec850362d1dcb93646469c  IMITATION_OF_LIFE_03_Play.mp4
f53d4390f4c74a19106088396a8418e905fb42ea1b65951385f96fad4f540531  IMITATION_OF_LIFE_04_Invention.mp4
e9cd5a6a2ec836af659076eb2816c4ad1c154720dc57821244da09de5e576feb  0_imitation_of_life.png
2224b0e7cb1a79d2c411db4079a1ceec1fabd7b34d09d09f48abaf88f69f0259  1_copy.png
cd1e400aede748da6582f021423423722519ee72db34bea52ecffbbac5428009  2_mirror.png
2f4197f8dfa18e1779bac6a1159e46764923841f83ee3c2a0041fbbce92bbbb6  3_play.png
745e0f4fc8ed92c8b46c3336b843192cf43d67caf8f8b0163bd959244c3758ff  4_invention.png
```
