# Pulsarlube Privacy Policy

Static site for Pulsarlube's Privacy Policy and Account & Data Deletion
pages, published via GitHub Pages for use as the required URLs in the
Google Play Console ("Set privacy policy" and the Data Safety section's
"Delete data URL").

## Structure

```
index.html              language-detect redirect (en/ko/ja; zh falls back to en)
en/index.html            Privacy Policy — English
ko/index.html            Privacy Policy — Korean (한국어)
ja/index.html             Privacy Policy — Japanese (日本語)
zh/index.html             Privacy Policy — Chinese, NOT linked from navigation
                          (content not yet rebranded/reviewed for Pulsarlube -
                          kept on disk for a future pass, not deleted)
account-deletion/index.html   Account & Data Deletion — EN/KO/JA in one page
```

## Live URLs (once GitHub Pages is enabled for this repo)

- Privacy Policy (auto language-detect): `https://nilupa-illangarathna.github.io/Pulsarlube-privacy-policy/`
- Privacy Policy (English, direct): `https://nilupa-illangarathna.github.io/Pulsarlube-privacy-policy/en/`
- Account & Data Deletion: `https://nilupa-illangarathna.github.io/Pulsarlube-privacy-policy/account-deletion/`

Enable Pages under **Settings → Pages → Build and deployment → Source:
Deploy from a branch → `main` / `(root)`**. Confirm the exact URL casing
shown there once it's live — GitHub sometimes normalizes it differently
from this README's guess.

## Known placeholders — verify before relying on these in production

- **Contact email** (`ej.jang@pulsarlube.com`) — the clearest "primary point
  of contact" on the Pulsarlube side per internal project docs, but it's an
  individual's email, not a dedicated `support@`/`privacy@` inbox. Swap this
  for a generic inbox if/when one exists.
- **7 business day** turnaround for deletion requests — carried over from
  the template this was built from; adjust if the real internal SLA differs.
- **Chinese (`zh/`)** is intentionally unlinked and still carries placeholder
  (not Pulsarlube) branding — only English, Korean, and Japanese are live
  for now.
