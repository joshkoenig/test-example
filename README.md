

**Don't clone this repo, but fork it - as Shoov is aware to the repository
name, so for the sake of the example, we want to make sure your test is unique**

Shoov is still in early stages so be gentle. Or contribute a PR.

![shoov_gizra_com__code_3a94afa481685398b62e__screenshots_12](https://cloud.githubusercontent.com/assets/125707/6941980/c5bb62d0-d88c-11e4-8e78-75ba19896f27.png)


# Installation

1. Fork this repo, and clone it
1. Install mocha globally ``npm install -g mocha``
1. Follow [installation](https://github.com/webdriverio/webdrivercss#install) notes for all the dependencies
1. Login to (Shoov)[http://shoov.gizra.com] and copy/ paste the code from on the My account page, in order to get your access token
1. ``npm install``

Note that currently the Pull Request functionality isn't deployed yet.

## Providers

For local testing use phantomJs ``phantomjs --webdriver=4444``

Otherwise you can use BrowserStack or Sauce Labs:

```bash
# Set BrowserStack keys
export BROWSERSTACK_USERNAME=<my user>
export BROWSERSTACK_KEY=<your user>
```

OR

```bash
# Set Suace Labs keys
export SAUCE_USERNAME=<my user>
export SAUCE_ACCESS_KEY=<your user>
```

# Usage

``mocha`` will tests all the files under the ``test`` folder.
