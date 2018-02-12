# Kaltefiste Website

The static website is built using [Nikola](https://getnikola.com/) and served by [Caddy](https://caddyserver.com/).

## edit

Use your favorite text editor to edit the content in `pages/` and `posts/`.

Use `nikola new_post --format=markdown` to create a new post or `nikola new_page --format=markdown` for a new page. You can also just create a new file with your editor and copy the metadata at the top from another one.

## build

```
nikola build
```

## test

This command opens the website in your default browser.

```
nikola serve --browser
```

To rebuild the website automatically after changes use `nikola auto --browser`.

## deploy

Push the website to the production server.

```
nikola deploy
```

Your SSH-Key must be configured to have access.

## commit

Commit your changes to the git repository and push it to Github.

```
git status
git add README.md
git commit -m "add README"
git push
```
