---
layout: post
title: Website Released
description: ''
image: "/assets/images/website.jpg"

---
The team and I have been working hard to get an Eco Forum website ready over the past few weeks.

I am pleased to announce the site is ready for release although there will be quite a lot more content added over the coming weeks and perhaps the odd feature.  Please take a look around.

For anyone interested in the technology behind the site, I'll include a little extra information.

cumbria.ecoforum.org.uk is a static [Jekyll](https://jekyllrb.com/) site hosted on [GitHub Pages](https://pages.github.com/).  I have created quite a few sites with these technologies in the past, including my own site, [craigchamberlain.it](https://craigchamberlain.it).  It's a great system with enough features including https enforcement and custom domains.

As I'm working with for this site, I decided to implement a content management system (CMS), which I had not done with Jekyll before.  I quickly found [Forestry](https://forestry.io/) as a compatible CMS and found it easy to customise.  With a few adaptions, I was able to hide the code from the others on the team and give them the means to add and edit content themselves.

![](/assets/images/forestry.jpg)

Another new element for me with this site is custom redirects.  Github Pages handles redirects from www.domain.com to domain.com as standard.  However, with cumbria.ecoforum.org I wanted to redirect from ecoforum.org.  This could be achieved with an entry in an .htaccess file or some other routing system.  However, we are running this domain without a webserver of our own.

I resorted to making a redirect page for each page of cumbria.ecoforum.org and upload to a parallel ecoforum.org site.  Rather than doing this longhand, I used PowerShell to create the files and directories required.

{% gist 41ec4343d4fb417e082ecac72fea2de2 %}

We have some other interesting features from GSuite but I'll save them for another article.

I hope you enjoy the site.  If you have any questions about the site please get in touch, [craig@craig.chamberlain.it](mailto://craig@craig.chamberlain.it).