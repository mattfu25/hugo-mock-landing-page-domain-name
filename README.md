# hugo-mock-landing-page

Mock landing page built using Hugo. It's for the "Dinner Table" app. The "Dinner Table" app is a digital space where users anonymously share daily highs and lows, mirroring the family dinner table tradition. It encourages mindfulness through daily prompts, providing a safe, anonymous environment for expression, connection, and growth.

This workflow is designed to automatically build and deploy a website created with the Hugo static site generator to GitHub Pages. It is triggered whenever new code is pushed to the repository's main branch.

The main steps are:

Check out the repository code, including fetching submodules (like Hugo themes) and the full commit history needed for certain Hugo features.
Set up the Hugo environment with the specified version and enable the extended Hugo functionality.
Build the static website files by running the hugo command with flags for including drafts, garbage collection, and minification.
Publish the generated static files to the gh-pages branch of the repository, which GitHub Pages uses to host and serve the website.
Optionally, the workflow can be configured to use a custom domain for the published site instead of the default GitHub Pages URL.
The workflow ensures an automated way to rebuild and republish the Hugo website whenever changes are made to the main codebase. It leverages GitHub's hosting capabilities for static sites by pushing the compiled files to the gh-pages branch.

Updated domain name.
