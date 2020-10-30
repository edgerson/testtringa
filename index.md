---
layout: blocks
title: Homepage
date: 2017-11-22T23:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2020/10/30/tringabirdicon_web.png"
  navigation:
  - link: "#features"
    link_text: Features
  - link: "#about"
    link_text: About
  cta:
    url: https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&provider=github&engine=jekyll
    button_text: Sign up for beta
- template: hero-banner-w-image
  block: hero-2
  slug: features
  headline: Continuous delivery for your whole team
  content: Tringa helps you seamlessly deploy software through your unique development
    pipeline to any hosting solution.
  cta:
    enabled: true
    url: https://github.com/forestryio/ubuild-jekyll
    button_text: Sign up for our beta
  image:
    image: ''
    alt_text: ''
  background_image: "/uploads/2018/06/21/hero-2-bg.png"
- template: detail-content
  block: text-1
  headline: Beta Features
  content: "<ul><li><p>With easy access to version status and deployment process,
    Tringa empowers your team to stay in sync and keep releasing great tools. Plus,
    you’ll get some extra features like easy rollbacks and redeployments.</p></li></ul>"
- template: 1-column-text
  block: one-column-1
  slug: about
  headline: About
  content: This is background of Tringa...
- template: signup-bar
  block: cta-bar
  content: Test!
  email_recipient: ''
- template: simple-footer
  block: footer-1
  content: Made with ❤︎ in Canada
- template: 2-column-text
  block: two-column-1
  col_1:
    headline: Beta Features
    slug: features
    content: ''
  col_2:
    headline: test 2
    slug: test2
    content: test tests
published: false

---
