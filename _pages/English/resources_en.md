---
title: "Resources"
layout: splash_en
permalink: /en/resources
header:
    overlay_color: "#d7ecf8"
    overlay_filter: rgba(15, 80, 180, 0.6)
    overlay_image: /images/splash/resources.webp
    caption: "[**Unsplash**](https://unsplash.com/)"

excerpt: "Download services, talks, articles and books here"

services:
- title: "Services"
  excerpt: " Here you can download PDF-versions of my services."
  image_path: "/images/resources/services.webp"
  image_caption: "Image from [Unsplash](https://unsplash.com)"
  btn_label: "Investigation into the 'State of the Nation'"
  btn_class: btn--primary
  url: "downloads/services/State-of-the-nation.pdf"

vorträge:
- title: "Lectures"
  image_path: "/images/resources/lectures.webp"
  url: "/resources/lectures"
  image_caption: "Image from [Unsplash](https://unsplash.com)"
  btn_label: "To the lectures"
  btn_class: btn--primary
  excerpt: "Here you can download several lectures (partly german)."

artikel:
- title: "Articles"
  image_path: "/images/resources/articles.webp"
  image_caption: "Image from [Unsplash](https://unsplash.com)"
  url: "/resources/articles"
  btn_label: "To the articles"
  btn_class: btn--primary
  excerpt: "Here you can download several articles (partly german)."

bücher:
- title: "Books"
  image_path: "/images/resources/book.webp"
  image_caption: "Image from [Unsplash](https://unsplash.com)"
  url: "downloads/books/agile_softwareentwicklung_embedded_real_time_systems_uml.pdf"
  btn_label: "Download here"
  btn_class: btn--primary
  excerpt: 'The book "Agile Softwareentwicklung für Embedded Real-Time Systems mit der UML" is unfortunately no longer available in stores. Therefore here as a free download'
---

{% include feature_row id="services" type="right"%}
{% include feature_row id="vorträge" type="left"%}
{% include feature_row id="artikel" type="right"%}
{% include feature_row id="bücher" type="left"%}