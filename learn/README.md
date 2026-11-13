# Ariel Learns (Rabbit R1 creation)

A look-and-tap learning game for a toddler. A picture shows on top and three words sit below. Ask "what color is it?" and she taps the right word.

- **Three games** on the start screen: 🎨 Colors (10 colors), 🔢 Numbers (count 1 to 5 things, tap the digit), 🐶 Animals (17 animals).
- **Right answer:** the button turns green with sparkles, the picture hops, a happy tune plays and the voice says the word and cheers (animals then make their real sound, numbers count out loud while each thing bounces). A star flies up to the top.
- **Wrong answer:** the button wiggles and greys out, the color face goes "oh!", and the voice says "Try again!". She keeps going until she finds it.
- **5 stars** gives a trophy, confetti and a fanfare. Tap to play more.
- **Tap the picture** for a boing and to hear the question again (animals make their sound).
- 🏠 goes back to the start screen.
- On the R1: the scroll wheel picks a game on the start screen and the side button starts it; in a game the side button skips to a new question.

## Sounds
- **Voice:** every phrase is a pre-recorded clip in `audio/voice/`, made with the Kokoro-82M neural voice "Heart" (Apache-2.0), so it sounds natural and works the same on every device, even offline once loaded.
- **Animal sounds:** real recordings in `audio/animal/`, from the MIT-licensed skanas.lv project (github.com/ronv/skanas.lv). The bee buzz is synthesized.
- Clips play through Web Audio, the same way the game's beeps do.

## Install on the R1
1. On the R1: open the creations card → create → "add via QR code".
2. Scan `install-qr.png`.

The QR holds the JSON in `creation.json`. Live at https://loci03.github.io/r1-toy-phone/learn/
