# WM-Tippkarte

A small, German-language World Cup prediction card. Enter two teams, a score and an optional reason, then copy a link so a friend can see and edit the prediction. The preview updates immediately.

Open `index.html` locally or visit the published GitHub Pages site. No build, account, database, fixtures, odds, analytics or server state.

## Product choices

- German first, because the challenge names German-speaking fans as the primary audience.
- No fabricated match data or betting odds. The user enters the match and prediction.
- The optional reason makes a shared pick feel personal. It is encoded in the link, so the page explicitly says that anyone with the link can read it.
- All shared text is inserted with `textContent`; it cannot become HTML.

This is an independent concept made for the We The Flywheel application task, not an official Tipmaster product.
