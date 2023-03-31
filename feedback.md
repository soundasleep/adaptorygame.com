---
layout: page
title: Leave feedback
---

<img src="/assets/images/icons/1f973.svg" alt="Party emoji" style="max-width:72px;max-height:72px;" />

## Thanks for playing Adaptory!

I'd love to hear how you feel! You can [mail me directly](mailto:jevon@stormcloak.games)
or come [join the party on Discord](https://discord.gg/gku8afsKWF).

You can also share your feedback with others on the web:

<ul class="social-media-list">
  <li><a class="highlight-inline" href="https://www.twitter.com/{{ site.twitter_username| cgi_escape | escape }}" title="Twitter"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#twitter' | relative_url }}"></use></svg> <span class="username">{{ site.twitter_username| escape }}</span></a></li>

  {%- for mst in site.mastodon -%}{%- if mst.username and mst.instance -%}<li><a class="highlight-inline" href="https://{{ mst.instance| cgi_escape | escape}}/@{{mst.username}}" title="Mastodon"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#mastodon' | relative_url }}"></use></svg> <span class="username">{{ mst.username|escape }}</span></a></li>{%- endif -%}{%- endfor -%}

  <li><a class="highlight-inline" href="https://reddit.com/r/{{ site.subreddit| cgi_escape | escape }}" title="Reddit"><svg class="svg-icon"><use xlink:href="{{ '/assets/reddit1.svg#reddit' | relative_url }}"></use></svg> <span class="username">{{ site.subreddit| escape }}</span></a></li>

  <li><a class="highlight-inline" href="https://www.facebook.com/{{ site.facebook_username| cgi_escape | escape }}" title="Facebook"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#facebook' | relative_url }}"></use></svg> <span class="username">{{ site.facebook_username| escape }}</span></a></li>
</ul>

