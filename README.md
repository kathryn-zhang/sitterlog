# SitterLog

The public pages for the SitterLog iOS app, served by GitHub Pages:

- Privacy policy — https://kathryn-zhang.github.io/sitterlog/privacy/
- Support — https://kathryn-zhang.github.io/sitterlog/support/
- Home and About — https://kathryn-zhang.github.io/sitterlog/ and `/about/`

The app links to the privacy policy from Settings, so keep that path stable.
The app's source lives in a separate, private repository.

## Before the home page goes live (after 1.0 is on the App Store)

`index.html` holds two placeholders, `APP_STORE_URL` (the badge link) and `APP_ID` (the Smart
App Banner). Fill both from
`https://itunes.apple.com/lookup?bundleId=com.kathryn.SitterAssistant&country=us`, which returns
`trackViewUrl` and `trackId` once the app is live, and check neither word remains before merging.

- The badge is Apple's official artwork (`images/app-store-badge.svg`, from Apple's marketing
  toolbox). Don't recolor or redraw it.
- Screenshots in `images/` are the App Store captures (fictional records), resized to 660 px.
  Re-export them when the app's screens change visibly.
- Don't name booking platforms beyond what a feature factually does, and no platform logos.
