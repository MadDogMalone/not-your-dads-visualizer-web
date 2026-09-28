# not-your-dads-visualizer-web
Windows 10/11 Chromium Visualizer

> 1. Click **Visualize system audio**.
> 2. In the popup pick the **Entire screen** tab and click your screen.
> 3. Turn on **Also share system audio** and click **Share**.
> 4. Play some music. Press **F** for fullscreen, **S** for settings, **H** for help.
>
> It only uses the sound. The screen picture is discarded immediately and nothing leaves your PC.

Tip: picking a single **Chrome tab** instead of the whole screen also works, and it visualizes just that tab's audio (e.g. a YouTube tab).

## What's in the settings panel

The panel has ten tabs:

- **Display:** beam, glow, trails, time window.
- **Shape:** circular wave, mirror.
- **Motion:** 3D rotation, spin.
- **Color:** presets, custom colour, colour cycle.
- **Audio:** source, gain / AGC, noise gate.
- **Filters:** DC block, high-pass, low-pass.
- **Effects:** feedback zoom, echo clones, kaleidoscope.
- **Geometry:** 3D companion shape, spectrum halo, spectrum terrain.
- **Scene:** starfield, beat sparks, reactive background, CRT / post effects.
- **React:** live bass / mid / treble / beat meters, plus sensitivity and beat-detection tuning.

Every effect starts **off**. Most effects have a "reacts to / pulses with" control that links them to loudness, bass, mids, treble or the beat pulse. The layer effects (shape, halo, terrain, stars, sparks) each have a "Gets trails / feedback" switch that decides whether they smear with the trails or stay crisp. A small dot on a tab means something on it differs from the default.

## Keys

| Key | Action |
|---|---|
| S | Settings |
| Z | Hide all UI |
| F / X | Fullscreen |
| C | Next colour preset |
| G | Grid |
| A | Change audio source |
| H / ? | Help |
| Right-click / double-click a slider | Reset it |

Settings are saved in each person's browser automatically.

## If something's wrong

- **"No sound was shared":** the "Also share system audio" switch was off. Try again and switch it on.
- **Nothing moves:** make sure something is actually playing. The Audio tab's input meter shows whether sound is arriving.
- **Low FPS on an older laptop:** go to Settings → Display → Resolution → **Half**. Or turn the glow off.
- **"8-bit mode" in the corner:** the graphics card doesn't support float buffers. It still works, but trails look slightly less smooth.
