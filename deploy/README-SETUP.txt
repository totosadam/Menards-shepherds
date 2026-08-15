========================================================
  MENARDS LEGENDARY GERMAN SHEPHERDS
  Website + self-service editor
========================================================

WHAT'S IN THIS FOLDER
  index.html      -> the website
  content.json    -> ALL the editable content (puppies, dogs, photos, and every bit of text)
  admin/          -> the editor your client logs into
  netlify.toml    -> tells Netlify how to serve the site

WHAT CAN BE EDITED (no coding, no GitHub for your client)
  - Every litter and puppy: name, description, photo, and status (Available / Reserved / Sold).
    The colored badge and the call-to-action update automatically from the status.
  - Sires and dams (the parent dogs) and their photos.
  - The photo gallery.
  - The "Why Us" boxes, health points, "How it works" steps, and the go-home checklist.
  - ALL page text: announcement bar, hero headline + intro, every section heading and
    paragraph, pricing, the About story, the bottom banner, footer, phone and email.


========================================================
  STEP-BY-STEP SETUP  (about 15 minutes, one time)
========================================================
You already have a GitHub account — great. Your client will NOT need one.

--------------------------------------------------------
PART 1 — Put the site on GitHub
--------------------------------------------------------
1. Go to github.com and log in.
2. Click the "+" (top right) -> "New repository".
3. Repository name: menards-shepherds  (anything is fine). Leave it Public. Click "Create repository".
4. On the next page, click the link "uploading an existing file".
5. Open this folder on your computer, select EVERYTHING inside it
   (index.html, content.json, netlify.toml, AND the admin folder), and drag it into the browser.
   -> Tip: drag the admin FOLDER in too, so github keeps the admin/ folder.
6. Click "Commit changes" (green button).

--------------------------------------------------------
PART 2 — Connect the repo to Netlify
--------------------------------------------------------
7. Go to app.netlify.com and log in.
8. Click "Add new site" -> "Import an existing project" -> "Deploy with GitHub".
   (Authorize Netlify to access GitHub if it asks.)
9. Pick your "menards-shepherds" repository.
10. Leave Build command BLANK. Set Publish directory to a single dot:  .
11. Click "Deploy". Wait ~1 minute — your site is live on a temporary .netlify.app address.

  ** Moving your GoDaddy domain to this new site **
  If your domain was pointed at the OLD (drag-and-drop) site, point it at this one:
  Netlify -> your new site -> "Domain management" -> "Add a domain" -> type your domain ->
  follow the steps. Netlify shows the exact DNS records; you paste those into GoDaddy
  (GoDaddy -> your domain -> DNS). No new purchase needed.

--------------------------------------------------------
PART 3 — Turn on the login system
--------------------------------------------------------
12. In your Netlify site: go to the "Identity" tab -> click "Enable Identity".
13. Under Identity -> "Registration preferences" -> set to "Invite only" and Save.
14. Under Identity -> "Services" -> "Git Gateway" -> click "Enable Git Gateway".

--------------------------------------------------------
PART 4 — Invite your client
--------------------------------------------------------
15. Identity tab -> "Invite users" -> type her email -> Send.
16. She gets an email, clicks "Accept the invite", and sets her own password. Done.


========================================================
  SEND THIS TO YOUR CLIENT  (how she edits)
========================================================
  1. Go to:  https://YOURDOMAIN.com/admin/
  2. Log in with your email and the password you set.
  3. Click "Website Content" -> "Puppies, Dogs, Photos & Text".
  4. Edit anything:
       - Mark a puppy Available / Reserved / Sold.
       - Add or remove a litter or puppy; upload a new photo.
       - Open "Page Text & Contact Info" to change any wording, the phone, or the email.
  5. Click "Publish" (top of the page).
  6. The live website updates within a minute or two.


========================================================
  NOTES
========================================================
- Existing dog photos load from the original Squarespace links (they still work fine).
  New photos your client uploads through the editor are stored with the site.
- To change the phone number everywhere: edit BOTH "Phone — shown on page" and
  "Phone — for the click-to-call button" (that second one is the digits, like +14025102493).
- To change the actual DESIGN / layout (not the words), come back to me.
