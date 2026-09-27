# Image Swipe

A baby-proof picture swiper. Type a word (e.g. "airplane"), tap **Start**, hand over the phone.

- Swipe right to left to see the next picture. Every other touch does nothing.
- No buttons while swiping. Zoom, long-press, and the back button are blocked.
- Back to the search screen: close and reopen the app, or hold the top-left corner for 3 seconds.

Pictures come from [Pixabay](https://pixabay.com) (curated free photos, safe search on).

## Put it on your phone
1. Open the site in Safari (iPhone) or Chrome (Android).
2. Share → **Add to Home Screen**. Now it's one tap to open, fullscreen.

## Fully lock the phone (recommended)
A web page can't stop the home gesture. Use the phone's built-in lock:
- **iPhone:** Settings → Accessibility → Guided Access → On. In the app, triple-click the side button → Start.
- **Android:** Settings → Security → App pinning → On. Open recent apps, tap the app icon → Pin.

## Picture Tiles (tiles.html)
A second version on its own page: open `tiles.html`.

- The home screen shows 4 random things (dog, train, apple, …) as picture tiles.
- Tap a tile: only pictures of that thing appear, in random order.
- Tap anywhere (or swipe) for the next picture.
- Back to the tiles (with 4 new random ones): hold the top-left corner for 3 seconds.
- Uses the same Pixabay key as the main page.

## Wo ist das? (lernen.html)
A German word game: open `lernen.html`.

- Two pictures appear. A gentle German voice asks, e.g. **"Wo ist der Traktor?"**
- Right picture: a soft chime and praise, e.g. "Super! Das ist der Traktor." Then the next pair comes.
- Wrong picture: it wiggles and the voice says **"Probier's nochmal!"**, then asks again.
- No tap for a while: the question is asked again (at most twice).
- Back to the start screen: hold the top-left corner for 3 seconds.
- Uses the same Pixabay key as the other pages.

**Best voice:** the app uses the phone's built-in German voice. For a softer, more natural one:
- **iPhone:** Settings → Accessibility → Spoken Content → Voices → German → download **Anna (Enhanced)** or a Premium voice.
- **Android:** Settings → Text-to-speech → Google → install German voice data.
