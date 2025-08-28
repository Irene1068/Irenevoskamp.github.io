# Irene's Portfolio — With Contact Form

## Set your real email (one place)
1. Open `index.html`.
2. Find `data-form-endpoint` on the `<form>` tag. Replace the value `https://formsubmit.co/YOUR_REAL_EMAIL` with your real email (e.g. `https://formsubmit.co/irene@example.com`).
3. Find the `<span id="emailObf" ...>` and replace `your.name` and `example.com` with your email's user and host (before/after the @).
4. Save. That's it — both the form and the mailto link will point to your real address.

## Publish
- GitHub Pages: upload all files to a repo named `YOURUSERNAME.github.io` and enable Pages.
- AWS Amplify or S3+CloudFront: same files work unmodified.

## Replace assets
- `assets/profile.jpg` — your headshot
- `assets/Resume.pdf` — your real resume
