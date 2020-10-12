---
layout: blocks
title: Homepage
date: 2017-11-22T23:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2020/10/12/tringawordmark_web_10-2020.png"
  navigation:
  - link: "/"
    link_text: Ubuild
  - link: "#swap"
    link_text: Swap
  - link: "#customize"
    link_text: Customize
  - link: "#responsive"
    link_text: Responsive
  - link: "#blocks"
    link_text: Blocks
  cta:
    url: https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&provider=github&engine=jekyll
    button_text: Import
- template: hero-banner-w-image
  block: hero-2
  slug: features
  headline: Continuous delivery for your whole team
  content: Tringa helps you seamlessly deploy software through your unique development
    pipeline to any hosting solution. With easy access to version status and deployment
    process, Tringa empowers your team to stay in sync and keep releasing great tools.
    Plus, you’ll get some extra features like easy rollbacks and redeployments.
  cta:
    enabled: true
    url: https://github.com/forestryio/ubuild-jekyll
    button_text: Sign up for our beta
  image:
    image: "/uploads/2018/06/21/product-shot-1.png"
    alt_text: Product Shot
  background_image: "/uploads/2018/06/21/hero-2-bg.png"
- template: content-feature
  block: feature-1
  media_alignment: Left
  slug: about
  headline: "<strong>About</strong>"
  content: This is background of Tringa...
  media:
    image: "/uploads/2018/06/21/blocks-split.png"
    alt_text: uBuild Blocks Mock-Up
- template: 1-column-text
  block: one-column-1
  slug: responsive
  headline: 16 Fully Responsive Design Blocks
  content: |
    The Design Blocks can be used without Forestry but to harness the power
    of Blocks we recommend using <a href="https://forestry.io">Forestry</a>. Once the site is imported you can immediately
    create new sites and make them fully customizable.
- template: full-width-media-element
  block: media-1
  image: "/uploads/2018/06/21/theme.png"
  caption: All Available Blocks
  slug: blocks
- template: detail-content
  block: text-1
  headline: About
  content: "<p>This is a paragraph about Tringa.</p>"
- template: signup-bar
  block: cta-bar
  content: Test!
  email_recipient: ''
- template: simple-footer
  block: footer-1
  content: Made with ❤︎ in Canada
published: false

---
