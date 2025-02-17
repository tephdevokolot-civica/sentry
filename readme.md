# Sentry

Sentry is a PHP 7.2+ fully-featured authentication & authorization system. It also provides additional features such as user groups and additional security features.

Sentry is a framework agnostic set of interfaces with default implementations, though you can substitute any implementations you see fit.

[![Build Status](https://travis-ci.org/cartalyst/sentry.png?branch=master)](https://travis-ci.org/cartalyst/sentry)

![Bitdeli](https://d2weczhvl823v0.cloudfront.net/cartalyst/sentry/trend.png)

### Features

It also provides additional features such as user groups and additional security features:

- Configurable authentication (can use any type of authentication required, such as username or email)
- Authorization
- Activation of user *(optional)*
- Groups and group permissions
- "Remember me"
- User suspension
- Login throttling *(optional)*
- User banning
- Password resetting
- User data
- Interface driven - switch out your own implementations at will

### Installation

Installation of Sentry is very easy. We've got a number of guides to get Sentry working with your favorite framework or on it's own:

In your `composer.json` file add `"cartalyst/sentry": "dev-feature/laravel-5.7",` to the `require` section.

Then add

```
"repositories": [
	{
		"type": "git",
		"url": "https://github.com/JamesMahy/sentry.git"
	},		
]
```

Once you've done this, you can follow the instruction here ignoring the Preparation section [Install Sentry](https://cartalyst.com/manual/sentry#installation)

### Getting Started

- Use [natively (through composer)](https://cartalyst.com/manual/sentry#native)

### Upgrading

Currently, we do not have an upgrade method from Sentry 1, however we may be able to publish one before the stable release of Sentry 2.0. When upgrading between betas or release-candidates, please see [our changelog](https://github.com/cartalyst/sentry/blob/master/changelog.md).

### Support

We offer support through [our help forums](http://help.cartalyst.com), on [IRC at #cartalyst](http://webchat.freenode.net/?channels=cartalyst) and through GitHub issues (bugs only).

If you like Sentry, consider [subscribing](http://www.cartalyst.com/pricing) to our [Arsenal](http://www.cartalyst.com/arsenal). It allows us to keep creating awesome software and afford to eat at night. Subscribers also get **priority support** with all of our packages, both free and subscriber-only.

