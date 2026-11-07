# Arhaan Jain's robotics research portfolio

A GitHub Pages website using the [Minimal Jekyll theme](https://github.com/pages-themes/minimal), with a custom responsive layout and project media.

Live URL: https://arhaan-jain.github.io/Website/

## Edit the site

- `index.md`: research introduction, papers, research experience, education, and skills.
- `_data/projects.yml`: selected project descriptions, media paths, and links.
- `more.html`: PillBuddy, industry experience, community work, and interests.
- `_config.yml`: profile name, contact links, CV path, and GitHub Pages URL.
- `_layouts/default.html`: shared profile sidebar and navigation.
- `_includes/project.html`: reusable project entry.
- `assets/css/style.scss`: styles extending the Minimal theme.
- `assets/images/`, `assets/videos/`, `assets/files/`: curated assets served by the website.

Use `relative_url` for local links so they include `/Website`. Project media paths in `_data/projects.yml` are processed by the include automatically.

The CV download is the supplied `UPenn Resume Academic.pdf`, published as `assets/files/arhaan-jain-academic-cv.pdf`. Update this copy when replacing the academic résumé.

## Source material

Original uploads in `W/`, `Profile Pic/`, and `Resume Dump/` are kept locally and excluded from both Git and Jekyll output. The site uses curated copies and compressed videos in `assets/`. Do not force-add the original folders: several original videos exceed GitHub's file-size limit.

Content comes from the supplied résumé versions, HeLoM and X-Morph papers, the final-year presentation, and project reports. The more recent résumés supply Penn education and the current research role. The actuator-network project uses the presentation's Go1 platform description; the résumé's broader MARMot work also mentions Go2. Paper figures are taken from the supplied PDFs and link to their papers. Papers are labeled as preprints/under review, as specified in the résumés.

Project videos are silent H.264 MP4 clips at 960px wide, with poster images and on-demand playback. The turtle entry links to the full YouTube video. Other original videos remain in the local source folders for future use.

## Local preview

Use a current Ruby installation with Bundler (the system Ruby on older Macs may be too old for current GitHub Pages dependencies):

```bash
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve
```

Visit http://127.0.0.1:4000/Website/. Restart after changing `_config.yml`.

For a production build:

```bash
bundle exec jekyll build
```

## Publish updates

The GitHub remote is `https://github.com/arhaan-jain/Website.git`. Pages should use **Deploy from a branch → main → /(root)**.

```bash
git add .
git commit -m "Update portfolio"
git push
```

Check the repository's Actions tab for the Pages build. GitHub runs Jekyll; do not add a `.nojekyll` file.
