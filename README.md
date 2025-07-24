# presentation-template
A fast, GitHub-deployable template for making [Reveal.js](https://github.com/joshed-io/reveal-hugo) presentations with [Hugo](https://gohugo.io/)

## Creating a Presentation
### Getting Set Up
Create your repo: Click "Use this template" on GitHub to create your own repository

Clone your repo:
```sh
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

Start the development server:

```sh
hugo server
```

### Customizing Content

Edit `content/_index.md` to update your slides

See a sample deck running locally at [localhost](http://localhost:1313/PLACEHOLDER_REPOSITORY_NAME/#/)

## Deploying to GitHub Pages

Commit and push your changes to the main branch:

``` sh
git add .
git commit -m "Your message"
git push origin main
```

Automatic deploy:

GitHub Actions (using [peaceiris/actions-gh-pages@v3](https://github.com/peaceiris/actions-gh-pages)) will build your site and deploy the static files to the gh-pages branch

Publish:
In your repo settings, set GitHub Pages to deploy from the gh-pages branch (`/root`)

Happy presenting!
