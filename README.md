# Diffusion Models In Recommendation Systems

A survey of diffusion models in recommendation systems.

![](images/taxonomy.png)

Detailed information can be found in our [survey paper](https://arxiv.org/pdf/2501.10548).

```Bibtex
@article{wei2025diffusion,
  title={Diffusion Models in Recommendation Systems: A Survey},
  author={Wei, Ting-Ruen and Fang, Yi},
  journal={arXiv preprint arXiv:2501.10548},
  year={2025}
}
```
## Table of Contents
- [Background in Diffusion Models](#background-in-diffusion-models)
- [Papers for Diffusion Models in Recsys](#papers-for-diffusion-models-in-recsys)
  -   [Collaborative Filtering](#collaborative-filtering)
      -  [Implicit Feedback](#implicit-feedback)
      -  [Explicit Ratings](#explicit-ratings)
      -  [Item Graph](#item-graph)
      -  [User Graph](#user-graph)
  -   [Sequential Recommendation](#sequential-recommendation)
      -  [Point-of-Interest](#point-of-interest)
      -  [Sequence as Diffusion Target and Guidance](#sequence-as-diffusion-target-and-guidance)
      -  [Sequence as Diffusion Target](#sequence-as-diffusion-target)
      -  [Sequence as Diffusion Guidance](#sequence-as-diffusion-guidance)
  -   [Multi-domain Recommendation](#multi-domain-recommendation)
      -  [Image Generation](#image-generation)
      -  [Text-to-Recommendation](#text-to-recommendation)
      -  [Multi-modal Attributes](#multi-modal-attributes)
      -  [Cross-domain](#cross-domain)
  -   [Responsible Recommendation](#responsible-recommendation)
      -  [Fairness](#fairness)
      -  [Accountability](#accountability)
      -  [Transparency](#transparency)
      -  [Out-of-Distribution](#out-of-distribution)

---

### Background in Diffusion Models
- [Deep Unsupervised Learning using Nonequilibrium Thermodynamics](https://arxiv.org/abs/1503.03585)
- [Generative Modeling by Estimating Gradients of the Data Distribution](https://arxiv.org/abs/1907.05600)
- [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)
- [Score-Based Generative Modeling through Stochastic Differential Equations](https://arxiv.org/abs/2011.13456)
- [Improved Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2102.09672)
- [Diffusion Models Beat GANs on Image Synthesis](https://arxiv.org/abs/2105.05233)
- [Classifier-Free Diffusion Guidance](https://arxiv.org/abs/2207.12598)
- [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)
- [Progressive Distillation for Fast Sampling of Diffusion Models](https://arxiv.org/abs/2202.00512)

---

### Papers for Diffusion Models in Recsys

### Collaborative Filtering

- #### **Implicit Feedback**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|Blurring-sharpening process models for collaborative filtering| SIGIR 2023 | <img width="1200" alt="image" src="images/implicit feedback/blurring-sharpening.png"> | [Link](https://arxiv.org/abs/2211.09324)|
|Incorporating Classifier-Free Guidance in Diffusion Model-Based Recommendation | Arxiv 2024 | <img width="800" alt="image" src="images/implicit feedback/incorporating.png"> | [Link](https://arxiv.org/abs/2409.10494)|
|Collaborative Filtering Based on Diffusion Models: Unveiling the Potential of High-Order Connectivity | SIGIR 2024 | <img width="800" alt="image" src="images/implicit feedback/collaborative.png"> | [Link](https://arxiv.org/abs/2404.14240)|
|Recommendation via collaborative diffusion generative model | KSEM 2022 | <img width="300" alt="image" src="images/implicit feedback/recommendation.png"> | [Link](https://link.springer.com/chapter/10.1007/978-3-031-10989-8_47)|
|Denoising diffusion recommender model | SIGIR 2024 | <img width="800" alt="image" src="images/implicit feedback/denoising.png"> | [Link](https://arxiv.org/abs/2401.06982)|
|A Directional Diffusion Graph Transformer for Recommendation | Arxiv 2024 | <img width="800" alt="image" src="images/implicit feedback/A.png"> | [Link](https://arxiv.org/abs/2404.03326)|
|Diffusion recommender model | SIGIR 2023 | <img width="800" alt="image" src="images/implicit feedback/diffusion.png"> | [Link](https://arxiv.org/abs/2304.04971)|
|Recfusion: A binomial diffusion process for 1d data for recommendation | Arxiv 2023 | <img width="800" alt="image" src="images/implicit feedback/recfusion.png"> | [Link](https://arxiv.org/abs/2306.08947)|
|SCONE: A Novel Stochastic Sampling to Generate Contrastive Views and Hard Negative Samples for Recommendation | WSDM 2025 | <img width="800" alt="image" src="images/implicit feedback/stochastic.png"> | [Link](https://arxiv.org/abs/2405.00287)|
|Effects of Using Synthetic Data on Deep Recommender Models' Performance | Arxiv 2024 | <img width="800" alt="image" src="images/implicit feedback/effects.png"> | [Link](https://arxiv.org/abs/2406.18286)|
|GDDRec: graph neural diffusion model for diversified recommendation | KIS 2025 | <img width="800" alt="image" src="images/implicit feedback/gddrec.png"> | [Link](https://link.springer.com/article/10.1007/s10115-025-02348-y)|
|Collaborative Diffusion Model for Recommender System | WWW 2025 | <img width="800" alt="image" src="images/implicit feedback/collaborative-diffusion.png"> | [Link](https://arxiv.org/abs/2501.18997)|
|Hyperbolic Diffusion Recommender Model | WWW 2025 | <img width="800" alt="image" src="images/implicit feedback/hyperbolic.png"> | [Link](https://arxiv.org/abs/2504.01541)|
|Conditional diffusion model for recommender systems | NN 2025 | <img width="800" alt="image" src="images/implicit feedback/conditional.png"> | [Link](https://www.sciencedirect.com/science/article/pii/S0893608025000838)|
|Generative Recommendation with Continuous-Token Diffusion | Arxiv 2025 | <img width="800" alt="image" src="images/implicit feedback/generative.png"> | [Link](https://arxiv.org/abs/2504.12007)|
|Diffusion Model as a Base for Cold Item Recommendation | Applied Sciences 2025 | <img width="800" alt="image" src="images/implicit feedback/diffusion-model.png"> | [Link](https://www.mdpi.com/2076-3417/15/9/4784)|
|Diff-GNDCRec: A diffusion model with graph-node enhancement and difference comparison for recommendation | IPM 2025 | <img width="800" alt="image" src="images/implicit feedback/diff-gndcrec.png"> | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0306457325000950?dgcid=rss_sd_all)|
|A Diffusion Model with User Preference Guidance for Recommendation | DASFAA 2024 | <img width="800" alt="image" src="images/implicit feedback/a-diffusion.png"> | [Link](https://link.springer.com/chapter/10.1007/978-981-97-5555-4_15)|
|Graph-based Diffusion Model for Collaborative Filtering | Arxiv 2025 | <img width="800" alt="image" src="images/implicit feedback/graph-based.png"> | [Link](https://arxiv.org/abs/2504.05029)|
|DiffGCL: Diffusion model-based Graph Contrastive Learning for Service Recommendation | ICWS 2024 | <img width="800" alt="image" src="images/implicit feedback/diffgcl.png"> | [Link](https://ieeexplore.ieee.org/document/10707576)|
|Divide-and-Conquer: Cold-Start Bundle Recommendation via Mixture of Diffusion Experts | Arxiv 2025 | <img width="800" alt="image" src="images/implicit feedback/divide.png"> | [Link](https://arxiv.org/abs/2505.05035)|
|DiffGraph: Heterogeneous Graph Diffusion Model | WSDM 2025 | <img width="800" alt="image" src="images/implicit feedback/diffgraph.png"> | [Link](https://arxiv.org/abs/2501.02313)|
|Diffusion-driven SpatioTemporal Graph KANsformer for Medical Examination Recommendation | Arxiv 2025 | <img width="800" alt="image" src="images/implicit feedback/diffusion-driven.png"> | [Link](https://arxiv.org/abs/2505.07431)|
|DiffGR: A Discrete Diffusion-Based Model for Personalised Recommendation by Reconstructing User-Item Bipartite Graphs | ECIR 2025 | <img width="800" alt="image" src="images/implicit feedback/diffgr.png"> | [Link](https://link.springer.com/chapter/10.1007/978-3-031-88714-7_23)|
|GGDHSCL: A Graph Generative Diffusion With Hard Negative Sampling Contrastive Learning Recommendation Method | TCSS 2025 | <img width="800" alt="image" src="images/implicit feedback/ggdhscl.png"> | [Link](https://ieeexplore.ieee.org/document/10904007)|
|Personalized Diffusion Model Reshapes Cold-Start Bundle Recommendation | WWW 2025 | <img width="800" alt="image" src="images/implicit feedback/personalized.png"> | [Link](https://arxiv.org/abs/2505.14901)|
|Addressing Cold-Start Problem in Click-Through Rate Prediction via Supervised Diffusion Modeling | AAAI 2025 | <img width="800" alt="image" src="images/implicit feedback/addressing.png"> | [Link](https://arxiv.org/abs/2504.06270)|

- #### **Explicit Ratings**
  
|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|DGRM: Diffusion-GAN recommendation model to alleviate the mode collapse problem in sparse environments | Pattern Recognition 2024 | <img width="1600" alt="image" src="images/explicit rating/DGRM.png"> | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0031320324004436)|
|EDGE-Rec: Efficient and Data-Guided Edge Diffusion For Recommender Systems Graphs | Arxiv 2024 | <img width="300" alt="image" src="images/explicit rating/EDGE-Rec.png">| [Link](https://arxiv.org/abs/2409.14689)|

- #### **Item Graph**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|DICES: Diffusion-Based Contrastive Learning with Knowledge Graphs for Recommendation | KSEM 2024 |<img width="800" alt="image" src="images/item graph/DICES.png"> | [Link](https://link.springer.com/chapter/10.1007/978-981-97-5495-3_9)|
|Diffkg: Knowledge graph diffusion model for recommendation | WSDM 2024 | <img width="300" alt="image" src="images/item graph/Diffkg.png">| [Link](https://arxiv.org/abs/2312.16890)|
|G-Diff: A Graph-Based Decoding Network for Diffusion Recommender Model | TNNLS 2024 | <img width="800" alt="image" src="images/item graph/G-Diff.png"> | [Link](https://ieeexplore.ieee.org/document/10750895)|
|Graph Signal Diffusion Model for Collaborative Filtering | SIGIR 2024 | <img width="800" alt="image" src="images/item graph/Graph.png">| [Link](https://arxiv.org/abs/2311.08744)|
|Disentangled Contrastive Bundle Recommendation with Conditional Diffusion | AAAI 2025 | <img width="800" alt="image" src="images/item graph/disentangled.png">| [Link](https://ojs.aaai.org/index.php/AAAI/article/view/33314)|
|RsDiff: Rational Score baesd Knowledge Graph Diffusion for Recommendation | Info Sci 2025 | <img width="800" alt="image" src="images/item graph/rsdiff.png">| [Link](https://www.sciencedirect.com/science/article/abs/pii/S0020025525004244)|

- #### **User Graph**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|Diffusion social augmentation for social recommendation | Supercomputing 2025 | <img width="1200" alt="image" src="images/user graph/Diffusion.png">| [Link](https://link.springer.com/article/10.1007/s11227-024-06695-5)|
|Recdiff: diffusion model for social recommendation | CIKM 2024 | <img width="1200" alt="image" src="images/user graph/Recdiff.png">| [Link](https://arxiv.org/abs/2406.01629)|
|Score-based generative diffusion models for social recommendations | Arvix 2024 | <img width="1200" alt="image" src="images/user graph/score-based.png">| [Link](https://arxiv.org/abs/2412.15579)|
|Graph diffusive self-supervised learning for social recommendation | SIGIR 2024 | <img width="1200" alt="image" src="images/user graph/graph.png">| [Link](https://dl.acm.org/doi/10.1145/3626772.3657962)|
|Dual Graph Denoising Model for Social Recommendation | WWW 2025 | <img width="1200" alt="image" src="images/user graph/dual.png">| [Link](https://dl.acm.org/doi/10.1145/3696410.3714874)|
|Model-Agnostic Social Network Refinement with Diffusion Models for Robust Social Recommendation | WWW 2025 | <img width="1200" alt="image" src="images/user graph/model-agnostic.png">| [Link](https://dl.acm.org/doi/10.1145/3696410.3714683)|

---

### Sequential Recommendation

- #### **Point-of-interest**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|Diffusion-based cloud-edge-device collaborative learning for next POI recommendations | KDD 2024 |<img width="1200" alt="image" src="images/POI/Diffusion-based.png">| [Link](https://arxiv.org/abs/2405.13811)|
|Diff-DGMN: A Diffusion-Based Dual Graph Multi-Attention Network for POI Recommendation | IoT 2024 |<img width="1200" alt="image" src="images/POI/Diff-DGMN.png">| [Link](https://ieeexplore.ieee.org/document/10640103)|
|A diffusion model for poi recommendation | TOIS 2023 |<img width="1200" alt="image" src="images/POI/A.png">| [Link](https://arxiv.org/abs/2304.07041)|
|DSDRec: Next POI recommendation using deep semantic extraction and diffusion model | Info Sci 2024 |<img width="1200" alt="image" src="images/POI/DSDRec.png">| [Link](https://www.sciencedirect.com/science/article/abs/pii/S0020025524009186)|
|HGDRec: Next poi recommendation based on hypergraph neural network and diffusion model | TSC 2025 |<img width="1200" alt="image" src="images/POI/hgdrec.png">| [Link](https://ieeexplore.ieee.org/abstract/document/10969795)|

- #### **Sequence as Diffusion Target and Guidance**
  
|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|Context Matters: Enhancing Sequential Recommendation with Context-aware Diffusion-based Contrastive Learning | CIKM 2024 |<img width="1200" alt="image" src="images/target and guidance/Diffusion-based.png">| [Link](https://arxiv.org/abs/2405.09369)|
|Dual Conditional Diffusion Models for Sequential Recommendation | Arxiv 2024 |<img width="1200" alt="image" src="images/target and guidance/Dual.png">| [Link](https://arxiv.org/abs/2410.21967)|
|Semantic-Aware Diffusion Model for Sequential Recommendation | Open Review 2024 |<img width="1200" alt="image" src="images/target and guidance/Semantic-aware.png">| [Link](https://openreview.net/forum?id=2E6OK8cSoB)|
|Diffusion Model for Interest Refinement in Multi-Interest Recommendation | Arxiv 2025 |<img width="1200" alt="image" src="images/target and guidance/Dual.png">| [Link](https://arxiv.org/abs/2502.05561)|
|Unlocking the Power of Diffusion Models in Sequential Recommendation: A Simple and Effective Approach | Arxiv 2025 |<img width="1200" alt="image" src="images/target and guidance/unlocking.png">| [Link](https://arxiv.org/abs/2505.19544)|
|Enhancing Sequential Recommendation with Global Diffusion | AAAI 2025 |<img width="1200" alt="image" src="images/target and guidance/enhancing.png">| [Link](https://ojs.aaai.org/index.php/AAAI/article/view/33341)|
|Intent-aware Diffusion with Contrastive Learning for Sequential Recommendation | SIGIR 2025 |<img width="1200" alt="image" src="images/target and guidance/intent-aware.png">| [Link](https://arxiv.org/abs/2504.16077)|
|Diffusion augmentation for sequential recommendation | CIKM 2023 |<img width="1200" alt="image" src="images/target/Diffusion.png">| [Link](https://arxiv.org/abs/2309.12858)|

- #### **Sequence as Diffusion Target**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|Discrete conditional diffusion for reranking in recommendation | WWW 2024 |<img width="1200" alt="image" src="images/target/Discrete.png">| [Link](https://dl.acm.org/doi/10.1145/3589335.3648313)|
|Breaking Determinism: Fuzzy Modeling of Sequential Recommendation Using Discrete State Space Diffusion Model | NeurIPS 2024 |<img width="1200" alt="image" src="images/target/Breaking.png">| [Link](https://arxiv.org/abs/2410.23994)|
|A Diffusion Data Enhancement Retentive Model for Sequential Recommendation | CISAT 2024 |<img width="1200" alt="image" src="images/target/A.png">| [Link](https://ieeexplore.ieee.org/abstract/document/10695308)|
|Diff4rec: Sequential recommendation with curriculum-scheduled diffusion augmentation | MM 2023 |<img width="1200" alt="image" src="images/target/Diff4rec.png">| [Link](https://dl.acm.org/doi/10.1145/3581783.3612709)|
|Multi-Interest Network with Simple Diffusion for Multi-Behavior Sequential Recommendation | SDM 2024 |<img width="1200" alt="image" src="images/target/Multi-interest.png">| [Link](https://epubs.siam.org/doi/10.1137/1.9781611978032.84)|
|Plug-in diffusion model for sequential recommendation | AAAI 2024 |<img width="1200" alt="image" src="images/target/Plug-in.png">| [Link](https://arxiv.org/abs/2401.02913)|
|SeeDRec: Sememe-based Diffusion for Sequential Recommendation | IJCAI 2024 |<img width="1200" alt="image" src="images/target/SeeDRec.png">| [Link](https://www.ijcai.org/proceedings/2024/251)|
|Bridging User Dynamics: Transforming Sequential Recommendations with Schr{\"o}dinger Bridge and Diffusion Models | CIKM 2024 |<img width="1200" alt="image" src="images/target/Bridging.png">| [Link](https://arxiv.org/abs/2409.10522)|
|Context-Aware Diffusion-based Sequential Recommendation | BigData 2024 |<img width="1200" alt="image" src="images/target/context-aware.png">| [Link](https://ieeexplore.ieee.org/document/10826051)|
|DiffGCA: A Diffusion Recommendation Model with Global Attention Mechanism | DSIT 2025 |<img width="1200" alt="image" src="images/target/diffgca.png">| [Link](https://ieeexplore.ieee.org/document/10880988)|
|When Feature Encoder Meets Diffusion Model for Sequential Recommendations | Info Sci 2025 |<img width="1200" alt="image" src="images/target/when.png">| [Link](https://www.sciencedirect.com/science/article/abs/pii/S0020025525000350)|
|EDiffuRec: An Enhanced Diffusion Model for Sequential Recommendation | Mathematics 2024 |<img width="1200" alt="image" src="images/guidance/EDiffurec.png">| [Link](https://www.mdpi.com/2227-7390/12/12/1795)|

- #### **Sequence as Diffusion Guidance**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|Conditional denoising diffusion for sequential recommendation | PAKDD 2024 |<img width="1200" alt="image" src="images/guidance/Conditional.png">| [Link](https://arxiv.org/abs/2304.11433)|
|Sequential recommendation with diffusion models | Arxiv 2023 |<img width="1200" alt="image" src="images/guidance/Sequential.png">| [Link](https://arxiv.org/abs/2304.04541)|
|Diffusion Recommendation with Implicit Sequence Influence | WWW 2024 |<img width="1200" alt="image" src="images/guidance/Diffusion.png">| [Link](https://dl.acm.org/doi/10.1145/3589335.3651951)|
|Diffurec: A diffusion model for sequential recommendation | TOIS 2023 |<img width="1200" alt="image" src="images/guidance/Diffurec.png">| [Link](https://dl.acm.org/doi/10.1145/3631116)|
|DimeRec: A Unified Framework for Enhanced Sequential Recommendation via Generative Diffusion Models | WSDM 2025 |<img width="1200" alt="image" src="images/guidance/Dimerec.png">| [Link](https://arxiv.org/abs/2408.12153)|
|Generate what you prefer: Reshaping sequential recommendation via guided diffusion | NeurIPS 2024 |<img width="300" alt="image" src="images/guidance/Generate.png">| [Link](https://arxiv.org/abs/2310.20453)|
|Generate and Instantiate What You Prefer: Text-Guided Diffusion for Sequential Recommendation | Arxiv 2024 |<img width="1200" alt="image" src="images/guidance/Instantiate.png">| [Link](https://arxiv.org/abs/2410.13428)|
|Implicit local--global feature extraction for diffusion sequence recommendation | EAAI 2025 |<img width="1200" alt="image" src="images/guidance/Implicit.png">| [Link](https://www.sciencedirect.com/science/article/abs/pii/S0952197624016294)|
|LeadRec: Towards Personalized Sequential Recommendation via Guided Diffusion | ICIC 2024 |<img width="1200" alt="image" src="images/guidance/Leadrec.png">| [Link](https://link.springer.com/chapter/10.1007/978-981-97-5618-6_1)|
|Preference Diffusion for Recommendation | Arxiv 2024 |<img width="1200" alt="image" src="images/guidance/Preference.png">| [Link](https://arxiv.org/abs/2410.13117)|
|Generative Diffusion Models for Sequential Recommendations | Recsys 2024 |<img width="1200" alt="image" src="images/guidance/generative.png">| [Link](https://arxiv.org/abs/2410.19429)|
|Learning Multiple User Distributions for Recommendation via Guided Conditional Diffusion | AAAI 2025 |<img width="1200" alt="image" src="images/guidance/learning.png">| [Link](https://ojs.aaai.org/index.php/AAAI/article/view/33401)|
|Unleashing the Potential of Two-Tower Models: Diffusion-Based Cross-Interaction for Large-Scale Matching | WWW 2025 |<img width="1200" alt="image" src="images/guidance/unleashing.png">| [Link](https://arxiv.org/abs/2502.20687)|
|Distinguished quantized guidance for diffusion-based sequence recommendation | WWW 2025 |<img width="1200" alt="image" src="images/guidance/distinguished.png">| [Link](https://arxiv.org/abs/2501.17670)|
|Addressing Missing Data Issue for Diffusion-based Recommendation | Arxiv 2025 |<img width="1200" alt="image" src="images/guidance/addressing.png">| [Link](https://arxiv.org/abs/2505.12283)|
|Enhancing Diffusion Model with Auxiliary Information Mining-Exploration and Efficient Sampling Mechanism for Sequential Recommendation | AAAI 2025 |<img width="1200" alt="image" src="images/guidance/enhancing.png">| [Link](https://ojs.aaai.org/index.php/AAAI/article/view/33370)|

---

### Multi-domain Recommendation

- #### **Image Generation**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|AdBooster: Personalized Ad Creative Generation using Stable Diffusion Outpainting | Recsys 2023 |<img width="1200" alt="image" src="images/image generation/Adbooster.png">| [Link](https://arxiv.org/abs/2309.11507)|
|A New Creative Generation Pipeline for Click-Through Rate with Stable Diffusion Model | WWW 2024 |<img width="1200" alt="image" src="images/image generation/A.png">| [Link](https://arxiv.org/abs/2401.10934)|
|Dynamic Product Image Generation and Recommendation at Scale for Personalized E-commerce | Recsys 2024 |<img width="200" alt="image" src="images/image generation/Dynamic.png">| [Link](https://arxiv.org/abs/2408.12392)|
|Diffusion Models for Generative Outfit Recommendation | SIGIR 2024 |<img width="1200" alt="image" src="images/image generation/Diffusion.png">| [Link](https://arxiv.org/abs/2402.17279)|
|GEMRec: Towards Generative Model Recommendation | WSDM 2024 |<img width="1200" alt="image" src="images/image generation/GEMRec.png">| [Link](https://arxiv.org/abs/2308.02205)|
|Recommendations Beyond Catalogs: Diffusion Models for Personalized Generation | Arxiv 2025 |<img width="1200" alt="image" src="images/image generation/recommendations.png">| [Link](https://arxiv.org/abs/2502.18477)|

- #### **Text-to-recommendation**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|Diffusion Model for Slate Recommendation | Arxiv 2024 |<img width="500" alt="image" src="images/text to rec/Diffusion.png">| [Link](https://arxiv.org/abs/2408.06883)|

- #### **Multi-modal Attributes**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|DiffMM: Multi-Modal Diffusion Model for Recommendation | MM 2024 |<img width="1200" alt="image" src="images/multi-modal/Diffmm.png">| [Link](https://arxiv.org/abs/2406.11781)|
|LD4MRec: Simplifying and Powering Diffusion Model for Multimedia Recommendation | Arxiv 2023 |<img width="1200" alt="image" src="images/multi-modal/LD4mrec.png">| [Link](https://arxiv.org/abs/2309.15363)|
|Multimodal Conditioned Diffusion Model for Recommendation | WWW 2024 |<img width="1200" alt="image" src="images/multi-modal/Multimodal.png">| [Link](https://dl.acm.org/doi/10.1145/3589335.3651956)|
|Diffusion Review-Based Recommendation | KSEM 2024 |<img width="1200" alt="image" src="images/multi-modal/Diffusion.png">| [Link](https://link.springer.com/chapter/10.1007/978-981-97-5489-2_23)|
|DiffCL: A Diffusion-Based Contrastive Learning Framework with Semantic Alignment for Multimodal Recommendations | Arxiv 2025 |<img width="1200" alt="image" src="images/multi-modal/diffcl.png">| [Link](https://arxiv.org/abs/2501.01066)|
|Curriculum Conditioned Diffusion for Multimodal Recommendation | AAAI 2025 |<img width="1200" alt="image" src="images/multi-modal/curriculum.png">| [Link](https://ojs.aaai.org/index.php/AAAI/article/view/33422)|
|DiffKD: collaborative graph diffusion with knowledge distillation for multimodal recommendation | JIIS 2025 |<img width="1200" alt="image" src="images/multi-modal/diffkd.png">| [Link](https://arxiv.org/abs/2406.11781)|

- #### **Cross-domain**
  
|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|Diffusion Cross-domain Recommendation | Arxiv 2024 |<img width="1200" alt="image" src="images/cross-domain/Diffusion.png">| [Link](https://arxiv.org/abs/2402.02182)|
|Diff-MSR: A Diffusion Model Enhanced Paradigm for Cold-Start Multi-Scenario Recommendation | WSDM 2024 |<img width="250" alt="image" src="images/cross-domain/Diff-msr.png">| [Link](https://dl.acm.org/doi/10.1145/3616855.3635807)|
|Exploring Preference-Guided Diffusion Model for Cross-Domain Recommendation | KDD 2025 |<img width="1200" alt="image" src="images/cross-domain/exploring.png">| [Link](https://arxiv.org/abs/2501.11671)|

---

### Responsible Recommendation

- #### **Fairness**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|Balancing User Preferences by Social Networks: A Condition-Guided Social Recommendation Model for Mitigating Popularity Bias | NN 2025 |<img width="1200" alt="image" src="images/fairness/Balancing.png">| [Link](https://arxiv.org/abs/2405.16772)|
|Controlling Diversity at Inference: Guiding Diffusion Recommender Models with Targeted Category Preferences | Arxiv 2024 |<img width="1200" alt="image" src="images/fairness/Controlling.png">| [Link](https://arxiv.org/abs/2411.11240)|
|Guided Diffusion-based Counterfactual Augmentation for Robust Session-based Recommendation | Arxiv 2024 |<img width="250" alt="image" src="images/fairness/Guided.png">| [Link](https://arxiv.org/abs/2410.21892)|
|DifFaiRec: Generative Fair Recommender with Conditional Diffusion Model | Arxiv 2024 |<img width="1200" alt="image" src="images/fairness/Diffairec.png">| [Link](https://arxiv.org/abs/2410.02791)|
|How Fair is Your Diffusion Recommender Model? | Arxiv 2024 |<img width="1200" alt="image" src="images/fairness/How.png">| [Link](https://arxiv.org/abs/2409.04339)|

- #### **Accountability**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|Manipulating Visually Aware Federated Recommender Systems and Its Countermeasures | TOIS 2023 |<img width="1200" alt="image" src="images/accountability/Manipulating.png">| [Link](https://dl.acm.org/doi/10.1145/3630005)|
|Adversarial Item Promotion on Visually-Aware Recommender Systems by Guided Diffusion | TOIS 2024 |<img width="1200" alt="image" src="images/accountability/Adversarial.png">| [Link](https://dl.acm.org/doi/10.1145/3666088)|
|Generating Model Parameters for Controlling: Parameter Diffusion for Controllable Multi-Task Recommendation | Arxiv 2024 |<img width="1200" alt="image" src="images/accountability/Generating.png">| [Link](https://arxiv.org/abs/2410.10639)|
|Multi-Resolution Diffusion for Privacy-Sensitive Recommender Systems | Access 2024 |<img width="1200" alt="image" src="images/accountability/Multi-resolution.png">| [Link](https://arxiv.org/abs/2311.03488)|
|ToDA: Target-oriented Diffusion Attacker against Recommendation System | Arxiv 2024 |<img width="1200" alt="image" src="images/accountability/ToDA.png">| [Link](https://arxiv.org/abs/2401.12578)|
|Federated Recommender System Based on Diffusion Augmentation and Guided Denoising | TOIS 2024 |<img width="1200" alt="image" src="images/target/Federated.png">| [Link](https://dl.acm.org/doi/10.1145/3688570)|
|Latent diffusion model-based data poisoning attack against QoS-aware cloud API recommender system | Computer Networks 2025 |<img width="1200" alt="image" src="images/accountability/latent.png">| [Link](https://www.sciencedirect.com/science/article/abs/pii/S138912862500088X)|
|FedDiffRec: A Module-wise Training Approach for Diffusion-Based Recommendation in Federated Learning | ICASSP 2025 |<img width="1200" alt="image" src="images/accountability/feddiffrec.png">| [Link](https://ieeexplore.ieee.org/document/10889647)|
|An Adversarial Model with Diffusion for Robust Recommendation against Shilling Attack| SAC 2025 |<img width="1200" alt="image" src="images/accountability/an.png">| [Link](https://dl.acm.org/doi/10.1145/3672608.3707821)|

-  #### **Transparency**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|An Explainable Recommendation Method based on Diffusion Model | BigDIA 2023 |<img width="1200" alt="image" src="images/transparency/An.png">| [Link](https://ieeexplore.ieee.org/document/10429319)|

- #### **Out-of-distribution**

|Title | Venue | Main Image | Paper|
| :--- | :--: | :---: | :---: |
|Graph Representation Learning via Causal Diffusion for Out-of-Distribution Recommendation | WWW 2025 |<img width="1200" alt="image" src="images/out of distribution/Graph.png">| [Link](https://arxiv.org/abs/2408.00490)|
|Distributionally robust graph out-of-distribution recommendation via diffusion model | WWW 2025 |<img width="1200" alt="image" src="images/out of distribution/distributionally.png">| [Link](https://arxiv.org/abs/2501.15555)|
