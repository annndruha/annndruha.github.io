# Resume (CV) site. [Example](https://cv.annndruha.space/)

Launch your resume site without server on github pages! Only need a domain.

# Configuration

* Fork this repo as `<you_nickname>.github.io`
* Create CNAME subdomain record on your DNS provider:
  * `cv` -> `<you_nickname>.github.io`
* Open fork repository settings
  * Go to `Pages/Custom domain` enter you `cv.<example.com>` (And enforce HTTPS)
* Make sure that CNAME file in repo contain your subdomain and domain `cv.<example.com>`
* Change left side with your information via [_config.yml](./_config.yml) like this:
  ```
  fullname: Andrey Marakulin
  favicon: /assets/images/favicon.svg
  logo: /assets/images/photo.png
  
  show_info: true
  age: 23 y.o.
  location: Sirius, Russia
  language: Russian, English
  
  show_contacts: true
  mailto: mailto:annndruha.github@gmail.com
  cv_pdf_link: https://raw.githubusercontent.com/Annndruha/annndruha.github.io/main/pdf/cv_pdf.pdf
  
  remote_theme: annndruha/minimal-resume
  plugins:
  - jekyll-remote-theme
  ```
* Change [index.md](./index.md) with you information
* Wait for actions auto build and enjoy your site 😋!


# Additional

This site required pages theme [minimal-resume](https://github.com/Annndruha/minimal-resume) which is in the [_config.yml](./_config.yml) as remote_theme.