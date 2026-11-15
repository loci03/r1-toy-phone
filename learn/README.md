# Ariel Learns (Rabbit R1 creation)

A look-and-tap learning game for a toddler. A picture shows on top and three words sit below. Ask "what color is it?" and she taps the right word.

- **Three games** on the start screen: 🎨 Colors (10 colors), 🔢 Numbers (count 1 to 5 things, tap the digit), 🐶 Animals (17 animals).
- **Right answer:** the button turns green with sparkles, the picture hops, a happy tune plays and the voice says the word and cheers (animals then make their real sound, numbers count out loud while each thing bounces). A star flies up to the top.
- **Wrong answer:** the button wiggles and greys out, the color face goes "oh!", and the voice says "Try again!". She keeps going until she finds it.
- **Numbers and Animals start easy and grow with her.** First 2 big choices, numbers 1-3 and 6 familiar animals (cow, dog, cat, duck, pig, sheep), and a win needs only 3 stars. After 2 wins: 3 choices, numbers to 4, 11 animals, 4 stars. After 5 wins: everything, 5 stars. Colors always plays at the full level.
- **Numbers counts smiley "color friends"** (the same kind of face as in Colors) most of the time, otherwise fun objects. Things sit on fixed dice-style spots so nothing gets cut off.
- **Gentle hints:** a wrong tap in Numbers counts the things out loud together; in Animals the animal makes its sound again. Then the right word glows, so she always finds it.
- **Stickers:** every win in Numbers or Animals gives a new sticker that goes on the shelf at the bottom of the start screen (🎁 on those buttons). Saved on the device.
- **5 stars** gives a trophy, confetti and a fanfare. Tap to play more.
- **Tap the picture** for a boing and to hear the question again (animals make their sound).
- 🏠 goes back to the start screen.
- On the R1: the scroll wheel picks a game on the start screen and the side button starts it; in a game the side button skips to a new question.

## Sounds
- **Voice:** every phrase is a pre-recorded clip in `audio/voice/`, made on our own Mac mini with Qwen3-TTS 1.7B VoiceDesign (8-bit MLX, Apache-2.0) from a written voice description: "A playful, giggly young girl's voice, about ten years old, American accent, super excited and delighted, sing-song and expressive, cartoon character energy." (seed 7; a few clips use another seed where seed 7 misspoke). It sounds excited and happy and works the same on every device, even offline once loaded.
- **Animal sounds:** real recordings in `audio/animal/`, from the MIT-licensed skanas.lv project (github.com/ronv/skanas.lv). The bee buzz is synthesized.
- Clips play through Web Audio, the same way the game's beeps do.

## Install on the R1
1. On the R1: open the creations card → create → "add via QR code".
2. Scan `install-qr.png`.

The QR holds the JSON in `creation.json`. Live at https://loci03.github.io/r1-toy-phone/learn/
