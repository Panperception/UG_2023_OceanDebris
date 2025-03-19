## Marine Debris Detection in Satellite Surveillance Using Attention Mechanisms

### Abstract
Marine debris poses a critical threat to environmental ecosystems, necessitating effective methods for its detection and localization. This study addresses the existing limitations in the literature by proposing an innovative approach that combines the instance segmentation capabilities of YOLOv7 with various attention mechanisms to enhance efficiency and broaden applicability. The primary contribution lies in the exploration and comparison of three attentional models: lightweight coordinate attention, combining spatial and channel focus (CBAM), and bottleneck transformer based on self-attention. Leveraging a meticulously labeled dataset of satellite images containing ocean debris, the study conducts a comprehensive assessment of box detection and mask evaluation. The results demonstrate that CBAM emerges as the standout performer, achieving the highest F1 score (77%) in box detection, surpassing coordinate attention (71%) and YOLOv7/bottleneck transformer (both around 66%). In mask evaluation, CBAM continues to lead with an F1 score of 73%, while coordinate attention and YOLOv7 exhibit comparable performances (around F1 scores of 68% and 69%), and bottleneck transformer lags behind at an F1 score of 56%. This compelling evidence underscores CBAM's superior suitability for detecting marine debris compared to existing methods. Notably, the study reveals an intriguing aspect of the bottleneck transformer, which, despite lower overall performance, successfully detected areas overlooked by manual annotation. Moreover, it demonstrated enhanced mask precision for larger debris pieces, hinting at potentially superior practical performance in certain scenarios. This nuanced finding underscores the importance of considering specific application requirements when selecting a detection model, as the bottleneck transformer may offer unique advantages in certain contexts.

A. Shen, Y. Zhu, P. Angelov and R. Jiang, "Marine Debris Detection in Satellite Surveillance Using Attention Mechanisms," in IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, vol. 17, pp. 4320-4330, 2024, doi: 10.1109/JSTARS.2024.3349489. 
https://ieeexplore.ieee.org/abstract/document/10379646
