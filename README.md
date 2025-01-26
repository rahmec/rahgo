# rahgo 

This is a hugo theme I use for my own personal website.
Hugo let you easily handle documents using markdown.

## Features

rahgo default setup lets you handle 5 default pages + custom blog articles:

- Homepage (`content/_index.md`)
- Library (`content/library.md`)
- Resume (`content/resume.md`)
- Projects (`content/projects.md`)
- Papers (`content/papers.md`)
- Posts (`content/posts/_index.md`)
- Custom post (`content/posts/<post-name>.md`)

For now these are encoded, but I will soon make the pages customizable using a configuration and a script.

## Setup 

```
hugo new site new-site
cd new-site
git clone https://github.com/rahmec/rahgo themes/rahgo
echo "theme = 'rahgo'" >> hugo.toml
```

## Configuration

Configure inside hugo.tml your website and url and contact information:

```
baseURL = 'https://<website-domain>/'
languageCode = 'en-us'
title = '<website-title>'
theme = 'rahgo'
[params]
    [params.contact]
        email = '<email>'
        github = 'https://github.com/<github-username>'
```
