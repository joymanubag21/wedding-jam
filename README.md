# wedding-jam

A permanent address for a Jam that is not permanent.

`https://joymanubag21.github.io/wedding-jam/` is printed on the cards on the
tables, so it can never change. The Spotify Jam invite behind it changes every
time a new Jam is started — including on the morning of the wedding.

## Changing the Jam on the day

Open `index.html`. The first thing in it is:

```js
const SPOTIFY_JAM_URL = "https://open.spotify.com/socialsession/...";
```

Paste the new invite link between the quotes, commit, push. GitHub Pages
republishes in about a minute. The printed cards are untouched — they point
here, and here points at whatever that one line says.

Nothing else in the file needs editing, and the URL appears nowhere else.
