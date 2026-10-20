# Ivory & Gold Wedding Invitation

A responsive single-page HTML/CSS/JavaScript wedding invitation demo with a layered animated envelope, wax seal, invitation reveal, countdown, photo gallery, and demo RSVP.

## Run locally
Open `index.html` in a browser. No build step required. Google Fonts and sample Unsplash photographs need an internet connection.

## Publish with GitHub Pages
Repository → Settings → Pages → Build and deployment: Deploy from a branch → `main` → `/(root)` → Save. GitHub Pages may take a few minutes to deploy.

## Customize
- Search `Amelia`, `Oliver`, `June 20, 2027`, and `Villa Aurelia` in `index.html` to change demo copy.
- Update the countdown target in the JavaScript: `2027-06-20T16:00:00+02:00`.
- Replace sample Unsplash image URLs with your own properly licensed photographs.
- Adjust the colors in the CSS `:root` variables.

## Important limitations
- The RSVP is **demo-only** and is stored in the visitor's browser via localStorage. It does **not** email, collect, or transmit responses. Connect a form backend before using this for a real event.
- There is no background music in this first version. Music requires a licensed audio file and a user-initiated playback control.
- The envelope uses layered CSS 3D transforms rather than a physically simulated 3D mesh.
- Sample wedding details and names are fictional.
- Canva Free editable cards are a separate deliverable; HTML animation cannot be imported as editable Canva animation.
