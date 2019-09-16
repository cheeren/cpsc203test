---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: untitleddrawing.png
  caption:
excerpt: "This course consists of a sequence of six explorations, assembled to provide a tour through data structure applications and algorithmic design. Built around topics from arts, sciences, and technology the explorations are thought provoking and engaging. Students emerge from the course with increased proficiency in Python programming, and with a broad spectrum of tools for algorithmic problems solving."
# feature_row:
#   - image_path: mm-customizable-feature.png
#     alt: "customizable"
#     title: "Super Customizable"
#     excerpt: "Everything from the menus, sidebars, comments, and more can be configured or set with YAML Front Matter."
#     url: "/docs/configuration/"
#     btn_label: "Learn More"
#   - image_path: mm-responsive-feature.png
#     alt: "fully responsive"
#     title: "Responsive Layouts"
#     excerpt: "Built on HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
#     url: "/docs/layouts/"
#     btn_label: "Learn More"
#   - image_path: mm-free-feature.png
#     alt: "100% free"
#     title: "100% Free"
#     excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it, whatever!"
#     url: "/docs/license/"
#     btn_label: "Learn More"
# feature_row2:
#   - image_path: mm-customizable-feature.png
#     alt: "customizable"
#     title: "Super Customizable"
#     excerpt: "Everything from the menus, sidebars, comments, and more can be configured or set with YAML Front Matter."
#     url: "/docs/configuration/"
#     btn_label: "Learn More"
#   - image_path: mm-responsive-feature.png
#     alt: "fully responsive"
#     title: "Responsive Layouts"
#     excerpt: "Built on HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
#     url: "/docs/layouts/"
#     btn_label: "Learn More"
#   - image_path: mm-free-feature.png
#     alt: "100% free"
#     title: "100% Free"
#     excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it, whatever!"
#     url: "/docs/license/"
#     btn_label: "Learn More"
github:
  - excerpt: '{::nomarkdown}<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=mmistakes&repo=minimal-mistakes&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe> <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=mmistakes&repo=minimal-mistakes&type=fork&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>{:/nomarkdown}'
---

<!--
{% include feature_row %}

{% include feature_row id="feature_row2" %} -->

<h1>{{ site.data.ui-text[site.locale].schedule | default: "SCHEDULE" }}</h1>

{% for post in site.posts %}
{% include archive-single.html %}
{% endfor %}
