# static-site-template

This repo contains a basic static site designed to be deployed to github pages

branches:
- `main` (where you are now) there is a 'vanilla' static site
- `jekyll` there is an example of using the static site generator [Jekyll](https://jekyllrb.com/) 

## Quick start

### 1. Fork the repo


### 2. Enable GitHub pages
In your repository on GitHub:
1. Navigate to `Settings > Code and Automation > Pages`
2. Set source `Deploy from a branch`
3. Select `main` in the dropdown and `/ (root)`
4. Press `Commit changes` in the top right

Navigate back to the `Code` tab and you should see `Deployments` in the pane on the right. You might have to push a new commit to trigger the first deployment. Click `github-pages` in `Deployments` and it will show you the url your site is published to.

### 3. Custom domain
Your site will be served on `*.github.io/<repo-name>` but it's more fun to have it on your own domain.

You'll need to purchase a domain from a registrar - and there is £20 tech budget available for this. These are normally charged yearly, and the tech budget is one-off (but next year's tech officers will probably let you expensive the domain again?)

Then once you have control of your domain you'll need to set up dns A/AAAA records to point to github's ip ranges. Follow the [github instructions](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain).

DNS is slow so don't panic if it doesn't work immediately just try again after a few minutes.

### 4. Hack

See these sites for inspiration:
- https://web.archive.org/web/20010730092051/http://softwire.co.uk/index.htm
- https://neocities.org/
- https://lvs.me.uk/
- https://downpour.games/~holly/where-s-madeleine?p=6sn
- https://earthbagbuilding.com/
- https://periodictable.com/Properties/A/Color.html

## Other ideas

- Write a django, ruby on rails, or other serverside rendered site without any javascript.
- Make a game see [downpour](https://downpour.games/)
- de-make an existing site to run under web 1.0. e.g. [frog-find, a search engine for use on vintage computers](http://frogfind.de/?lg=en-us)