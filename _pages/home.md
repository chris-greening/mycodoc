---
layout: splash
permalink: /
title: Mycodoc
header:
  overlay_image: /images/image.gif
  cta_label: "<i class='fa fa-download'></i> pip install mycodoc"
  cta_url: "https://pypi.org/project/mycodoc/"
excerpt: mycodoc

feature_row:
  - image_path: images/project_overview.png
    image_size: 100px
    alt: ""
    title: "🧠 Clear Project Overview"
    excerpt: "Give visitors a quick understanding of what this project does and why it exists. Use this space to introduce the purpose or goals of your work."
    url: ""
    btn_label: "Learn More"
  - image_path: images/quickstart.png
    alt: ""
    title: "🚀 Quick Start Instructions"
    excerpt: "Help users get up and running fast. Include a few simple steps or commands that explain how to install, build, or run the project."
    url: ""
    btn_label: "Learn More"
  - image_path: images/docs.png
    alt: "100% free"
    title: "📚 Documentation-Ready"
    excerpt: "This site is fully prepared for documentation, guides, and changelogs. Add pages, organize content, and make this project easy to explore."
    url: "/license/"
    btn_label: "Learn More"
github:
  - excerpt: '{::nomarkdown}<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=mmistakes&repo=minimal-mistakes&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe> <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=mmistakes&repo=minimal-mistakes&type=fork&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>{:/nomarkdown}'
---


{% include feature_row %}


<h2> Recent Blog Posts </h2>


{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}


[See all blog posts...]({`{` site.url `}`}{`{` site.baseurl `}`}/blog/){: .btn .btn--info}
