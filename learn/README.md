# Ariel Learns (Rabbit R1 creation)

A look-and-tap learning game for a toddler. A picture shows on top and three words sit below. Ask "what color is it?" and she taps the right word.

- **Three games** on the start screen: 🎨 Colors (10 colors), 🔢 Numbers (count 1 to 5 things, tap the digit), 🐶 Animals (16 animals).
- **Right answer:** the button turns green with sparkles, the picture hops, a happy tune plays and the voice says the word (animals also make their sound, numbers count out loud while each thing bounces). A star flies up to the top.
- **Wrong answer:** the button wiggles and greys out, the color face goes "oh!", and the voice says "Try again!". She keeps going until she finds it.
- **5 stars** gives a trophy, confetti and a fanfare. Tap to play more.
- **Tap the picture** for a boing and to hear the question again (animals make their sound).
- 🏠 goes back to the start screen.
- On the R1: the scroll wheel picks a game on the start screen and the side button starts it; in a game the side button skips to a new question.

The voice uses the device's own voice if it has one, otherwise the built-in meSpeak voice shared with Ariel's Phone (`../mespeak.js`). Sounds are made by the page itself.

## Install on the R1
1. On the R1: open the creations card → create → "add via QR code".
2. Scan `install-qr.png`.

The QR holds the JSON in `creation.json`. Live at https://loci03.github.io/r1-toy-phone/learn/
