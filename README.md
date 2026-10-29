# Binaural Beats

A personal binaural beats generator. Open the GitHub Pages URL on your phone, no download or account needed. On iPhone, Share > Add to Home Screen puts it on your home screen like an app.

## How it works

Two tones are generated live in the browser: one for the left ear, one for the right ear, slightly different. Your brain perceives a third tone, the difference between them. Example: 200 Hz in the left ear and 210 Hz in the right ear gives a 10 Hz beat. That beat only exists in your head.

## Controls

- Presets: Deep Sleep (Delta 2 Hz), Meditation (Theta 6 Hz), Relaxation (Alpha 10 Hz), Focus (Beta 16 Hz), Peak Focus (Gamma 40 Hz), plus full custom control
- Base frequency slider (100-500 Hz, default 200)
- Beat frequency slider (0.5-50 Hz)
- Tone: sine, triangle, or square
- Ambient noise: off, white, pink, or brown, with its own level slider
- Volume slider
- Session timer: 10, 20, 30, 60 minutes, or no limit, with a gentle fade-out at the end

## Bands

- Delta (0.5-4 Hz): deep sleep, rest
- Theta (4-8 Hz): deep meditation, creativity, light sleep
- Alpha (8-13 Hz): relaxation, light meditation, stress reduction, pre-sleep
- Beta (13-30 Hz): focus, concentration, problem-solving
- Gamma (30+ Hz): peak focus, flow state

## Notes

- Headphones are required. Binaural beats only work when a different tone reaches each ear separately.
- Keep the volume low and comfortable. Try 10 to 30 minutes at first and see how you respond. Experiences vary, and it does not suit everyone.
- All sound is synthesized live in the browser. Nothing is downloaded, recorded, or sent anywhere.

## Run locally

Any static server works, for example: `python3 -m http.server` in this folder, then open http://localhost:8000.
