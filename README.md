# Golden Hour Café: Welcome to my café

A single-file, fully responsive landing page for a café with three outlets in Singapore (Jurong, Orchard and Tampines). No build step and no dependencies: open `index.html` in a browser.

## Features

- **Cinematic hero:** three full-bleed slides with large gradient titles, a soft right-to-left misty wipe between slides, and auto-advance every 5 seconds. Clicking a round thumbnail on the right jumps to a slide.
- **Outlet search bar:** choose an outlet, a pick-up date, a pick-up time (slots follow each outlet's opening hours) and an order type (Pick up or Dine in).
- **Our Outlets:** three outlet cards. Clicking one flies the photo into an outlet page with the outlet manager, an About section, menu highlights, a rating row and an **Order ahead** card that carries over your search choices.
- **Other outlets:** the detail page links to the remaining outlets.
- **Responsive:** works on desktop and phone widths, with no sideways scrolling.
- **Custom cursor:** a soft grey dot that grows over clickable things (hidden on touch devices).

## Run it

Open `index.html` in any modern browser. It needs an internet connection for the web fonts and the photos.

### Publish with GitHub Pages (optional)

1. In the repo, go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
3. After a minute the site appears at `https://<your-username>.github.io/<repo-name>/`.

Note: Pages for private repositories needs a paid GitHub plan.

## Customise

Everything is inside `index.html`.

| What | Where |
| --- | --- |
| Outlet names, addresses, opening hours and manager names | the `OUTLETS` array near the top of the script (**these are placeholders, replace them with real details**) |
| Hero titles and captions | the `SL` array |
| Photos | the `PX(id, width)` helper builds Pexels image links from photo IDs; change the ids in `SL`, `TH`, `OUTLETS` and `INTERIORS`, or replace `PX` with your own image URLs |
| Menu highlights and prices | the `MENU` array |
| Colours | the CSS variables at the top of the `<style>` block |

## Credits

- Photos from [Pexels](https://www.pexels.com), used under the Pexels licence.
- Fonts: [Urbanist](https://fonts.google.com/specimen/Urbanist) and [Gilda Display](https://fonts.google.com/specimen/Gilda+Display) via Google Fonts.
- Avatar images in the detail page are generated placeholders from the original design.

The brand "Golden Hour Café", the outlet addresses and the people named on the page are invented for demonstration.
