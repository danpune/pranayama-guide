# pranayama-guide

A simple, immersive breathing guide to pranayama.

**Live:** https://danpune.github.io/pranayama-guide/

What's on the page:

- What pranayama is (*prana* + *ayama*) and why a few minutes a day helps
- A paced box-breathing circle to follow: in 4, hold 4, out 4, hold 4
- The four stages of a single breath: Puraka, Kumbhaka, Rechaka, Shunyaka
- Three short beginner videos on YouTube

## How it's built

One static `index.html`, served by GitHub Pages from `main`. No build step, no JavaScript, no framework. The breathing circle is a CSS animation on a 16-second loop, and for visitors who have reduced motion turned on it stops growing and shrinking while the stage labels keep the rhythm. Images are inlined; the only outside request is Google Fonts.

To preview locally:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Credits

Cycle stages adapted from "The Basics of the Pranayama Cycle" by Renato Yoga, licensed CC BY-SA 4.0 (Wikimedia Commons).

For general wellbeing only. This is not medical advice.
