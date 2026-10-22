# Publish the NumberyardOS policies

**Naming:** NumberyardOS is the public-facing name of the application. AvsOS is its internal development name; both refer to the same Reddit Devvit application.

This folder is a standalone static website: `index.html`, `privacy.html`, `terms.html`, `style.css`. It requires no backend and publishes **no NumberyardOS source code**.

Recommended route: create a separate public GitHub repository specifically for these legal pages (NOT the private NumberyardOS source), copy these site files to its root, open Settings → Pages, select **Deploy from a branch**, select `main` and `/ (root)`, and save. Use the actual resulting HTTPS links ending in `/privacy.html` and `/terms.html` in Reddit Developer Portal → NumberyardOS → App Details.

Do not treat hypothetical URLs as already published. Verify both public pages load in a logged-out browser before submitting to Reddit. Modmail is the contact channel; the policy does not require a personal email address.
