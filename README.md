# Mechanism-SMILES
We structured each data entry as an integrated triplet comprising mechanistic diagrams (e.g., electron-pushing arrow schematics), natural language descriptions of reaction steps, and standardized Mechanism SMILES representations, enabling multimodal benchmarks to assess both general and domain-specific large language models (LLMs). This design facilitates evaluation for multiple tasks, such as testing LLMs' mechanistic comprehension via natural language through bi-directional translation between natural language and Mechanism SMILES, as well as challenging multimodal LLMs through cross-modal tasks, such as generating Mechanism SMILES from reaction diagrams, among other tasks. An example of a data entry is as follow:

{
  "id": "3",
  "image_path": "images/image_3.png",
  "smiles": "[CH2:1]=[C:2]([CH3:3])[OH:4].[CH3:5][C+:6]([CH3:7])[OH:8] <--> {2,1-2,6}[CH3:3][C+:2]([OH:4])[CH2:1][C:6]([CH3:5])([CH3:7])[OH:8]",
  "description": "烯醇中的双键提供电子，进攻碳正离子，形成新的 C-C 键，同时碳正离子转移到烯醇的α-碳上，生成稳定的正离子中间体。"
}
