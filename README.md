# Wedding Website - Status = In Development 


If you're reading this- hello! We did not want to use a prebuilt website, we are developers after all! So here it is deployed on GitHub Pages.

The framework used to make the site is also called [Hugo](https://gohugo.io/)

## Inspiration

I took heavy inspiration from [this Wix template](https://www.wix.com/website-template/view/html/1883). I copied the UI (parallax, nav positioning) and made my own version of the round header image using [Affinity Designer](https://affinity.serif.com/en-gb/designer/) using a [colour palette I found](https://colorhunt.co/palette/faf2da8e97754a503de28f83).

## Tools

I used [Hugo](https://gohugo.io/) to build the site even though it's just a single page because
1) It means I can edit the HTML in partials and have easier to understand commits
2) By generating the HTML from config and markdown files I can let non-devs, i.e. my fiance, edit the sites content easily without needing to set up a CMS for a _single page_ of content.

## Deployment

This repo is deployed using GitHub Actions free tier and the [instructions in this guide](https://gohugo.io/hosting-and-deployment/hosting-on-github/).

The GitHub Action runs the `hugo --minify` command to generate the static pages of the site, and then it commit them to the root directory in the `gh_pages` branch. This branch (& the root dir) is the source for the GitHub Pages deployment.

## Tutorials/Resources Used

- [W3 Schools - How TO - Parallax Scrolling](https://www.w3schools.com/howto/howto_css_parallax.asp)
- [Animated Hamburger Menu Tutorial - CSS Effects](https://www.youtube.com/watch?v=dIyVTjJAkLw)

Hugo template derived from 
https://github.com/SarahFrench/wedding-website
