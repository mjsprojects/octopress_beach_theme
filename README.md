# Octopress Beach theme

This is an Octopress theme based on a Drupal theme from https://drupal.org/project/beach

## Installation

These instructions will create a git submodule under the __.themes/beach__ directory. From your blog directory, run these commands.

``` sh
git submodule add https://github.com/mjsprojects/octopress_beach_theme.git .themes/beach
```

You should then commit the changes.

``` sh
git add .themes
git add .gitmodules
git commit -m "added beach theme"
```

Next, you should apply the theme to your blog and generate the stylesheets. Follow the [install instructions](#applying-the-beach-theme-to-your-blog).

## Updating the theme

From your Octopress blog's directory, assuming your theme directory is called __beach__.

``` sh
cd .themes/beach
git pull origin master
```

Next, you should apply the theme to your blog and generate the stylesheets. Follow the [install instructions](#applying-the-beach-theme-to-your-blog).

## Applying the beach theme to your blog

Follow this set of instructions whenever you made a new install or update to your themes.

``` sh
rake install[beach]
rake generate
```

Take a look at the changes using the in built Octopress local server at http://localhost:4000

``` sh
rake preview
```

If everything looks ok, deploy it.

``` sh
rake deploy
```

## Support

Should you have any problems, raise an issue on this repository.

