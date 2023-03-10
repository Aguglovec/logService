---
title: Blockquotes - Shortcodes
sectionID: unique_id_3
permalink: false
date: 2020-09-23
excerpt: Blockquotes are easy, even in Markdown. But what if you want to style them?
author: shane-robinson
draft:
eleventyNavigation: # Required if want to display in Main Nav Bar
  key: main # "main" is required
  title: Препцентры # as it will appear in the nav
  order: 3 # order to display in the nav (index = 1)
  url: preps
  local: true  
seo:
  title:
  description:
  image: 2020/09/blockquote.jpg
images: # relative to /src/assets/images/
  feature:
  thumb: 2020/09/blockquote.jpg
  slide:
tags:
  - blockquote
  - shortcodes
  - emoji
  - markdown
section: hero-graphic-section
sectionSettings:
  height:
    mobile: # options = h-1/1 (default = full screen), h-1/2, h-1/3, h-3/4, h-9/10, h-48 (12rem, 192px), h-56 (14rem, 224px), h-64 (16rem, 256px)
    desktop: # leave blank to inherit "mobile" height (default = full screen)
  bg:
    color: # default bg-black
    image: home/port3.jpg # relative to /assets/images/
    imagePosition: # options = bg-center (default), bg-left, bg-right
    video: pixabay-john-macdougall.mp4 # local relative /assets/video/, or full https://... if remote?
    opacityMobile: opacity-50 # options opacity-n, 5, 10, 15, 20, 25, 50, 75, 100 (default)
    opacityDesktop: opacity-75 # Leave blank to inherit opacityMobile, use same options as opacityMobile
  headingText: Прием и хранение товара в стране назначения, доставка на Амазон
  headingTextColor: # default = text-white (can use any TailwindCSS text-[color]-[xxx])
  headingTextCase: # default = as typed - options: uppercase, lowercase, capitalize
  subheadingText: <ul><li>Подберем вам препцентр в стране назначения, если лимиты не позволяют вам доставить товар сразу на фулфилменты Амазон</li><li>Подготовим шипменты для доставки на Амазон и проконтролируем доставку товара по ним</li></ul>
  subheadingTextColor: # Leave empty to inherit headingTextColor or default (text-white) or use any text-[color]-[xxx]
  buttonText: Связаться с нами... # no button generated if left blank
  buttonURL: /#contact # full url required. Example: https://thisdomain.com/somepage/
  buttonTextColor: # leave blank to inherit from /src/_data/colors.buttonCustom or buttonDefault
  buttonBgColor: # leave blank to inherit from /src/_data/colors.buttonCustom.bg or buttonDefault.bg
  buttonBgHover: # leave blank to inherit from /src/_data/colors.buttonCustom.bgHover or buttonDefault.bgHover
  buttonBorder: # leave blank to inherit from /src/_data/colors.buttonCustom.border or buttonDefault.border
  carousel:
    images:
      - home/6.jpg
      - home/7.jpg
      - home/8.jpg
      - home/9.jpg
---
