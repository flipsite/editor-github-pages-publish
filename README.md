# Flipsite Editor: Publish to GitHub Pages

Follow these steps to enable publishing to GitHub Pages directly from the Flipsite Editor.

## Steps

1. **Enable GitHub Pages** in your repository  
   - Go to your repository **Settings → Pages** and select the branch you want to publish from.

2. **Add a custom workflow** to your repository  
   - Copy the workflow code from [`workflow.yml`](workflow.yml) and add it to `.github/workflows/` in your repository.

3. **Create a personal access token (PAT)** with fine-grained access  
   - Visit [Personal Access Tokens](https://github.com/settings/personal-access-tokens) to create a token.

4. **Set permissions for the token**  
   - Grant **Read & Write** access for **Actions** and **Contents** of the repository.

5. **Connect Flipsite Editor to GitHub**  
   - Go to the Flipsite Editor **Settings** page and add your repository and the access token.
