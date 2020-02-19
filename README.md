# Hugo Airspace Forestry starter

![Preview](https://user-images.githubusercontent.com/37659754/53851035-78e85c80-3fe7-11e9-8589-8a0524071d60.png)

[Live Preview](http://demo.themefisher.com/airspace-hugo/)

[Airspace Hugo theme](https://github.com/themefisher/airspace-hugo/) is developed by Themefisher.

## Requirements

- GitHub, GitLab or BitBucket account
- Hugo > 0.58.0

## Content Management

![](static/images/kross-forestry.jpg)

[![import to Forestry](https://assets.forestry.io/import-to-forestryK.svg)](https://app.forestry.io/quick-start?repo=DirtyF/hugo-airspace-forestry&engine=hugo&version=0.64.1)

This project has been pre-configured to work with [Forestry](https://forestry.io) a git-based CMS, [import your repository in Forestry](https://app.forestry.io/quick-start?repo=DirtyF/hugo-airspace-forestry&engine=hugo&version=0.64.1) and you'll be able to edit and preview your site ✨. \

Any changes you make in Forestry will be commited back to the repo, and deployed if you use [Netlify](#netlify) or [ZEIT now](#zeit-now).

## Local development

```bash
# clone the repository
git clone git@github.com:DirtyF/hugo-airspace-forestry.git

# cd in the project directory
cd hugo-airspace-forestry

# Start local dev server
hugo server
```

## Deployment and hosting 

### Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/DirtyF/hugo-airspace-forestry)

1. Set the build command to: `hugo --gc --minify`
2. Set the publish directory to: `public`
3. Make sure to set `HUGO_VERSION` to 0.58.0 or above (tested with 0.64.1)
3. Set the publish directory to: `public`

That's it, now your site gets deployed automatically on `git push` or when saving documents from Forestry.

### ZEIT Now

[![Deploy with ZEIT Now](https://zeit.co/button)](https://zeit.co/new/project?template=https://github.com/DirtyF/hugo-airspace-forestry)

Follow the steps.

## Feedback

[Open an issue](https://github.com/themefisher/airspace-hugo/issues) in the theme's repository.

## LICENSE

MIT as specified in the theme's [LICENSE](https://github.com/themefisher/airspace-hugo/blob/master/LICENSE) file 
