# Kingside site

Support page and privacy policy for the Kingside: Chess Clock iOS app, served with GitHub Pages at
https://sleepsheeps.github.io/kingside-site/

App Store Connect has them as the support URL and the privacy policy URL. `privacy.html` must
resolve, or App Store review stops on it.

The privacy policy describes what the app actually does: no data collected, no permissions, and
no network except the App Store for the optional tips. The Live Activity is updated on the device
(`pushType: nil`). If the app ever starts using the network, a permission, push or a third-party
SDK, update `privacy.html` (and the App Store privacy label) in the same change.

The support page quotes the app's own setting names (src/i18n/en.ts in the app repo); keep them in
step when those change.
