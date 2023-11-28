

<div align="left">
    <br>
    <img align="center" src="https://github.com/AI-team-UoA/pyJedAI/blob/main/docs/img/pyjedai.logo.drawio.png?raw=true" alt="pyJedAI" width="400"/>
   <br>
</div>
<br>
</div>

STELARs Open Source tool for Schema Matching and Entity Linking
---
A plethora of techniques has been proposed for Schema Matching, Entity Linking and Geospatial Interlinking. To facilitate their use by researchers and practitioners, in the context of Tasks 3.1 and 3.2, we developed pyJedAI, an open-source library that leverages Python’s data science ecosystem to build powerful end-to-end workflows for these tasks. We have publicly released the source code of pyJedAI at [https://github.com/AI-team-UoA/pyJedAI](https://github.com/AI-team-UoA/pyJedAI) under Apache License V2.0, which supports both academic and commercial applications. 

All releases from [0.0.2](https://github.com/AI-team-UoA/pyJedAI/releases/tag/v0.0.2) to [0.1.3](https://github.com/AI-team-UoA/pyJedAI/releases/tag/0.1.3) have been developed in the context of STELAR, following Deliverable Software Requirements.

__Website:__ A website has been created, providing documentation to STELARs partners and to the open-source community.

Link: [https://pyjedai.readthedocs.io](https://pyjedai.readthedocs.io/en/latest/intro.html)

# Schema Matching
- [Source code](https://github.com/AI-team-UoA/pyJedAI/tree/main/src/pyjedai/schema_matching.py)
- ADD [Tutorial]()

# Entity Linking

### [JedAIToolkit](https://github.com/scify/JedAIToolkit) re-implemented in pyJedAI
- [Source code](https://github.com/AI-team-UoA/pyJedAI/tree/main/src/pyjedai) 

### Join-based workflow
- [Source code](https://github.com/AI-team-UoA/pyJedAI/tree/main/src/pyjedai/joins.py)
- [Tutorial](https://pyjedai.readthedocs.io/en/latest/tutorials/SimilarityJoins.html)

### Blocking-based workflow
- Components source code:
    - [Block Building](https://github.com/AI-team-UoA/pyJedAI/tree/main/src/pyjedai/block_building.py)
    - [Block Cleaning](https://github.com/AI-team-UoA/pyJedAI/tree/main/src/pyjedai/block_cleaning.py)
    - [Comparison Cleaning](https://github.com/AI-team-UoA/pyJedAI/tree/main/src/pyjedai/comparison_cleaning.py)
    - [Entity Matching](https://github.com/AI-team-UoA/pyJedAI/blob/main/src/pyjedai/matching.py)
    - [Clustering](https://github.com/AI-team-UoA/pyJedAI/blob/main/src/pyjedai/clustering.py)

- Tutorials showing blocking based workflows:
    - [Clean Clean Entity Resolution](https://pyjedai.readthedocs.io/en/latest/tutorials/SimilarityJoins.html)
    - [Dirty Entity Resolution Tutorial](https://pyjedai.readthedocs.io/en/latest/tutorials/DirtyER.html)
    - [Clean Clean Entity Resolution for Naive Users](https://pyjedai.readthedocs.io/en/latest/tutorials/WorkFlow.html)
    - [Clean Clean Entity Resolution using TFIDF](https://pyjedai.readthedocs.io/en/latest/tutorials/TfIdfWorkflow.html)

### NN-based workflow
- [Source code](https://github.com/AI-team-UoA/pyJedAI/tree/main/src/pyjedai/vector_based_blocking.py)
- [Tutorial](https://pyjedai.readthedocs.io/en/latest/tutorials/pyTorchWorkflow.html)

### Progressive ER
- [Source code](https://github.com/AI-team-UoA/pyJedAI/tree/main/src/pyjedai/prioritization.py)
- ADD [Tutorial]()

# Geospatial Interlinking
