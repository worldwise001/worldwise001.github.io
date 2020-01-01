---
layout: page
title: home
---
### whoami

I am currently a software engineer in bay area, with 4+ years of industry experience, and 4+ years of not-very-relevant academic experience. My pronouns are she/her. I dislike photos of myself. I have strong opinions on software development and security/privacy but I value collaboration. I like really interesting and obscure facts, especially pertaining to cultural, culinary, linguistic, and unrelatedly, electronics/computer history.

### fun stuff

For fun I work on hobbyist electronics and 3D printing. Sometimes I will do hobbyist software projects, but that's rare. I also enjoy cooking and arts/crafts.

Some current projects include building a nixie doom clock and some custom housing for the timelapse cameras for my 3D printer.

I sometimes [play (video) games](https://steamcommunity.com/id/worldwise001), and less frequently [stream my gameplay](https://www.twitch.tv/worldwise001).

I have [two cats](https://www.instagram.com/sprinks_n_izzy).

I run some [Tor relays](/tor/).

### what am i up to

{% for post in site.posts limit:1 %}
    <h3><a class="post-link" href="{{ post.url }}">{{ post.title }}</a></h3>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y"}}</span>
    <p>{{ post.excerpt }}</p>
{% endfor %}

[more...](/posts/)

### work stuff

I wear, or have worn, a number of hats. My title is Software Engineer, but I frequently jump into devops or devsecops or secops or SRE problems. Outside of writing software day to day, my responsibilities also include designing software systems, evaluating security systems and processes, mentoring and advising engineers, and interviewing/screening possible candidates. I am fairly flexible on the tech stack, having experience in the following:
- writing/modifying Linux drivers
- writing operating system core software
- writing highly reliable backend services
- machine learning research
- scaling data pipelines
- web/frontend development
- some minor exploits
- administering Linux servers/systems
- administering PKIs

My research focus in a past life has been on privacy problems relating to big data, namely things like: stylometry and profile-linking problems. I am currently interested in data tracing and protection problems; specifically interested in user credential propagation, and scalable access control techniques on a per-field level as opposed to per-table, per-operation, or per-database level. I am also interested in scalable data identification and redaction techniques, which I find akin on the same difficult as spam identification problems.

You can see my full work history [as a resume](/resume.pdf) or on [LinkedIn](https://www.linkedin.com/in/shharvey).

### contact

I may be reached at s at shh dot sh . My GPG Key is 1BE6 766C DC52 439A 5722 DCA2 BDE4 3806 8A2B D353.

You can also interact with me on [Twitter](https://www.twitter.com/worldwise001).