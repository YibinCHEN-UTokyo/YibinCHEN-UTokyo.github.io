## Final Report

In this report, two papers will be discussed on its significance: _A survey on Vision Transformer_ (TPAMI), and _Structured Bird’s-Eye-View Traffic Scene Understanding from Onboard Images_ (ICCV).

---

### _A survey on Vision Transformer_

This survey provides an extensive review of Vision Transformer, covering its historical development, principles and mathematical formulation, applications in multiple domains, and current challenges and future prospects. Additionally, it underlines the significance of Vision Transformer by highlighting their advantages over traditional Convolutional Neural Networks, which are popular utilized for image and video processing.

The importance of this survey lies in its comprehensive overview of the advancements and challenges of Vision Transformers, and explicit mathematical formulation of the pure transformer and its variants. Detailed theoretical analysis and experimental validation in this survey can be a solid foundation for investigators’ learning and discussion, and systematic review on the techniques may provide valuable insights for further research and applications. Therefore, this survey made a unique contribution and was worthy of publication in top journals.

### _Structured Bird’s-Eye-View Traffic Scene Understanding from Onboard Images_

Researches on traffic scene understanding primarily focused on generating high-definition maps, combined with a modular perception stack. Its traditional solutions usually relied heavily on multiple sensors, which made them effective but costly and geographically restrictive. Conversely, this paper proposed a method for recovering the topological structure of the road network in Bird’s-Eye-View (BEV) with a single front-facing camera image.

Briefly, this paper introduced a transformer-based neural network that predicts a complete lane graph structure and detects traffic participant in BEV. 

The method represents the road network as a directed graph whose edges denote road centerlines with traffic flow. Each road segment is modeled using Bezier curves and the connectivity is determined utilizing a transformer. The proposed method includes common traffic participant detection as well. The method allows for downstream tasks, such as trajectory planning and navigation.

According to the paper, the proposed method achieves superior performance, specifically precision-recall and connectivity scores, in lane graph estimation compared to existing ones. However, it has some limitations. For instance, the precision-recall metrics suggest the omission of some centerlines, which affects the overall detection ratio. Additionally, the complexity of urban traffic scenes remains a significant factor of accuracy.

This paper is fairly significant since it introduces a scalable and cost-effective solution for traffic scene understanding. By leveraging a single onboard camera, the method reduces dependency on multiple sensors and explicit maps prepared in advance, making autonomous driving more accessible. Moreover, the innovative utilization of a transformer-based architecture for joint lane graph and object detection in BEV is so practical and works well that it has the potential to be integrated into autonomous driving systems. From my perspective, this paper is substantial enough to earn its acceptance.
