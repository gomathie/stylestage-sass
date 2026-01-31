# Style Stage Source Sass

> A minimal starter for Style Stage submissions that includes the source Sass used to create the base Style Stage theme, and the source HTML.

[Read the full guidelines](https://stylestage.dev/guidelines/) to ensure your final styles will be ready for inclusion in the showcase!

## Group Members

1. Bodric Young
2. TJ Stricklang
3. Mathias Lago

The final stylesheet will be placed in `public/style.css`.

You may alter anything and everything, but keep in mind that the final stylesheet should be unminified and ideally non-prefixed. All Style Stage submissions are parsed with `autoprefixer` during the publish build process, and unminified stylesheets are easier for visitors to learn from.

> If you change the output stylesheet name, be sure to update the link to it in `index.html`

### Publish to Github Pages

This starter uses github actions to auto deploy `public` directory to `gh-pages` branch whenever there is a push to `main` branch.

1. Go to repo settings, under Github Pages, select `gh-pages` as source
2. Go to https://username.github.io/stylestage-sass to see your published site.

## Submitting Your Stylesheet

Once you've created your stylesheet with this starter, publish this as a public repo and then you can use the GitHub link to the "raw" version of the `public/style.css` file for your final submission.

If you choose to publish to github pages, you can use:
https://username.github.io/stylestage-sass/style.css

You will need to fork [the main Style Stage repo](https://github.com/5t3ph/stylestage) to add your stylesheet, as [explained in the FAQ](https://stylestage.dev/guidelines/#how-do-i-create-a-pull-request-pr).
