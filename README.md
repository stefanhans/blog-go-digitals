### Hugo sources for website "go-digital"

- develop under "go-digitals-hugo" (repo)


    baseurl = "https://stefanhans.github.io/"
    hugo server -D

- create static files for "stefanhans.github.io" (repo)

config.toml:

    baseurl = "https://stefanhans.github.io/"

    publishDir = "../go-digitals-staging"

cmd:

    hugo -D

