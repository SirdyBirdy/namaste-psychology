# Namaste Psychology — Booking Page

A single-page link for clients: intake form, payment QR, cancellation policy, and clinic location — no back-and-forth messages needed.

## Deploy on GitHub Pages

1. Create a new GitHub repo (e.g. `namaste-psychology-booking`) and push these files.
2. Go to **Settings → Pages**.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save. Your page will be live at `https://<your-username>.github.io/<repo-name>/` in a minute or two.

## Updating content

Everything lives in `index.html`:
- **Intake form link** — search for `forms.gle`
- **Payment QR** — replace `assets/payment-qr.png` with a new image (keep the same filename, or update the `src` in the Payment section)
- **Cancellation policy** — edit the `<ul class="policy-list">` items
- **Clinic location / maps link** — search for `maps.app.goo.gl`

No build step — it's plain HTML/CSS, so edits go live as soon as you push.
