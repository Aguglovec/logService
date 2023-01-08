---
title: test0
sectionID: unique_id_4
permalink: false
date: 2020-09-24
excerpt: Not yet native in 11ty, creating draft posts is easy.
author: shane-robinson
draft: false
eleventyNavigation: # Required if want to display in Main Nav Bar
  key: main # "main" is required
  title: Возмещения # as it will appear in the nav
  order: 4 # order to display in the nav (index = 1)
  url: reimbursement
  local: true  
seo:
  title:
  description:
  image: 2020/09/draft.png
images: # relative to /src/assets/images/
  feature:
  thumb: 2020/09/draft.png
  align: # object-center (default) - other options at https://tailwindcss.com/docs/object-position
  height: # optional. Default = h-48 md:h-1/3
tags:
  - structure
  - customization
  - frontmatter
section: hero-split-section
sectionSettings:
  height:
    mobile: # options = h-1/1 (default = full screen), h-1/2, h-1/3, h-3/4, h-9/10, h-48 (12rem, 192px), h-56 (14rem, 224px), h-64 (16rem, 256px)
    desktop: # leave blank to inherit "mobile" height (default = full screen)
  bg:
    color: bg-neutral-400 # default bg-black
    image: home/warehouse3.jpg # relative to /assets/images/
    imagePosition: # options = bg-center (default), bg-left, bg-right
    video: forestfire.mp4 # local relative /assets/video/, or full https://... if remote?
    opacityMobile: opacity-50 # options opacity-n, 5, 10, 15, 20, 25, 50, 75, 100 (default)
    opacityDesktop: opacity-75 # Leave blank to inherit opacityMobile, use same options as opacityMobile
  headingText: Работа с возмещениями
  headingTextColor: text-black # default = text-white (can use any TailwindCSS text-[color]-[xxx])
  headingTextCase: # default = as typed - options: uppercase, lowercase, capitalize
  subheadingText: <ul><li>Сталкивались ли вы с проблемой потери товара на Амазоне во время приема или иных перемещений? </li><li>Мы проанализируем все отчеты по товарным поступлениям и найдем все пути товародвижения. </li><li>Организуем подачу кейсов на Амазон по возмещениям.</li></ul>
  subheadingTextColor: # Leave empty to inherit headingTextColor or default (text-white) or use any text-[color]-[xxx]
  buttonText: Связаться с нами... # no button generated if left blank
  buttonURL: /#contact # full url required. Example: https://thisdomain.com/somepage/
  buttonTextColor: # leave blank to inherit from /src/_data/colors.buttonCustom or buttonDefault
  buttonBgColor: # leave blank to inherit from /src/_data/colors.buttonCustom.bg or buttonDefault.bg
  buttonBgHover: bg-neutral-600 # leave blank to inherit from /src/_data/colors.buttonCustom.bgHover or buttonDefault.bgHover
  buttonBorder: # leave blank to inherit from /src/_data/colors.buttonCustom.border or buttonDefault.border
  carousel:
    images:
      - home/6.jpg
      - home/7.jpg
      - home/8.jpg
      - home/9.jpg
---
