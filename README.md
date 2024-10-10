# Human Object Interaction
Human Object Interaction(HOI) tracking...
updated at 20240927

# Dataset
- HICO [paper] [code]
- HICO-DET [paper] [code]
- V-COCO [paper] [code]

# Survey
- Human object interaction detection: Design and survey
(Image and Vision Computing-2023, by Maya Antoun @ American University of Beirut) [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0262885622002463)

# Two-stage Methods
Consist of object dection (first stage) and interaction prediction (sencond stage). Extract various features like apparence, spatial, pose and semantic features.

Pros: Flexiable architecture, diverse feature combination 

Cons: Computationally expensive, prone to overfitting, lack of context

# One-stage Methods
Detecting human-object pairs and interaction simultaneously using two parallel branches. Capture contextual information from an early stage.

Pros: Simpler, faster, more efficient, solve sample imbalance

Cons: Need complex post-processing, difficulty in feature unification

# End-to-End Methods
Detect human-object pairs and interaction without post-processing.

Pros: Full context, no need for hand-designed regions

Cons: Require large amount of data


# LLM based Methods
- Boosting Human-Object Interaction Detection with Text-to-Image Diffusion Model
(arXiv-2023, by Jie Yang @ 香港中文大学) [[paper]](https://arxiv.org/pdf/2305.12252)
- RAM++：Open-Set Image Tagging with Multi-Grained Text Supervision
(arXiv-2023, by Xinyu Huang @ 上海复旦大学)[[paper]](https://arxiv.org/pdf/2310.15200)[[code]](https://github.com/xinyu1205/recognize-anything)

# Result
