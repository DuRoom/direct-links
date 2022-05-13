# Direct Links

This extension adds direct links to various DuRoom actions:

- `/login` will redirect to homepage and open the Log In modal
- `/signup` will redirect to homepage and open the Sign Up modal
- `/forgot` will redirect to homepage and open the Forgot Password modal
- `/composer` will redirect to the all discussions page and open the new discussion composer box

Additionally, **only for the composer**, you may append `?title=`, `?content=` and/or `?primary_tag=slug` parameters to `/composer` to define the default values in the editor. This is useful for share features or bookmarklets.

Sample url with auto-fill parameters:

`/composer?title=test&primary_tag=general&content=this is some content`

## Installation

```bash
composer require duroom/direct-links
```

## Updating

```bash
composer update duroom/direct-links
php duroom migrate
php duroom cache:clear
```

## Removing

```bash
composer remove duroom/direct-links
```
