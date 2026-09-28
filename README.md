# nedobylskiy.com

Minimal, static personal site for Andrei Nedobylskii. The root `index.html` is the complete site. It requires no build step.

To publish: in repository Settings → Pages, select Deploy from a branch, `main`, `/ (root)`. Configure DNS for the apex domain `nedobylskiy.com`, verify the custom domain in Pages, and enable HTTPS after the certificate becomes available. The `CNAME` file preserves the domain on branch deployments.
