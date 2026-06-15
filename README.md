# Dura Care — client preview

Password-protected preview of the **Dura Care** website, published via GitHub Pages.

🔒 `index.html` is encrypted with [StatiCrypt](https://github.com/robinmoisson/staticrypt)
(AES, client-side). Visitors must enter the shared password to view the page.

**Live preview:** https://cajsa-torahermansson-sudo.github.io/Dura-Care-alt.A/
_(password shared separately)_

---

The un-encrypted source is maintained privately and is intentionally **not**
included here — this repo is public (required for free GitHub Pages), so it only
contains the encrypted page, which is useless without the password.

To update the preview: re-export the self-contained HTML, re-encrypt it, and
replace `index.html`.
