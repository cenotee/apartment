# Apartment Booking — Simple Static Page

This is a minimal booking page that embeds a Google Calendar and a Google Form.

Files added:

- `index.html` — The booking page with the calendar and form embeds.
- `styles.css` — Minimal responsive styling.

Open locally:

```zsh
cd /Users/jurajslota/Documents/littlebigappartment/apartment
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

Notes:

- The calendar iframe uses the public calendar URL you provided.
- The form iframe uses the form URL with `?embedded=true` to allow embedding.

Hero and photo gallery

- A hero background image was added to the top of the page (uses a public Unsplash photo hotlink).
- A responsive photo carousel with three apartment photos was added below the main content. The carousel has previous/next controls, small indicators, and autoplay.

If you prefer local images instead of hotlinks, place images in an `images/` folder and update the `src` attributes in `index.html`.
