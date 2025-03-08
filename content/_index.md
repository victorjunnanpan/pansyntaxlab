---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Pan's Syntax Lab
    
      image:
        filename: teamphoto.jpg
      text: |
        <br>
        
        The **Pan's Syntax Lab** is a research team led by Prof Victor Junnan Pan based at the Department of Linguistics and Modern Languages, The Chinese University of Hong Kong. Our team mainly focuses on generative syntax, especially, the Minimalist Program. We also work on heritage language, language contact, minority and endangered languages (Sino-Tibetan), and, psycho and neurolinguistics under the formal syntactic theoretical framework. / 香港中文大學語言學及現代語言系潘俊楠教授帶領的句法團隊致力於生成句法學，尤其是最簡方案, 繼承語和語言接觸、少數民族語言和瀕危語言以及理論語言學框架下的心理和神經語言學等領域的研究。/ L’équipe de recherche dirigée par le professeur Victor Junnan Pan au sein du Département de Linguistique et de Langues Modernes à l'Université Chinoise de Hong Kong travaille sur la syntaxe générative, notamment, le Programme Minimaliste, les langues d’héritage, le contact linguistique, les langues minoritaires et en danger (sino-tibétaines), et, la psycho et la neurolinguistique dans le cadre théorique de la syntaxe formelle.

  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
