# Ariel's Phone (Rabbit R1 creation)

A toy cell phone for the Rabbit R1. Tap numbers on a colorful dial pad, press **Call**, hear it ring, and a friend answers and chats through the R1's AI and speaker like a real phone call. No real calls are ever placed.

- **Who she can call:** 22 people (Grandma, Grandpa, a teacher, doctor, firefighter, chef, pilot, astronaut, princess, pirate, Santa, Tooth Fairy, mermaid, robot and more) and 25 animals (bunny, puppy, kitty, dino, unicorn, lion, elephant, monkey, owl, frog, dragon, octopus and more).
- **Phone numbers:** people are 11, 12, 13… and animals are 51, 52, 53… (shown in the 👥 list). Any other number reaches a surprise friend, and the same number always gets the same friend.
- **How a call goes:** the friend talks, then the screen shows "🎤 Your turn!" for about 7 seconds while Ariel talks back. The friend reacts as if they heard her and keeps chatting. If the R1 lets the page use the microphone, the friend answers as soon as she stops talking (and uses her real words if speech recognition is available). Tapping the green bar or clicking the side button also means "done talking". After 16 turns the friend says goodbye.
- Emoji buttons (👋 😂 🎵 📖 ❤️ 🙈 🍪 😴) are optional quick replies.
- On the R1: side button opens the list, scroll wheel picks, side button calls.

## Install on the R1
1. Make sure the site is live at https://loci03.github.io/r1-toy-phone/
2. On the R1: open the creations card → create → "add via QR code".
3. Scan `install-qr.png`.

The QR holds the JSON in `creation.json`.

## Voice
The friend's lines are spoken by the app itself: first the device's system voice if it has one, then the built-in meSpeak voice (`mespeak.js`, a browser build of eSpeak, GPL, https://github.com/mikolalysenko/mespeak), and as a last resort an online voice. If you see 🔇 during a call, tap it to see a short sound check report.
