## Ecstatic Labs Blog

The ecstatic labs platofrm is powered by Octopress 3.0.

Note: Octopress 3.0 is in development at https://github.com/octopress/octopress

## Posts

Current posts can be edited in source/_posts

## Add a new post

    rake new_post

You will find your new post in source/_posts

## Serve Locally

    rake preview

Then browse to http://localhost:4000

## Live Deploy

The first time you pull down this repo you will need to run this setup...

    rake setup_github_pages

When prompted paste in the link to the gh-pages repo.

Finally to push changes into the live blog...

    rake generate
    rake deploy

This will push changes into the gh-pages on the EcstaticLabsBlog and site vistors will see the changes immediately.
Don't forget to push your changes into the source repo using `git push origin`.
