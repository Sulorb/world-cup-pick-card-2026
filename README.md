# WM-Tippkarte

A small, German-language World Cup prediction card. Enter two teams, a score and an optional reason, then copy a link so a friend can see and edit the prediction. The preview updates immediately.

[Try the live page](https://sulorb.github.io/world-cup-pick-card-2026/) or open `index.html` locally. No build, account, database, fixtures, odds, analytics or server state.

## Product choices

- German first, because the challenge names German-speaking fans as the primary audience.
- No fabricated match data or betting odds. The user enters the match and prediction.
- The optional reason makes a shared pick feel personal. It is encoded in the link, so the page explicitly says that anyone with the link can read it.
- All shared text is inserted with `textContent`; it cannot become HTML.

## Quick check

Enter two teams and a score, then copy the challenge link. Opening that link restores the card and leaves it editable. Clear either score field and the page rejects the incomplete prediction instead of treating it as zero.

This is an independent concept made for the We The Flywheel application task, not an official Tipmaster product.
