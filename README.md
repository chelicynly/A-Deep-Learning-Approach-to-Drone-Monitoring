
## A Deep Learning Approach to Drone Monitoring
### [[paper]](https://arxiv.org/abs/1712.00863)
#### Yueru Chen, Ye Wang, Pranav Aggarwal, Jongmoo Choi, and C.-C. Jay Kuo
## Overview of the system
![overview](https://user-images.githubusercontent.com/16787952/33512269-7ee320c2-d6e1-11e7-93be-76891c575726.png)
## Abstract
A drone monitoring system that integrates deep-learning-based detection
and tracking modules is proposed in this work.  The biggest challenge in
adopting deep learning methods for drone detection is the limited amount
of training drone images. To address this issue, we develop a
model-based drone augmentation technique that automatically generates
drone images with a bounding box label on drone's location.  To track a
small flying drone, we utilize the residual information between
consecutive image frames. Finally, we present an integrated detection
and tracking system that outperforms the performance of each individual
module containing detection or tracking only. The experiments show that,
even being trained on synthetic data, the proposed system performs well
on real world drone images with complex background. The USC drone
detection and tracking dataset with user labeled bounding boxes is
available to the public.
## Dataset
### [[online drone dataset]](https://drive.google.com/open?id=1rWfiT8kXloUK5sdWYLyeGLSNus0f73iR)
![onlinedrone](https://user-images.githubusercontent.com/16787952/33512265-6bd137da-d6e1-11e7-85d8-0a98929a3260.png)
### [[usc drone dataset]](https://drive.google.com/open?id=1JzKESVGtS9VX80XL-D3DuUmcWE0doeJg)
![uscdrone](https://user-images.githubusercontent.com/16787952/33512268-7b189684-d6e1-11e7-9868-91e3b8299ed5.png)
### [[thermal usc drone dataset]](https://drive.google.com/open?id=1jsdmOvXqtB6e9H-02CqnKUaOH33kNigV)
![thermal-drone](https://user-images.githubusercontent.com/16787952/33532395-33908bf0-d84e-11e7-8ffb-6a48ed5bde52.png)
## Acknowledgments
This research is supported by a grant from the Pratt & Whitney
Institute of Collaborative Engineering (PWICE). 
