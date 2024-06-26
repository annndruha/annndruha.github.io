```diff
- Repo updated to 2.X.X multi-language version.
# If your resume is broked, and you want use old version,
# in YOUR_REPO/_config.yml change this line
- remote_theme: annndruha/minimal-resume
# to this:
- remote_theme: annndruha/minimal-resume@v1.0.0
```

# Web resume (CV) on GitHub pages  ([Example](https://cv.annndruha.space/))

**Fork this repo for create your own web CV**

Launch your resume site without own server! Optional set a domain name.

This is **multi-language** resume. For only one language use [old version](https://github.com/annndruha/annndruha.github.io/releases/tag/v1.0.0)

# Configuration

## Fork and setup 
* Fork this repo as `<you_github_nickname>.github.io`
* Change left side with your information in [_config.yml](./_config.yml) for both languages.
  * `show_branding` flag for show or disable branding-header.
* Change [index.md](./index.md) with you information for both languages.
  > Be careful and don't delete languages separators. You may use files from templates folder. Just replace `index.md` with one of templates.
* Change `/assets/images/photo.png` and pdf's links.
* This repo hasn't got a pdf converter, manually update the pdf's files in `/assets/pdf`.
* Wait a minute for GitHub-actions auto build and enjoy your site on `<you_github_nickname>.github.io` 😋!

## Set a own sub-domain name.
* Setup your domain (may skip this step and site be on `<you_github_nickname>.github.io`)
  * Create CNAME subdomain record on your DNS provider:
    * `cv` -> `<you_nickname>.github.io`
  * Open fork repository settings
  * Go to `Pages/Custom domain` enter you `cv.<example.com>` (And enforce HTTPS)
  * Change [CNAME-file](https://github.com/annndruha/annndruha.github.io/blob/main/CNAME) in fork with your subdomain: `cv.<example.com>`

# Extra

This site uses theme [minimal-resume](https://github.com/Annndruha/minimal-resume) which is in the [_config.yml](./_config.yml) as remote_theme. Don't remove theme line from config.yml.
