---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Research Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
- title: Recognition of Fabric Structure Parameters Based on Deep Neural Networks
  # company: GenCoin
  # company_url: ''
  # company_logo: org-gc
  location: Jiangnan University
  date_start: '2019-01-01'
  date_end: '2021-03-01'
  description: |2-
      A graduate project granted under the Postgraduate Research & Practice Innovation of Jiangsu Province 1062050205206039. 
      
      The project adopted a wireless device and established a fabric images dataset with elaborated structure parameters. Presented a multi-task and multi-scale convolutional neural network (MTMSnet) to recognize the fabric density, weaving pattern, reaching under 2% and 10% error respectively.
      
      The project is called <a href="https://www.jntex.cn" target="_blank">"织识"</a>， which is now online. Some of the source can be found in my <a href="https://github.com/breeeak/MTMSnet-initial/tree/master/MTMSnet-dev" target="_blank">"Github"</a>

- title: Fabric Defect Detection Based on Deep Neural Networks
  # company: GenCoin
  # company_url: ''
  # company_logo: org-gc
  location: Jiangnan University
  date_start: '2019-01-01'
  date_end: '2021-03-01'
  description: |2-
      A project came from the competition of <a href="https://tianchi.aliyun.com/competition/entrance/231666/information" target="_blank">Tianchi 2019 Guangdong Intelligent Identification of Cloth Defects</a>.
      
      Proposed a two-stage strategy to do local defect prediction and global defect recognition by using the Inception-VI model and LeNet-5 model, reaching 93.2% accuracy based on our cropped dataset.

- title: Objective Evaluation of Fabric Smoothness Based on Deep Neural Networks
  # company: GenCoin
  # company_url: ''
  # company_logo: org-gc
  location: Jiangnan University
  date_start: '2019-01-01'
  date_end: '2021-03-01'
  description: |2-
      The decoloration problem was solved by a paired image-to-image translation model built by conditional generative adversarial networks (GAN), which is also promising for fabric defect detection and other problems.
      
      An ordinal classification framework based on label noise estimation (OCF-LNE) to objectively evaluate the fabric smoothness appearance degree. In this project, I helped to establish the dataset and the paper can be found in <a href="https://doi.org/10.1109/ACCESS.2019.2959705" target="_blank">https://doi.org/10.1109/ACCESS.2019.2959705</a>


- title: Fabric Images Style Transfer Based on Deep Neural Networks
  # company: GenCoin
  # company_url: ''
  # company_logo: org-gc
  location: Jiangnan University
  date_start: '2019-01-01'
  date_end: '2021-03-01'
  description: |2-
      A genetic algorithm (GA) and A style-generative adversarial networks (StyleGAN) based method was adopted to realize the color transfer of colored spun yarned fabrics. The effect of the fabric images style transfer can be found in my <a href="https://github.com/breeeak/FabricStyleTransfer" target="_blank">GitHub</a>

- title: Development of ERP System in Textile Production Enterprises
  # company: GenCoin
  # company_url: ''
  # company_logo: org-gc
  location: Jiangnan University
  date_start: '2019-01-01'
  date_end: '2021-03-01'
  description: |2-
    A graduate project which was a web-based production management system specially designed for textile production enterprises, which also involved data-collecting devices based on Arduino to monitor weaving process in real-time. 
    
    Responsible for the back-end and front-end development and the thesis “Development of APS Software for Scheduling of Multi-varieties Weaving Production” won the “Excellent Theses of Jiangnan University”. 
    
    The source code can be found in my <a href="https://github.com/breeeak/jnERP" target="_blank">GitHub</a>. A demo project can be found in <a href="http://www.jntex.cn:88/" target="_blank">http://www.jntex.cn:88/</a>


design:
  columns: '2'
---
