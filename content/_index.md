---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Data Engineering and Semantics Research Unit
      image:
        filename: fss.jpg
      text: |
        <div style="text-align: justify">
        The <b>Data Engineering and Semantics Research Unit (UR21ES01)</b> was created in 2021 as a structure for the coordination and proliferation of research works about intelligent systems driven by knowledge resources. The Unit's mission is to develop computer applications for automating several tasks in multiple areas of interest.
        </div>

  - block: markdown
    content:
      title: The DES Office and Data Center
      text: |
        <div style="display: flex; justify-content: center;">
          {{< video src="VID1.mp4" controls="yes" >}} {{< video src="VID2.mp4" controls="yes" >}}
        </div>
      design:
        columns: '1'
        spacing:
          padding: ['20px', '0', '20px', '0']
        
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
      title: Partners
      subtitle: ''
      text: |
        ||
        :--:|:--:|:--:|:--:|:--:|:--:
        ![](/albums/partners/wikimedia.svg)  | ![](/albums/partners/virginia.png)| ![](/albums/partners/bern.png)| ![](/albums/partners/pretoria.png) | ![](/albums/partners/uned.jpg)| ![](/albums/partners/obuda.png)
        ![](/albums/partners/mir.jpg)| ![](/albums/partners/milan.jpg)| ![](/albums/partners/nui.jpg)| ![](/albums/partners/basque.png) | ![](/albums/partners/havre.png)| ![](/albums/partners/lis.png)
        ![](/albums/partners/world.png)  |![](/albums/partners/kaist.png)| ![](/albums/partners/minds.jpg)| ![](/albums/partners/UDE.svg)| ![](/albums/partners/fab.png)| ![](/albums/partners/tech.png)
        ![](/albums/partners/intel.png)  |![](/albums/partners/phoenix.jpg)| ![](/albums/partners/sifast.svg)| ![](/albums/partners/jumia.jpg)| ![](/albums/partners/spark.png)| ![](/albums/partners/inel.png)
        
        
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
