# tree-cutting-

Premium landing page demo for a tree service, built as a single static page under the placeholder brand **Heartwood Tree Co.**

Open `index.html` in a browser, or serve the folder with any static host (GitHub Pages, Netlify, Vercel). No build step and no dependencies apart from Google Fonts.

## What's on the page

- 24/7 storm line in the top strip, plus a sticky header with a phone link and a free-estimate button
- Hero with a field-note card and trust signals (rating, insurance, fixed quotes)
- Credentials strip: ISA, TRAQ, ANSI A300 and Z133, liability and workers' comp
- Services: removal, pruning, crane work and storm response, with "from" prices
- Four-step process beside a sample tree risk assessment
- Recent-work gallery and reviews
- Ballpark estimator (service, height, access, stump) linked to a quote form with inline validation
- Storm section with a service-area ring diagram, an FAQ and a footer

## Customizing

- **Brand, phone, email, hours:** search `index.html` for `Heartwood`, `555`, `heartwoodtree.example` and `Mon–Fri`.
- **Colors and fonts:** every color and typeface is a token in the `:root` block at the top of the `<style>`.
- **Estimator prices:** the `RANGES`, `ACCESS` and `STUMP` tables in the script at the bottom of the page.
- **Quote form:** it validates and then shows a confirmation, but sends nothing. Point it at your backend, or at a form service such as Formspree or Netlify Forms, inside the `submit` handler.
- **Sample content:** reviews, ratings, prices and job figures are placeholders. Replace them with real ones before going live.

## Credits

Photos from [Unsplash](https://unsplash.com) (Unsplash License) by Zack Masters, Dmytro Glazunov, Paula Morin, Patti Black, Michael Wilson and Richard Burlton.
Type: Cormorant Garamond, Jost and IBM Plex Mono from Google Fonts.
