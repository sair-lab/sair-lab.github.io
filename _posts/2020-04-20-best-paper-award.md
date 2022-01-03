---
layout: page
title: Best Paper Award
subtitle: "International Conference on Advanced Robotics (ICAR)"
categories: highlights
author: "Chen Wang"
published: true
permalink: /best-icar/
image: /img/posts/highlights/ni-slam.gif
datatable: true
hero_height: is-small
title_image: None
link-new-tab: true
show_sidebar: true
hide_footer: false
---

Paper titled "Non-iterative SLAM" received the best paper award in robotic planning from the International Conference on Advanced Robotics (ICAR).

<figure>
    <img src="/img/posts/highlights/ni-slam-laptop.gif" />
    <figcaption>
        Real-time dense mapping on a laptop.
    </figcaption>
</figure>

Existing SLAM methods often require iterative solutions to find data association.
For example, they require gradient descent algorithm to perform bundle adjustment, require RANSAC and ICP to match two point clouds.
However, all of them are computational expensive or sensitive to initialization.

To solve this problem, we develop **Non-iterative SLAM**, which has a non-iterative solution.
It is the first RGB-D-Inertial SLAM method that has a closed-from solution only with a complexity of O(N log N).

Because of this, it is very computationally efficient. We can even perform real-time dense mapping on a credit card sized computing board.

<figure>
    <img src="/img/posts/highlights/ni-slam-real-time.gif" />
    <img src="/img/posts/highlights/credit-card-board.png" />
    <figcaption>
        Live demo on a credit card sized computing board. No post-processing required.
    </figcaption>
</figure>

To the best of our knowledge, it was the world’s first real-time dense mapping demo on such a small computer.
It can provide centimeter level accuracy with an onboard low power processor on a flying robot.

<figure>
    <img src="/img/posts/highlights/ni-slam.gif" />
    <figcaption>
        Real-time trajectory estimation on a flying robot.
    </figcaption>
</figure>

The closed-form solution is based on our **kernel cross-correlator** (KCC), which is published in AAAI 2017.
KCC is robust to noises, thus the trajectory estimation is also smoother than other methods.

<figure>
    <img src="/img/posts/highlights/ground-robot.png" width="40%"/> 
    <img src="/img/posts/highlights/ni-slam-ground.gif" width="55%"/>
    <figcaption>
        Robot Localization only with Ground Textures.<br>
        The QR code is for calculating the drift error instead of localization.
    </figcaption>
</figure>

We also applied it to warehouse robots for high-precision localization only with ground textures.
In the tests, it only produces 0.1% to 0.5% drift error if no loop closure is given.

Theoretically, the closed-form solution is based on our paper titled "Kernel Cross-Correlator", which has a closed-form solution in frequency domain. For more detailed information, please refer to our papers.

### Related Papers

Paper: [Non-iterative SLAM](https://arxiv.org/pdf/1701.05294)

Paper: [Non-iterative RGB-D-inertial Odometry](https://arxiv.org/abs/1710.05502)

Paper: [Kernel Cross-Correlator](https://arxiv.org/abs/1709.05936)

### Citation

    @inproceedings{wang2017non,
     title={Non-iterative SLAM},
     author={Wang, Chen and Yuan, Junsong and Xie, Lihua},
     booktitle={International Conference on Advanced Robotics (ICAR)},
     pages={83--90},
     year={2017},
     organization={IEEE},
    }

    @article{wang2017noniterative,
     title={Non-iterative RGB-D-inertial Odometry},
     author={Wang, Chen and Hoang, Minh-Chung and Xie, Lihua and Yuan, Junsong},
     journal={arXiv preprint arXiv:1710.05502},
     year={2017},
    }

    @inproceedings{wang2018kernel,
     title={Kernel Cross-Correlator},
     author={Wang, Chen and Zhang, Le and Xie, Lihua and Yuan, Junsong},
     booktitle={Thirty-Second AAAI Conference on Artificial Intelligence (AAAI)},
     pages={4179--4186},
     year={2018},
    }
