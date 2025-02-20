# Hugo Mock Landing Page Autodeployed

## Workflow Overview

The .github/workflows/gh-pages-deployment.yaml file sets up an automated process that triggers on every push to the main branch. The workflow performs the following steps:

1. Checkout Repository: Retrieves the source code from the repository, including Hugo themes.

2. Initialize Hugo: Sets up the Hugo environment with the specified version (0.144.1) and enables extended features.

3. Build Static Files: Runs the Hugo build command to generate the static site content.

4. Deploy to GitHub Pages: Publishes the generated site to the gh-pages branch using the peaceiris/actions-gh-pages action.

## Author

Yun Zheng
