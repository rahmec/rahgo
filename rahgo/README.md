# rahgo 

This is a [Hugo](https://github.com/gohugoio/hugo) theme I use for my own [personal website](https://rielme.ch).
Hugo let you easily handle documents using markdown.

## Setup 

```
hugo new site new-site
cd new-site
git clone https://github.com/rahmec/rahgo themes/rahgo
echo "theme = 'rahgo'" >> hugo.toml
```

## Configuration

Configure inside `hugo.toml` your website's url and contact information:

```
baseURL = 'https://<website-domain>/'
languageCode = 'en-us'
title = '<website-title>'
theme = 'rahgo'
[params]
    [params.contact]
        email_name = '<name>'
        email_domain1 = '<domain1>'
        email_domain2 = '<domain2>'
        github = 'https://github.com/<github-username>'
        orcid = 'https://orcid.org/<orcid>'
        domain = '<domain>'

```
