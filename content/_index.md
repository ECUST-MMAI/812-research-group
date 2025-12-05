---
# Leave the homepage title empty to use the site title
title: Welcome 欢迎
date: 2023-11-20
type: landing

sections:
  - block: hero
    content:
      title: |
        ECUST-MMAI
        Lab Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        The ECUST-MMAI Lab Group is led by Professor Yu Zhu. Our team is committed to the research of artificial intellegence, advanced deep learning algorithms, computer vision, and multimedia applications. Including Medical Imaging, Autonomous Driving, Deepfake, Image Superresolution, NERF, Expression Recognition and etc..

        华东理工大学-多模态人工智能课题组由朱煜教授领导。我们致力于人工智能、先进深度学习算法、计算机视觉以及多媒体应用的研究，包括医学影像、自动驾驶、深度伪造、图像超分辨率、NERF、表情识别等领域。

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
          filename: A_finalpic01.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
