
![](https://d3k90kvix375hb.cloudfront.net/assets/home/hero/startup@2x-7d19c0222639db59ac497178719016583e1c886ac83eff67670d2c7584513620.png)

# Awesome Heroku [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of helpful Heroku resources.


## Table of Contents

- [Deployment](#deployment)
- [Domains](#domains)
- [Security](#security)
- [Toolbelt](#toolbelt)


## Deployment

- `article` [Automating our Heroku deployments from Jenkins](https://www.paulfurley.com/automating-heroku-deployments-from-jenkins/) — explains how you'd go about automating certain parts of deployment like enabling maintenance mode, copying your database from production to staging, running migrations against staging, etc.


## Domains

- `article` [Hosting multiple Heroku apps on a single domain](https://pilot.co/blog/hosting-multiple-heroku-apps-on-a-single-domain/) — an article on how to share the same domain between multiple Heroku applications.
- `question` [How do you host multiple heroku apps on a single domain?](http://stackoverflow.com/questions/19119164/multiple-heroku-apps-on-a-single-domain) — a StackOverflow question with a few responses to a the common question of how to serve multiple Heroku apps from different paths instead of subdomains.


## Security

- `article` [Set up CloudFlare's free SSL on Heroku](https://robots.thoughtbot.com/set-up-cloudflare-free-ssl-on-heroku) — walks you through the exact steps to setting up free SSL via Cloudflare.


## Toolbelt

- `official` [Toolbelt Download](https://toolbelt.heroku.com/) — where to download the Heroku toolbelt.
- `plugin` [heroku-accounts](https://github.com/ddollar/heroku-accounts) — makes it easy to work with multiple accounts at once from the command line.
- `plugin` [heroku-pg-extras](https://github.com/heroku/heroku-pg-extras) — a toolbelt plugin that adds extra useful plugins for working with Postgres. Things like analyzing cache hit rates, outlier queries, unused indexes, table sizes, etc.


## Goodbye...

- `tool` [dokku](http://dokku.viewdocs.io/dokku/) — a self-hosted, docker-based, Heroku-compliant platform.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ian Storm Taylor](http://ianstormtaylor.com) has waived all copyright and related or neighboring rights to this work.
