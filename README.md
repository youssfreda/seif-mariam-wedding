# Seif & Mariam invitation

## Turn on RSVP collection
1. Create a form in https://app.web3forms.com using the recipient email you want for RSVP notifications.
2. Copy the form Access Key into web3formsAccessKey in config.js.
3. Set the website URL to your final GitHub Pages URL when available.
4. Test an acceptance and a decline from the hosted invitation and confirm both emails arrive.

Guests enter only full name, attendance and total guests including themselves. Declines have zero guests. Guest email addresses are not requested. Repeat submissions are separate: review repeated names before counting guests. Responses go to the email attached to your Web3Forms form, not a public guest list. The page only confirms success after Web3Forms accepts the request. Until an access key is supplied, no RSVP is sent.

## Host on GitHub Pages
1. Create a repository in your personal GitHub account, for example seif-mariam-wedding. Use a public repository if using GitHub Free. Its code and embedded photos will be publicly accessible.
2. Upload index.html, config.js, wedding.ics and .nojekyll to the repository root. No build or installation is needed. The photos and music are embedded in index.html.
3. Open repository Settings → Pages → Build and deployment → Deploy from a branch.
4. Select main and / (root), then Save.
5. Wait for deployment and open the URL shown under Pages, typically https://YOUR-USERNAME.github.io/seif-mariam-wedding/ .
6. Share that URL after testing the RSVP form on your phone.

## Design and details
The envelope opening is retained, followed by the restored open burgundy envelope with photo and date cards, cream heart and seal. The invitation panel now uses the exact supplied childhood-photo poster, framed in cream like the screenshots. Its English names, calendar and venue are already part of the photo. An Arabic invitation underneath includes the names, Thursday 3 December 2026 at 8 PM, and Jan Hall, Al-Waha Club, Al Balajat Road. Confirm these details before sharing. The burgundy confirmation button opens the bilingual RSVP form, followed by the countdown. The time remains UTC+02:00 as in the original.

For a quick local preview, open Seif-Mariam-Invitation.html. For GitHub upload use index.html, config.js, wedding.ics and .nojekyll. Configure config.js for the hosted site; the standalone preview uses the configuration as it was when packaged.

This package has not been published, and RSVP collection still needs your Web3Forms Access Key. Browser rendering and real delivery need verification after deployment.
