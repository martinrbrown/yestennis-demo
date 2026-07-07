# Yes!Tennis — Backlog

## In progress / next up
- [ ] Move FAQ accordion from separate page to Home page
- [ ] Add mock Login/Sign-in (registered members, booking tracking)
      — opportunity to add an inaccessible CAPTCHA as a new barrier
- [ ] Replace coloured-square placeholders on "Why Yes!Tennis" cards with icons
      (source: Noun Project)
- [ ] Generate AI hero image (mixed-ability doubles rally — no suitable
      stock image found)

## Later / lower priority
- [ ] Basic animated explainer video of Yes!Tennis fundamentals
      — keep deliberately simple, avoid this becoming a major production
- [ ] Wally scenario companion doc: "Inclusive Session Guidelines for
      Coaches" — thematically linked to Yes!Tennis, but NOT wired into
      the website or repo dependency

## Barrier tracking
Confirmed barriers (v1, home page):
1. Missing alt text — hero image
2. No real heading structure (div masquerading as H1)
3. Ambiguous link text — "Learn more" / "Click here" (x2 instances)
4. Low-contrast CTA button (~2.2:1)
5. Underline-only link, cue lost on hover/focus

Planned additions:
- Inaccessible CAPTCHA (Login/Sign-in page)

## Infrastructure notes
- Static HTML/CSS/JS, no framework — deliberate choice, see project notes
- Repo: github.com/martinrbrown/yestennis-demo
- Live: yestennis.org (Vercel, DNS via Cloudflare)
- Severity-tier toggle mechanic (obvious/partial/subtle): deferred until
  proven necessary in actual course use — do not build pre-emptively
