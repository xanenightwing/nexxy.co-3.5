---
_schema: default
title: Home
seo:
  page_description: >-
    Nexan's Website - a place for a silly possum vtuber to put their opinions in
    a way that can't be censored by the social media sites
  canonical_url:
  featured_image:
  featured_image_alt:
  author_twitter_handle:
  open_graph_type:
  no_index: false
layout: layouts/component-page.html
permalink: /
eleventyExcludeFromCollections: false
content_blocks:
  - _bookshop_name: hero
    background_color: '#808080'
    heading:
      heading_text:
      heading_gradient_color: '#FF785A'
    subheading:
      markdown_content: ''
      color: '#393939'
    image:
      image_path:
      alt_text: >-
        An illustration of someone leaning against the inside of a desktop
        computer monitor, with one leg dangled off the side. They're holding a
        piece of paper with a large 'A', and are next to some buttons on the
        screen.
    buttons:
      - _bookshop_name: buttons/primary
        button_text:
        button_icon:
        button_link:
        background_color: '#034ad8'
        hover_brightness: 0.85
        text_color: '#ffffff'
      - _bookshop_name: buttons/secondary
        button_text:
        button_icon:
        button_link:
        text_color: '#034ad8'
        hover_brightness: 0.95
  - _bookshop_name: left-right
    background_color: '#808080'
    heading:
      heading_text:
      color: '#393939'
    text:
      markdown_content: ''
      color: '#393939'
    image:
      image_path: /assets/images/undraw-hello.svg
      alt_text: >-
        An illustration of someone sitting a desk with a monitor and a pile of
        books on it. Seen from behind, the figure is turned around to face us
        and is waving.
    flipped: true
    button:
      _bookshop_name: buttons/primary
      button_text: GitHub
      button_icon: fa-brands fa-github
      button_link: https://github.com/CloudCannon/eleventy-starter/
      background_color: '#034ad8'
      hover_brightness: 0.85
      text_color: '#ffffff'
  - _bookshop_name: left-right
    background_color: '#ffffff'
    heading:
      heading_text: You choose your editing experience.
      color: '#393939'
      text_color: '#333232'
    text:
      markdown_content: >-
        CloudCannon is a flexible Git-backed CMS that specialises in editing
        markdown and data files.


        Visual editing allows you to preview your changes live before you save
        them.


        Git-backed means you can keep all your familiar git workflows, while
        providing an easy-to-understand interface for non-technical editors to
        collaborate via Git.
      color: '#393939'
      text_color: '#333232'
    image:
      image_path: /assets/images/undraw-startup.svg
      alt_text: >-
        An illustration of someone leaning on one leg while facing us, next to a
        laptop that comes up their waist. One of their hands is on the back of
        the laptop, and one is in their pocket. On the laptop screen is an
        illustration of the world.
    flipped: false
    button:
      _bookshop_name: buttons/primary
      button_text: GitHub
      button_icon: fa-brands fa-github
      button_link: https://github.com/CloudCannon/eleventy-starter/
      background_color: '#034AD8'
      hover_brightness: 0.85
      text_color: '#ffffff'
      button_aria_label:
---
