# Arhaan Jain's personal website

A GitHub Pages portfolio using the official [Minimal Jekyll theme](https://github.com/pages-themes/minimal).

## Customize

- Edit `_config.yml` to set your name (`title`) and short introduction (`description`).
- Edit `index.md` to replace the placeholder bio, projects, experience, education, and contact information. Remove sections you don't need.
- Add a photo to `assets/images/profile.jpg` and uncomment `logo` in `_config.yml` to show it in the sidebar.
- Add your CV to `assets/files/cv.pdf` and uncomment the CV link in `index.md`.
- Use `relative_url` for local images and links, as shown in the commented examples in `index.md`. This supports both root sites and project sites.

The layout and CSS come from the theme; you do not need to copy its source files. No custom domain or paid hosting is required.

## Publish on GitHub Pages

1. Sign in to GitHub as `arhaan-jain` and create an **empty public repository** named **`arhaan-jain.github.io`**. Don't add a README or other initial files there.
2. The URL is already configured as `https://arhaan-jain.github.io`, with an empty `baseurl`.
3. From this folder, run:

   ```bash
   git init
   git branch -M main
   git add .
   git commit -m "Set up Minimal Jekyll portfolio"
   git remote add origin https://github.com/arhaan-jain/arhaan-jain.github.io.git
   git push -u origin main
   ```

4. On GitHub, open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **Deploy from a branch**, then **main** and **/(root)**. Click **Save**.
6. Check the repository's **Actions** tab for the Pages build. Once it finishes, open the URL shown in **Settings → Pages**.

GitHub builds Jekyll for you. You do not need Ruby installed locally to publish. Keep Jekyll processing enabled; do not add a `.nojekyll` file.

## Optional local preview

With a current Ruby installation and Bundler available:

```bash
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve
```

Open the local URL printed by Jekyll (normally `http://127.0.0.1:4000`). If `baseurl` is `/Website`, visit `http://127.0.0.1:4000/Website/`.

Restart the preview after changing `_config.yml`. To check a production build:

```bash
bundle exec jekyll build
```

## Future updates

Edit your content, then run:

```bash
git add .
git commit -m "Update portfolio"
git push
```

GitHub Pages rebuilds automatically after each push to `main`.
