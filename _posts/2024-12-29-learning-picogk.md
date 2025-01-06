---
title: Computational Engineering with PicoGK (part 1)
description: Starting my journey with PicoGK
author: eero
date: 2024-12-29 22:36:00 +0200
updated: 2025-01-02 21:44:00 +0200
categories: [Computational Engineering]
tags: [C#, CEM, engineering, PicoGK]
pin: true
math: true
mermaid: true
image:
  path: /assets/img/post_images/picogkpost.jpeg
  lqip: 
  alt: 
---

## Introduction
As I have gained more knowledge in Additive Manufacturing (AM) also known as Industrial 3D-printing, I have seen the advantages that it can offer. With AM, there is more freedom of design. AM technologies can produce geometries that conventional manufacturing methods can not. In short, parts can be more complex, more lighter and with embedded functionalities to reduce separate parts requiring assembly.

However, the geometries that you can make are hard to design with traditional CAD-programs. CAD-design is quite repetitive and manual and while parametric designs are possible to create, they can break quite easily. Traditional CAD uses boundary representations and meshes to define the models, which are not adequate for advanced manufacturing and generative design. This is why tools such as [nTop][ntop] and PicoGK exist. In this post series I will focus on learning C# programming and using **PicoGK**.

## PicoGK
[PicoGK][picogk-github] ('peacock') is an open-source geometry kernel developed by [LEAP 71][leap-71]. PicoGK is the foundation for creating Computational Engineering Models (CEMs). It is written in C# and the performance critical parts are written in C++.

>Computational Engineering is a new paradigm where the entire process of designing a product is encoded into an algorithm
{: .prompt-info }

## Coding for Engineers
[Coding for Engineers][coding-for-engineers] is a book published by Lin Kayser from LEAP71. The book is currently an ongoing project and Lin publishes new content one chapter at a time. Follow Lin on his [LinkedIn][linn-kayser-linkedin] to know when new chapters are released.

The book is a programming course for engineers to start the paradigm shift from old visual tools like CAD to [Computational Engineering][computational-engineering].

What I love about the book is that Lin teaches fundamental programming concepts better than most of the coding tutorials out there. There is also the exciting aspect of creating new 3D-designs in a completely new way and seeing the power of computational engineering in practice.


### Chapters 1-7
Chapters from 1 to 7 cover programming concepts to get the necessary knowledge before using PicoGK. The topics cover object-oriented programming topics such as information hiding, polymorphism and inheritance.




------------
[picogk-github]: https://github.com/leap71/PicoGK/tree/main
[coding-for-engineers]: https://picogk.org/coding-for-engineers/TOC.html
[linn-kayser-linkedin]: https://www.linkedin.com/in/linkayser/recent-activity/all/
[leap-71]: https://leap71.com/
[computational-engineering]: https://leap71.com/computationalengineering/
[ntop]: https://www.ntop.com/
[picogk]: https://picogk.org/
