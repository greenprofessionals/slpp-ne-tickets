SLPP New England Tickets - GitHub Pages Repo

Repository name:
slpp-ne-tickets

Expected GitHub Pages base URL:
https://greenprofessionals.github.io/slpp-ne-tickets/

Files:
claim.html
v.html
Code.gs
config.html (optional admin configuration page)
images/
  ticket-single-template.png
  ticket-single-patron-template.png
  ticket-double-patron-template.png

IMPORTANT:
After creating the repo and enabling GitHub Pages, update your deployed Apps Script
with Code.gs from this bundle (or manually change only these two constants):

BASE_CLAIM_URL = 'https://greenprofessionals.github.io/slpp-ne-tickets/claim.html'
BASE_VOUCHER_URL = 'https://greenprofessionals.github.io/slpp-ne-tickets/v.html'

Then redeploy/update the Apps Script web app if necessary.

Tier mapping:
single  -> images/ticket-single-template.png
patron  -> images/ticket-single-patron-template.png
double  -> images/ticket-double-patron-template.png
