---
title: "Joint Attention, Computer Vision, Foundation Models: How state-of-the-art AI approaches can analyze instances of early childhood development"
collection: talks
permalink: /publication/joint_attention.md
excerpt: 'In this work, we develop a pipeline that identifies instances of joint attention by using three different computer vision models, Constrative Language-Image Pre-training (CLIP), a 2D joint attention detector, and a monocular depth estimation model, to reconstruct the 3D coordinates of the caregiver, child, and object of focus.'
date: 2023-05-01
venue: 'IHD Flash Talks'
paperurl: 'https://github.com/raymondEDS/JA3DTriangle/blob/master/Documents/Paper.pdf'

---
The Filming Interactions to Nurture Development (FIND) program uses video coaching to promote positive interactions between caregivers and children. One important interaction in early childhood development is joint attention where both caregiver and the child focus on a single object. In this work, we develop a pipeline that identifies instances of joint attention by using three different computer vision models, Constrative Language-Image Pre-training (CLIP), a 2D joint attention detector, and a monocular depth estimation model, to reconstruct the 3D coordinates of the caregiver, child, and object of focus. Using the 3D coordinates we are able to calculate the area of a 3D triangle that represents the space between the three entities. Our analysis shows that in instances of shared reading the area of the triangle is less than in other playing activities where joint attention is present. Our work is innovative in achieving two goals: first, we provide quantitative evidence to gain new insights into caregiver-child interactions; second, we explore the potential of a novel computational method to improve video coding programs, such as reducing the time and resources required for manual coding. Future work will include creating a labeled dataset for model evaluation and refining the model pipeline.

[Download paper here](https://github.com/raymondEDS/JA3DTriangle/blob/master/Documents/Paper.pdf)

[Paper Github Repo](https://github.com/raymondEDS/JA3DTriangle/tree/master)

