```diff
- Repo updated to 2.X.X multi-language version.
# If your resume is broked, and you want use old version,
# in YOUR_REPO/_config.yml change this line
- remote_theme: annndruha/minimal-resume
# to this:
- remote_theme: annndruha/minimal-resume@v1.0.0
```

# Web resume (CV) on GitHub pages  ([Example](https://cv.annndruha.space/))

**Fork this repo for create your own web CV ([Example](https://cv.annndruha.space/))**

Launch your resume site without own server! Optional need a domain name.

This is **multi-language** resume. For only one language use [old version](https://github.com/annndruha/annndruha.github.io/releases/tag/v1.0.0)

# Configuration

* Fork this repo as `<you_github_nickname>.github.io`
* Setup your domain (may skip this step and site be on `<you_github_nickname>.github.io`)
  * Create CNAME subdomain record on your DNS provider:
    * `cv` -> `<you_nickname>.github.io`
  * Open fork repository settings
  * Go to `Pages/Custom domain` enter you `cv.<example.com>` (And enforce HTTPS)
  * Change [CNAME-file](https://github.com/annndruha/annndruha.github.io/blob/main/CNAME) in fork with your subdomain: `cv.<example.com>`
* Change left side with your information in [_config.yml](./_config.yml) for both languages.
* Change [index.md](./index.md) with you information for both languages.
  > Be careful and don't delete languages separators. You may use [template](https://github.com/annndruha/annndruha.github.io/blob/main/index_multi_language_template.md). Just delete my `index.md` and rename `index_multi_language_template.md`
* Change `/assets/images/photo.png` and pdf link
* This repo hasn't got a pdf converter, manually update the pdf's files.
* Wait a minute for GitHub-actions auto build and enjoy your site 😋!


# Extra

This site required page theme [minimal-resume](https://github.com/Annndruha/minimal-resume) which is in the [_config.yml](./_config.yml) as remote_theme.
