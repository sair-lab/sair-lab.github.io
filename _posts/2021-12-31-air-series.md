---
layout: page
title: Air Series Articles Prereleased
# subtitle: "Air Series is a collection of articles in robotics mentored by Dr. Chen Wang in 2021."
categories: highlights
author: "Chen Wang"
published: true
permalink: /airseries/
image: /img/posts/2021-12-31-air-series/AirDet-16x9.gif
datatable: true
hero_height: is-small
title_image: None
link-new-tab: true
show_sidebar: true
hide_footer: false
---

**Air Series** is a collection of **five articles mentored by Chen Wang** in the year of 2021.

All articles are **first authored by Undergraduate or Master students** and **second authored by Chen Wang**.

A wide variety of topics in **robotics** are covered, including **localization**, **detection**, and **lifelong learning**.

<style>
.csl-block {
    font-size: 16px;
}
.csl-title, .csl-author, .csl-event, .csl-editor, .csl-venue {
    display: block;
    position: relative;
    font-size: 15px;
}

.csl-title b {
    font-weight: 600;
}

.csl-content {
    display: inline-block;
    vertical-align: top;
    padding-left: 20px;
}

.bibliography {
   list-style-type: none;
}
</style>


## Air Series Articles

{% bibliography --query @*[keywords=airseries] %}


### Contribution


* **AirDet: Few-shot Detection without Fine-tunning**

   * The first practical few-shot object detection method that requires no fine-tunning.
   * It achieves even better results than the exhaustively fine-tuned methods (up to 60% improvements).
   * Validated on real world sequences from DARPA Subterranean (SubT) challenge.

<figure>
    <img src="/img/posts/2021-12-31-air-series/AirDet.gif" />
    <figcaption>
        Only three examples are given for novel object detection without fine-tunning.
    </figcaption>
</figure>

* **AirObject: Temporal Object Embedding**

   * The first temporal object embedding method.
   * It achieves the state-of-the-art performance for video object identification.
   * Robust to severe occlusion, perceptual aliasing, viewpoint shift, deformation, and scale transform.

<figure>
    <img src="/img/posts/2021-12-31-air-series/AirObject.gif" />
    <figcaption>
        Temporal object matching on videos.
    </figcaption>
</figure>

* **AirDOS: Dynamic Object-aware SLAM (DOS) system**

   * The first DOS system showing that camera pose estimation can be improved by incorporating dynamic articulated objects.
   * Establish 4-D dynamic object maps.

<figure>
    <img src="/img/posts/2021-12-31-air-series/AirDOS.gif" />
    <figcaption>
        Dynamic Objects can correct the camera pose estimation.
    </figcaption>
</figure>

* **AirLoop: Lifelong learning for Robots**

   * The first lifelong learning method for loop closure detection.
   * Model incremental improvement even after deployment.

<figure>
    <img src="/img/posts/2021-09-28-airloop/tartanair-ll.gif" />
    <figcaption>
        The model is able to correct previously made mistakes after learning more environments.
    </figcaption>
</figure>

* **AirCode: Robust Object Encoding**

   * The first deep point-based object encoding.
   * It achieves the state-of-the-art performance for video object identification.
   * Robust to severe occlusion, perceptual aliasing, viewpoint shift, deformation, and scale transform.

<figure>
    <img src="/img/posts/2021-10-06-aircode/object-matching1.gif" />
    <img src="/img/posts/2021-10-06-aircode/object-matching2.gif" />
    <figcaption>
        A human matching demo.
    </figcaption>
</figure>

More information can be found at the [research page](/research). Some project pages will be released soon.

### First Author Information (When the work was done)

* [Bowen Li](https://jaraxxus-me.github.io/)
   * RISS intern at Carnegie Mellon University.
   * Third year undergraduate at Tongji University, China.

* [Nikhil Varma Keetha](https://www.linkedin.com/in/nikhil-varma-keetha-612685193/)
   * RISS intern at Carnegie Mellon University.
   * Third year undergraduate at Indian Institute of Techonology Dhanbad.

* [Dasong Gao](https://scholar.google.com/citations?user=_loctXsAAAAJ&hl=en)
   * Master student of Machine Learning at Carnegie Mellon University.

* [Yuheng Qiu](https://scholar.google.com/citations?user=aEK45mEAAAAJ)
   * Undergraduate of Chinese University of Hong Kong.
   * Research Associate (Now: PhD student) at Carnegie Mellon University.

* Kuan Xu
   * Master Graduate of Harbin Institute of Technology, China.
   * Engineer at Tencent and Geekplus.

Congratulations to the above young researchers!