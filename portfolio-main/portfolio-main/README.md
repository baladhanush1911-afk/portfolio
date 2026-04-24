# Portfolio Website

This is a static portfolio site and is ready to deploy.

## Easiest way to put it online

Use Netlify Drop:

1. Go to Netlify Drop.
2. Drag the `portfolio-main` folder from this project into the upload area.
3. Netlify will publish the site and give you a live URL.

## If you connect the repo to Netlify

This repo includes a `netlify.toml` file in the outer project folder.

- Publish directory: `portfolio-main`
- Build command: not required

## Notes

- The contact form uses EmailJS from the browser, so static hosting is fine.
- If the form does not send after deployment, the issue will likely be in the EmailJS service or template settings rather than the hosting itself.
