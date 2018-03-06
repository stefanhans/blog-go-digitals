### Hugo sources for website "go-digital"

- develop under "go-digitals-hugo" (repo)

cmd:

    hugo server -D

- create static files for "stefanhans.github.io" (repo)

config.toml:

    baseurl = "https://stefanhans.github.io/"

    publishDir = "../go-digitals-staging"

cmd:

    hugo -D

- push files to "stefanhans.github.io" (github) and view [https://stefanhans.github.io](https://stefanhans.github.io)
