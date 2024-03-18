# VE-ELIN

MultiModal Summarization (MMS) aims to generate a concise summary based on multimodal data like texts and images and has wide application in multimodal fields.
Previous works mainly focus on the coarse-level textual and visual features in which the overall features of the image interact with the whole sentence.
However, the entities of the input text and the objects of the image may be underutilized, limiting the performance of current MMS models.
In this paper, we propose a novel Visual Enhanced Entity-Level Interaction Network (VE-ELIN) to address the problem of underutilization of multimodal inputs at a fine-grained level in two ways.
We first design a cross-modal entity interaction module to better fuse the entity information in text and the object information in vision.
Then, we design an object-guided visual enhancement module to fully extract the visual features and enhance the focus of the image on the object area.
We evaluate VE-ELIN on two MMS datasets and propose new metrics to measure the factual consistency of entities in the output.
Finally, experimental results demonstrate that VE-ELIN is effective and outperforms previous methods under both traditional metrics and ours.
