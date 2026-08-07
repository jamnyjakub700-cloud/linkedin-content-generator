# LinkedIn Content Generator

A toolkit for branded LinkedIn visuals: carousel decks, OG images for meta tags,
and single post images.

## What it does

- **Carousels** as individual slides plus a combined PDF, in the portrait format
  LinkedIn actually rewards.
- **OG images** sized for link previews, so a shared post does not fall back to a
  cropped screenshot.
- **Post visuals** with an optional AI-generated background and a text hook.
- **One brand equals one config file**, so the same code serves several brands
  and a new brand is a config change rather than a fork.
- **Degrades gracefully.** When image generation is unavailable it falls back to a
  solid background instead of failing the run, because a plain correct image beats
  no image.

## Code

This repository holds the description. The implementation lives in a private
repository.

Happy to walk through how it is built: **[jakubjamny.com](https://jakubjamny.com)**

## License

MIT, see [LICENSE](LICENSE).
