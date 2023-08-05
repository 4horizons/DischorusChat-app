<a href="https://www.discourse.org/">
  <img src="https://i1.sndcdn.com/avatars-000018434253-d288tr-t500x500.jpg" width="300px">
</a>

Dischorus is a variation of a 100% open source discussion platform built for the next decade of the Internet. Use it as a:

- mailing list
- discussion forum
- long-form chat room

To learn more about the philosophy and goals of the original project, [visit **Parent Site**](https://www.discourse.org).

## Screenshots

<img src="https://user-images.githubusercontent.com/1681963/52239118-b304f800-289b-11e9-9904-16450680d9ec.jpg" alt="Mobile" width="414">

Browse [lots more notable Discourse instances](https://www.discourse.org/customers).

## Development

To get your environment setup, follow the community setup guide for your operating system.

1. If you're on macOS, try the [macOS development guide](https://meta.discourse.org/t/beginners-guide-to-install-discourse-on-macos-for-development/15772).
1. If you're on Ubuntu, try the [Ubuntu development guide](https://meta.discourse.org/t/beginners-guide-to-install-discourse-on-ubuntu-for-development/14727).
1. If you're on Windows, try the [Windows 10 development guide](https://meta.discourse.org/t/beginners-guide-to-install-discourse-on-windows-10-for-development/75149).

If you're familiar with how Rails works and are comfortable setting up your own environment, you can also try out the [**Discourse Advanced Developer Guide**](docs/DEVELOPER-ADVANCED.md), which is aimed primarily at Ubuntu and macOS environments.

Before you get started, ensure you have the following minimum versions: [Ruby 3.2+](https://www.ruby-lang.org/en/downloads/), [PostgreSQL 13](https://www.postgresql.org/download/), [Redis 7](https://redis.io/download). If you're having trouble, please see our [**TROUBLESHOOTING GUIDE**](docs/TROUBLESHOOTING.md) first!


## Requirements

Dischorus is built for the *next* 10 years of the Internet, so our requirements are high.

supports the **latest, stable releases** of all major browsers and platforms:

| Browsers              | Tablets      | Phones       |
| --------------------- | ------------ | ------------ |
| Apple Safari          | iPadOS       | iOS          |
| Google Chrome         | Android      | Android      |
| Microsoft Edge        |              |              |
| Mozilla Firefox       |              |              |

Additionally, we aim to support Safari on iOS 15.7+.

## Built With

- [Ruby on Rails](https://github.com/rails/rails) &mdash; Our back end API is a Rails app. It responds to requests RESTfully in JSON.
- [Ember.js](https://github.com/emberjs/ember.js) &mdash; Our front end is an Ember.js app that communicates with the Rails API.
- [PostgreSQL](https://www.postgresql.org/) &mdash; Our main data store is in Postgres.
- [Redis](https://redis.io/) &mdash; We use Redis as a cache and for transient data.
- [BrowserStack](https://www.browserstack.com/) &mdash; We use BrowserStack to test on real devices and browsers.

Plus *lots* of Ruby Gems, a complete list of which is at [/main/Gemfile](https://github.com/discourse/discourse/blob/main/Gemfile).

## Accessibility

To guide our ongoing effort to build accessible software we follow the [W3C’s Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/TR/WCAG21/). If you'd like to report an accessibility issue that makes it difficult for you to use Discourse, email accessibility@discourse.org. For more information visit [discourse.org/accessibility](https://discourse.org/accessibility).

## Dedication

Built with [love, Internet style.](https://www.youtube.com/watch?v=Xe1TZaElTAs)
