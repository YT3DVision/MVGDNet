# MVGDNet: A Novel Motion-aware Video Glass Surface Detection Network (AAAI-2026)

## Abstract: 
Glass surface ubiquitous in both daily life and professional environments presents a potential threat to vision-based systems, such as robot and drone navigation. To solve this challenge, most recent studies have shown significant interest in Video Glass Surface Detection (VGSD). We observe that objects in the reflection (or transmission) layer appear farther from the glass surfaces. Consequently, in video motion scenarios, the notable reflected (or transmitted) objects on the glass surface move slower than objects in non-glass regions within the same spatial plane, and this motion inconsistency can effectively reveal the presence of glass surfaces. Based on this observation, we propose a novel network, named MVGD-Net, for detecting glass surfaces in videos by leveraging motion inconsistency cues. Our MVGD-Net features three novel modules: the Cross-scale Multimodal Fusion Module (CMFM) that integrates extracted spatial features and estimated optical flow maps, the History Guided Attention Module (HGAM) and Temporal Cross Attention Module (TCAM), both of which further enhances temporal features. A Temporal-Spatial Decoder (TSD) is also introduced to fuse the spatial and temporal features for generating the glass region mask. Furthermore, for learning our network, we also propose a large-scale dataset, which comprises 312 diverse glass scenarios with a total of 19,268 frames. Extensive experiments demonstrate that our MVGD-Net outperforms relevant state-of-the-art methods.


## Citation: 
Yiwei Lu, Hao Huang, Tao Yan*, "MVGDNet: A Novel Motion-aware Video Glass Surface Detection Network", Proc. AAAI 2026.

### TODO

Our paper is available at arXiv: <a href="https://doi.org/10.48550/arXiv.2601.13715">https://doi.org/10.48550/arXiv.2601.13715</a>.
We will release our code and dataset as soon as possible.

### pipeline
![MVGDNet](/fig/MVGDNet.png "MVGDNet")

### Results

**Quantitative Results**

![dingliang](/fig/quan_result.png)

**Qualitative Results on MVGD-D**

![MVGD-D](/fig/result_MVGD_D.png)

**Qualitative Results on MVGD-D**

![VGSD-D](/fig/result_VGSD_D.png)

## Acknowledgement

[RAFT](https://github.com/princeton-vl/RAFT)
