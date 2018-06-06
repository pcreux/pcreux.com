---
layout: home
---

Hello, my name is Philippe Creux.

I am a Software Developer based in Vancouver, BC. I deeply care about shipping software that’s simple, robust and cost-effective.

I build healthy software at [Kickstarter](https://www.kickstarter.com) to *help bring creative projects to life*.

I’ve been sharing my learnings and practices on various blog posts and built several open source projects.

I am currently running the [Vancouver Ruby meet-up](http://vanruby.org). Prior to that, I ran the meet-ups [Lyon.rb](http://lyonrb.fr) and [Agile Valence](http://groupspaces.com/CARAValence), hosted the podcast [Parlons Ruby](http://parlonsruby.com) and co-organized the [Ruby Lyon Conference 2012](http://2012.rulu.eu).


# Latest blog posts

{% for post in site.data.posts %}

## [{{post.title}}]({{post.url}}) – {{post.date}}

{% endfor %}

# Latest talks

{% for talk in site.data.talks %}

## [{{talk.title}}]({{talk.url}}) – {{talk.date}}, at [{{talk.location.name}}]({{talk.location.url}})

{% endfor %}

# Open source

## [CSV Importer](https://github.com/pcreux/csv-importer) – CSV Import for humans on Ruby / Ruby on Rails

## [ActiveAdmin](http://activeadmin.info) – Administration framework for Ruby on Rails

## [rspec-set](https://github.com/pcreux/rspec-set) – Speed-up your specs!

## [jekyll-s3](https://github.com/laurilehmijoki/s3_website) – Push your jekyll blog to Amazon S3

## [active_sanity](https://github.com/pcreux/active_sanity) – Sanity check your database

## [bundler-auto-update](https://github.com/pcreux/bundler-auto-update) – Auto-magi-safely update your Gemfile

## [git-branch-delete-orphans](https://github.com/pcreux/git-branch-delete-orphans) – Delete orphan branches

# Live, free and unmaintained projects

## [3Smileys](http://3smileys.com/) – Get feedback on newsletters and emails you send. 2013

## [bustop.ca](http://bustop.ca/) – Real-time bus arrivals in Vancouver, BC. 2012

## [thatz.at/](http://thatz.at/) – Your time in any timezone. 2010

# Community

I run [VanRuby](http://vanruby.org).

I co-organized the Ruby Conference [Rulu 2012](http://2012.rulu.eu).

I ran the podcast [ParlonsRuby](http://parlonsruby.com) with Fabien Catteau.

I taught [Agility, TDD and Git](https://speakerdeck.com/search?q=Philippe+Creux+IUT) at the University Aix-Marseille II.

I co-organized the [Lyon Ruby Meetups](http://lyonrb.fr) as well as the
[Valence Agile Meetups](http://groupspaces.com/CARAValence).

# Around the web

You can find me on [Twitter](http://twitter.com/pcreux), [Github](http://github.com/pcreux), [LinkedIn](http://linkedin.com/in/pcreux) and [Instagram](https://www.instagram.com/pcreux).

# Contact me at pcreux AT gmail DOT com.

