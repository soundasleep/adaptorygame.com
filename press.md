---
layout: press

# NOTE:
# jekyll doesn't support including markdown yet. Ugh.
# This is why we have the nasty { capture } junk.
# https://github.com/jekyll/jekyll/issues/1303
---

# [Adaptory](/) – press kit

<section class="toc">
  {% capture temp %}{% include press/toc.md %}{% endcapture %}
  {{ temp | markdownify }}
</section>

<section class="facts">
  {% capture temp %}{% include press/facts.md %}{% endcapture %}
  {{ temp | markdownify }}
</section>

<section class="description">
  {% capture temp %}{% include press/description.md %}{% endcapture %}
  {{ temp | markdownify }}
</section>

<section class="content">
  {% capture temp %}{% include press/content.md %}{% endcapture %}
  {{ temp | markdownify }}
</section>

Contact: Jevon Wright <[hello@stormcloak.games](mailto:hello@stormcloak.games)>

Last updated March 2024.
