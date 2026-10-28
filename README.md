# Sanctuary Sitting Room

Advocate Sitting Room for Oneness Wellness Sanctuary. Plain HTML, CSS, and JavaScript, served from this repository root. Advocate-only for now (`noindex`). This is the static replacement for the previously hosted advocate app. Nothing here depends on that host.

## Test URL

https://shifa-star.github.io/oneness-sitting-room/

Tracking links use `?ref=<Name>&via=person`. The advocate list is in [LINKS.md](LINKS.md).

Example: https://shifa-star.github.io/oneness-sitting-room/?ref=Rita&via=person

`ref`, `referrer`, or `from` names who sent the visitor. `via` or `how` records how they found the room (`person`, `message`, `calendar`, `search` or `looked`, `unsure`). Words stay on this device until **Send request**.

## Booking

The calendar stays the existing GoHighLevel booking link:

https://link.onenesswellnesslifestyles.com/widget/bookings/owlhcentersos

## Unknown paths

`404.html` sends any missing path back to this site root and keeps the query string, so `?ref=` and `via=` survive. On the test host that root is `/oneness-sitting-room/`. On the future custom domain it is `/`.

## DNS cutover (later)

Do not change DNS from this repository. Do not attach a custom domain until `app.onenesswellnesslifestyles.com` already points here.

Absolute share tags in `index.html` (`og:image`, `og:url`, `twitter:image`) use the test Pages URL `https://shifa-star.github.io/oneness-sitting-room/`. At cutover, change those to `https://app.onenesswellnesslifestyles.com/…` (for example `https://app.onenesswellnesslifestyles.com/og.jpg` and `https://app.onenesswellnesslifestyles.com/`). Styles, scripts, icons, and `manifest.webmanifest` stay relative.
