# Carbon Efficient Karpenter (Master’s Thesis)
[Carbon_Efficient_Karpenter.pdf](Carbon_Efficient_Karpenter.pdf)

## Abstract
Data centers are responsible for 0.6% of global greenhouse gas emissions. To reduce these emissions, existing research focus mostly on carbon-aware scheduling and scaling of short-running workloads. This thesis introduces a novel method called carbon efficient cluster autoscaling to reduce operational and embodied carbon emissions from all workloads on cloud-based Kubernetes clusters. A carbon efficient cluster autoscaler for Kubernetes is developed by adapting Karpenter, an open-source state-of-the-art cluster autoscaler, to minimize cloud instance carbon emission estimates from BoaviztAPI. The developed Carbon Efficient Karpenter shows a statistically significant median reduction in cloud instance carbon emissions when compared to the original Karpenter. In locations where electricity has low, moderate, and high carbon intensity, the 25th/75th percentile reductions are 26%/45%, 7%/32%, and 4%/5%, respectively. This suggests that carbon efficient cluster autoscaling is a viable method for reducing the carbon footprint of Kubernetes clusters that run on cloud infrastructure. Widespread adoption could incentivize carbon emission optimizations throughout the cloud computing supply chain. An array of research questions emerge from these findings.

## Software
The software in this master’s thesis is available in two Git repositories at the _thesis_ tag:
- https://github.com/JacobValdemar/carbon-efficient-karpenter/tree/thesis
- https://github.com/JacobValdemar/carbon-efficient-karpenter-utilities/tree/thesis

## Sharing
Please share a link to this repository instead of sharing the pdf directly.

## Citing
If you use this master’s thesis in your work, please cite it using the following entry.

```bib
@thesis{andreasenCarbonEfficientKarpenter2024,
  title = {Carbon {{Efficient Karpenter}}: {{Optimizing Kubernetes Cluster Autoscaling}} for {{Carbon Efficiency}}},
  shorttitle = {Carbon {{Efficient Karpenter}}},
  author = {Andreasen, Jacob Valdemar},
  date = {2024-01-03},
  institution = {{Aarhus University}},
  location = {{Aarhus, Denmark}},
  langid = {english},
  language = {en},
  url = {https://github.com/JacobValdemar/carbon-efficient-karpenter-thesis}
}
```
> J. V. Andreasen, “Carbon Efficient Karpenter: Optimizing Kubernetes Cluster Autoscaling for Carbon Efficiency,” Aarhus University, Aarhus, Denmark, Jan. 3, 2024. [Online]. Available: https://github.com/JacobValdemar/carbon-efficient-karpenter-thesis
