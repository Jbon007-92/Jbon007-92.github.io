# Jbon007-92.github.io

Built from HomePower's `site/` folder (the HomePower repository is the source; edit there).

- `/.well-known/appspecific/com.tesla.3p.public-key.pem`: the public key Tesla's Fleet API
  requires on the app's domain. Public by design; no private key exists anywhere.
- `/tesla/callback/`: where Tesla's sign-in returns; it hands the one-time code to the phone app.
- `.nojekyll`: lets GitHub Pages serve the `.well-known` folder.
