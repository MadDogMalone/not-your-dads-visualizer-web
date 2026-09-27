# not-your-dads-visualizer-web
Windows 10/11 Chromium Visualizer

> 1. Click **Visualize system audio**.
> 2. In the popup pick the **Entire screen** tab and click your screen.
> 3. Turn on **Also share system audio** and click **Share**.
> 4. Play some music. Press **F** for fullscreen, **S** for settings, **H** for help.
>
> It only uses the sound. The screen picture is discarded immediately and nothing leaves your PC.

Tip: picking a single **Chrome tab** instead of the whole screen also works, and it visualizes just that tab's audio (e.g. a YouTube tab).

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
