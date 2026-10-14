# Read Text Aloud — pages

Welcome and uninstall pages for the Read Text Aloud Chrome extension, served via GitHub Pages.

- `/welcome/` — opens once after installation
- `/uninstall/` — feedback form, opens when the extension is removed
- the privacy policy lives in a separate repo: `read-text-aloud-privacy`

The repository must stay public: GitHub Pages does not serve private repos on the free plan.

`welcome/step-1-2-pin.png` and `welcome/step-3-4-reading.png` are drawn in HTML/CSS, not screenshots:
a Chrome toolbar, an article and the extension's popup and player (version 1.0.0).

`uninstall/index.html` posts to a Google Form. Fill in `FORM_ID`, `ENTRY_REASON` and `ENTRY_DETAILS`
at the bottom of the file from the form's pre-filled link. Until then the page shows the thank-you
state and sends nothing. The "Get Read Text Aloud back" link points to a Chrome Web Store search until
the listing has its own address.
