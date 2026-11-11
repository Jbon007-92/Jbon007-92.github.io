# Jbon007-92.github.io

Built from HomePower's `site/` folder (the HomePower repository is the source; edit there).

- `/` (`index.html`): HomePower's home page. Google's sign-in screen links to it (Google Auth
  Platform, Branding), and the app may be In production only with it and the privacy policy.
- `/privacy.html`: HomePower's privacy policy, also linked from Google's sign-in screen. No names,
  email addresses or street addresses.
- `/.well-known/appspecific/com.tesla.3p.public-key.pem`: the public key Tesla's Fleet API
  requires on the app's domain. Public by design; no private key exists anywhere.
- `/tesla/callback/`: where Tesla's sign-in returns; it hands the one-time code to the phone app.
- `.nojekyll`: lets GitHub Pages serve the `.well-known` folder.
- `robots.txt` and each page's `noindex`: kept out of search engines.
