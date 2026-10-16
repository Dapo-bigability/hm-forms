# Healthy Minds forms

Hosts `hm-forms.js`, the referral and class registration forms shown on hmllc.org.

Served by GitHub Pages at `https://dapo-bigability.github.io/hm-forms/hm-forms.js`.

This file contains only the form itself. It holds no client data and no passwords. Submissions go straight from the visitor's browser to Healthy Minds' Google Workspace.

Use `<div data-hm-form="chooser"></div>` on the Make a Referral page to show all forms as cards (links like `#prp-adult` open one directly), or `outpatient`, `prp-adult`, `prp-minor`, `positive-parenting` for a single form.

To update the forms, replace `hm-forms.js` with the new build and commit. The website picks it up within about 10 minutes.
