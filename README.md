# delnablastudio.com

The DEL Nabla Studio website: home (Word Gates), support and privacy policy.
Plain HTML and CSS, hosted free on GitHub Pages.

- `index.html`: home page
- `support.html`: support page (the App Store asks for a Support URL)
- `privacy.html`: privacy policy (both stores ask for a Privacy Policy URL)
- `assets/`: styles, the Word Gates icon, favicons
- `CNAME`: the custom domain for GitHub Pages
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## When the game ships

Download the official badges and save them in `assets/`:

- Google Play: https://play.google.com/intl/en_us/badges/ (save as `assets/google-play-badge.png`)
- App Store: https://developer.apple.com/app-store/marketing/guidelines/ (save as `assets/app-store-badge.svg`)

Then in `index.html`, delete the two "coming soon" lines and remove the
`<!--` and `-->` around the badge links (put the real App Store link in).
Both companies only allow their badges as links to the live listing, so
add them once the game is out.

## Before turning on ads

The privacy policy already covers optional AdMob rewarded ads. When ads are
added, the game also needs the consent prompt for the EU and UK and a way to
change that choice in settings, as the policy says. AdMob also asks for an
`app-ads.txt` file at the root of this site.
