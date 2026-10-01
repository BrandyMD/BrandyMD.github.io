# BrandyMD GitHub Pages — FINAL (GA4 native outbound click tracking)

Upload the CONTENTS of this ZIP to the root of your `BrandyMD.github.io` repository and commit to `main`.

Included:
- Existing site wording/design preserved
- 10 app cards on the homepage
- App titles link to their dedicated landing pages
- 10 dedicated app landing pages total
- 12 search-focused guide/article pages
- 23 searchable entry pages total
- Updated sitemap.xml
- robots.txt
- Google Analytics tag: G-9577M9WPJ9
- No custom click script

Why no custom click script:
GA4 Enhanced Measurement already records outbound links automatically as the built-in `click` event, including `link_domain` and `link_url`.

In GA4 create `google_play_click` from the built-in event using:
- event_name equals click
- link_domain equals play.google.com

Then mark `google_play_click` as a Key event.

`app-ads.txt` is NOT included, so your existing file remains untouched.
