# Murry's Portfolio — Render update

## Upload these files

Upload `index.html` AND the complete `assets` folder from the site package into the top level of `MichaeljayMMurry/murrys-portfolio` on GitHub. Keep the folder named `assets`; do not flatten its contents into the repository root.

Use GitHub's **Add file → Upload files**, drag in `index.html` and the `assets` folder, then commit to `main`. Render can keep serving the previous deployment while it publishes the new commit.

The Render settings stay the same:

- Root Directory: blank
- Build Command: `echo "No build needed"`
- Publish Directory: `.`

This redesign uses external image files for faster loading and for social link previews. Uploading only `index.html` is no longer sufficient.

## Activate the contact inbox once

1. After the update is live, open `https://murrys-portfolio.onrender.com/` and submit your own test message from the contact form.
2. Open `murrymikel9990@gmail.com` and look for the FormSubmit activation email. Check Spam if needed.
3. Click the confirmation link to activate the inbox.
4. Submit a second test message and confirm that it arrives.

Visitors do not need a Google account or sign-in. The form uses FormSubmit to deliver messages to the existing Gmail inbox. No Gmail password, API key, or private credential is included in the website.

The browser checks simulated success, failure, activation-needed, invalid-input, and network-error responses. No real messages were sent during development. Inbox delivery has not been verified because activation belongs to the email owner.

## Refresh the shared-link picture

The share card shows Murry's full face and uses:

`https://murrys-portfolio.onrender.com/assets/murry-share-v2.jpg`

Once the update is live, confirm that this image URL opens. If Messenger or Facebook keeps showing an old card, open https://developers.facebook.com/tools/debug/ and request **Scrape Again** for the portfolio URL. The social platform controls preview caching.

## Included changes

- Dark mode on every initial load, with a manual light-mode switch.
- Full-name header, a large MURRY hero title, larger unnumbered section headings, and mobile navigation that fit narrow screens.
- Cinematic charcoal, steel, and red design with original misty landscape art.
- A clear face-focused social preview and face favicon.
- An on-page contact form and preserved social/phone links.
- Original projects, certificates, setup, education, and photos preserved.

## References

- Form submission and activation: https://formsubmit.co/ and https://formsubmit.co/help
- FormSubmit AJAX: https://formsubmit.co/ajax-documentation
- Social metadata: https://ogp.me/
- Render static hosting: https://render.com/docs/static-sites

## Publication status

This package was prepared and tested locally. It was not uploaded to GitHub or deployed to Render by the assistant. Computer Use stopped because it could not determine the current browser URL with enough confidence. The current live site remains unchanged until this package is committed and deployed.
