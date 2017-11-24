---
title: "Where Do Your Czech Customers Live?"
categories:
  - Post Formats
tags:
  - image
  - Post Formats
excerpt: "This post should display a **header with a solid background color**, if the theme supports it."
header:
  overlay_color: "#333"
---

The preferred way of using images is placing them in the `/assets/images/` directory and referencing them with an absolute path. Prepending the filename with `{% raw %}{{ site.url }}{{ site.baseurl }}/assets/images/{% endraw %}` will make sure your images display properly in feeds and such.

Standard image with no width modifier classes applied.

**HTML:**

```html
{% raw %}<img src="{{ site.url }}{{ site.baseurl }}/assets/images/map_cr_cities_bubbles.jpg" alt="">{% endraw %}
```

**or Kramdown:**

```markdown
{% raw %}![alt]({{ site.url }}{{ site.baseurl }}/assets/images/map_cr_cities_bubbles.jpg){% endraw %}
```

![Unsplash image 9]({{ site.url }}{{ site.baseurl }}/assets/images/map_cr_cities_bubbles.jpg)

Image that fills page content container by adding the `.full` class with:

**HTML:**

```html
{% raw %}<img src="{{ site.url }}{{ site.baseurl }}/assets/images/map_cr_cities_bubbles.jpg" alt="" class="full">{% endraw %}
```

**or Kramdown:**

```markdown
{% raw %}![alt]({{ site.url }}{{ site.baseurl }}/assets/images/map_cr_cities_bubbles.jpg)
{: .full}{% endraw %}
```

![Unsplash image 10]({{ site.url }}{{ site.baseurl }}/assets/images/map_cr_cities_bubbles.jpg)
{: .full}