# Ariel Learns: voice auditions

Each file reads the same six lines with a short pause between them:
"What color is it?" / "Blue! Great job!" / "How many? One! Two! Three!" / "A cow! Yay! That's right!" / "Oops! Try again!" / "Hooray! You did it! You are so smart!"

Rendered locally on the Mac mini (MLX, Apple Silicon), with no cloud TTS. Each line was rendered on its own, joined with 0.45 s of silence and loudness-normalized to about -16 LUFS (ffmpeg loudnorm). Every file was checked with Whisper large-v3-turbo, and all six lines come back word for word.

| # | Model | Voice (design prompt) | Settings | Measured pitch |
|---|---|---|---|---|
| 1 | Qwen3-TTS 12Hz 1.7B VoiceDesign (8-bit MLX) | "A bright, cheerful young American woman, like a preschool TV show host talking to a toddler. Big smile in her voice, excited, warm, bouncy and enthusiastic, clear slow-ish pronunciation, high energy." | seed 7, language english | ~340 Hz |
| 2 | Qwen3-TTS 12Hz 1.7B VoiceDesign (8-bit MLX) | "A playful, giggly young girl's voice, about ten years old, American accent, super excited and delighted, sing-song and expressive, cartoon character energy." | seed 7 (last line seed 23: seed 7 said "Jose" instead of "Hooray") | ~420 Hz |
| 3 | Qwen3-TTS 12Hz 1.7B VoiceDesign (8-bit MLX) | "A warm, upbeat young American man, friendly kids' TV presenter, cheerful and excited, smiling, energetic and encouraging, medium-high pitch." | seed 7 | ~310 Hz (higher than a typical man, so it may sound youthful) |
| 4 | VoxCPM2 (8-bit MLX) | "A bright, cheerful young woman, excited preschool teacher, smiling, warm and enthusiastic" | seed 7, 10 steps, cfg 2.0 | ~330 Hz |

Pick a number and the whole game can be re-voiced with that exact prompt and seed. With a reference clip, the voice stays identical across every line.
