# Stage Plot

An interactive 3D stage plot for bands, FOH engineers and monitor techs. Build the stage, place the band and their gear, and walk through it on a phone or a laptop.

**Live app:** https://waldenhollow.github.io/stage-plot/ (replace with your GitHub username once Pages is on)

## What it does

- **Band and backline:** musicians with instruments, amps, pedalboards, drum kits, keys, DIs and mics. Drag anything in the 3D view and turn it with the Turn bar.
- **Loose mics and DIs:** drop one in, drag it near a drum, amp or player and it snaps on with the right stand.
- **Inputs and monitors:** auto-numbered input list, wedge and IEM mixes (mono or stereo per musician), personal mixers, drum subs.
- **Mix gear:** FOH and monitor consoles, IEM rack, splitters, stage boxes, rack mixers and Wi-Fi routers, all movable.
- **Patch bay:** front panels laid out like the real units (XR18, X32 and others), with drag-to-patch XLR, Cat5 and USB cables. Devices can be removed from their headers.
- **Playback rigs:** laptop, iPad, phone or MP3 player, connected by USB, audio interface, stereo DI or Dante, with a step-by-step cable chain and named stems.
- **Lights and FX:** pars, movers, spark machines, fog, haze and amp banners.
- **Walkthrough:** orbit, top-down plot and walk mode with saved camera stops.

## Running it

It's a single file, `index.html`, with no build step. Open it in a browser, or serve the folder:

```bash
python3 -m http.server 8791
```

Then go to http://localhost:8791.

Plots save in the browser (localStorage) on whatever device you use. Use **Save & share** to download a plot file and open it on another device.

## Libraries

[three.js](https://threejs.org/) 0.147.0, loaded from the jsDelivr CDN. Fonts from Google Fonts.
