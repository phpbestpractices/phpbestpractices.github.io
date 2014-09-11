# PHP Best Practices

This is the GitHub Pages repository for the _PHP Best Practices_ project in
order to manage translations of https://phpbestpractices.org/.

* This website is a simple HTML file project.

## How to Contribute

1. Fork and edit
2. Preview locally
3. Submit pull request for consideration

## Where

https://phpbestpractices.org/ or https://phpbestpractices.github.io/

* English: [.org](https://phpbestpractices.org/) | [.github.io](https://phpbestpractices.github.io/)
* Brazilian Portuguese: [.org](https://phpbestpractices.org/index.pt_BR.html) | [.github.io](https://phpbestpractices.github.io/index.pt_BR.html)

### Translations

If you are interested in translating _PHP Best Practices_, fork this repo on
GitHub and publish your localized fork to your own GitHub Pages account. We'll
link to your translation from the primary document.

When your translation is ready, open an issue on the
[Issue Tracker](https://github.com/phpbestpractices/phpbestpractices.github.io/issues)
to let us know.

#### Meta Tag for Tracking/Syncing with EN

PHP Documentation itself has some rules for translations, you can see more on
http://doc.php.net/tutorial/translating.php for translating.

To ease tracking of translations to you and to others getting into the efforts
in the future, let's use this:

```html
<!-- EN-Revision: [some SHA-1 commit] -->
```

This way we can say in which [english version](index.html) your translation
is based, and see if it's desynced.

Example:

```html
<!doctype html>
<html>
    <head>
        <!-- EN-Revision: 37c7eea0a03a9129fb99e3e9355b05daa80d826e -->
        <title>
        ...
```

To get the SHA-1 of the latest modification, use one of these commands:

```shell
$ git log index.html | head -n 1 | awk '{print $2}'
```

or

```shell
$ git log index.html
```

## License

[PHP Best Practices](https://phpbestpractices.org/) by [Alex Cabal](https://alexcabal.com/) is released into the [public domain](https://creativecommons.org/publicdomain/zero/1.0/).
