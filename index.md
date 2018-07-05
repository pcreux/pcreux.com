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

{% for project in site.data.os_projects %}

## [{{project.title}}]({{project.url}}) – {{project.description}}

{% endfor %}

# Live, free and unmaintained apps

{% for app in site.data.apps %}

## [{{app.title}}]({{app.url}}) – {{app.description}}

{% endfor %}

# Community

I run [VanRuby](http://vanruby.org).

I co-organized the Ruby Conference [Rulu 2012](http://2012.rulu.eu).

I ran the podcast [ParlonsRuby](http://parlonsruby.com) with Fabien Catteau.

I taught [Agility, TDD and Git](https://speakerdeck.com/search?q=Philippe+Creux+IUT) at the University Aix-Marseille II.

I co-organized the [Lyon Ruby Meetups](http://lyonrb.fr) as well as the
[Valence Agile Meetups](http://groupspaces.com/CARAValence).

# Around the web

You can find me on [Twitter](http://twitter.com/pcreux), [Github](http://github.com/pcreux), [LinkedIn](http://linkedin.com/in/pcreux) and [Instagram](https://www.instagram.com/pcreux).

