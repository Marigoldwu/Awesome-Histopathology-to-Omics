<h1 align="center">🧬 Awesome-Histopathology-to-Omics</h1>

<p align="center">
  <img src="https://awesome.re/badge.svg" alt="Awesome">
  <img src="https://img.shields.io/badge/UPDATE-2026--01--06-orange" alt="Update">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
</p>

## 🚀 Introduction

A curated collection of papers, codes, and resources for cross-modal translation/prediction/generation between histopathological imaging and omics (genomics, proteomics, etc.), including histopathology-to-mIF image generation, histopathology-to-genomic prediction, etc.

## 📋 Table of Contents

- [🔎 Survey/Review/Benchmark/Protocol Papers List](#-surveyreviewbenchmark-protocol-papers-list)
- [🔬 Research Papers List](#-research-papers-list)
  - [Hist to Genomics/Transcriptomics](#hist-to-genomicstranscriptomics)
  - [Hist to Proteomics](#hist-to-proteomics)
  - [Hist to Multi-omics](#hist-to-multi-omics)
  - [Hist to Cell](#hist-to-cell)
  - [Hist to Pathology](-hist-to-pathology)
- [🔗 Related Repositories](#-related-repositories)
- [❤️ Contributing](#-contributing)
- [⭐ Citation](#-citation)
- [📧 Contact](#-contact)

## 🔎 Survey/Review/Benchmark/Protocol Papers List
<details open>
<summary><b>&nbsp;2025 (6)</b></summary>
<ul>
    <li>
      [10-28] 【<b>Survey</b>】<i>Content Generation Models in Computational Pathology: A
Comprehensive Survey on Methods, Applications, and Challenges. <b>IEEE Rev Biomed Eng</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://oar.a-star.edu.sg/storage/o/ozokdvm7xw/content-generation-models-in-computational-pathology.pdf' target='_blank'>Article</a>
    </li>
    <li>
      [10-14] 【<b>Survey</b>】<i>Computer Vision Methods for Spatial Transcriptomics: A Survey. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/10.1101/2025.10.13.682148v1.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/hrlblab/computer_vision_spatial_omics' target='_blank'>Code</a>
    </li>
    <li>
      [09-09] 【<b>Data-quality Benchmark</b>】<i>Impact of Data Quality on Deep Learning Prediction of Spatial Transcriptomics from Histology Images. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/10.1101/2025.09.04.674228v1.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/calebhallinan/dataquality_geneprediction' target='_blank'>Code</a>
    </li>
    <li>
      [08-19] 【<b>SpaCKLE</b>】<i>Completing spatial transcriptomics data for gene expression prediction benchmarking. <b>MEDIA</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.sciencedirect.com/science/article/pii/S1361841525003019' target='_blank'>Article</a>
    </li>
    <li>
      [05-13] 【<b>Survey</b>】<i>Combining spatial transcriptomics with tissue morphology. <b>NAT COMMUN</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1038/s41467-025-58989-8' target='_blank'>Article</a>
    </li>
    <li>
      [02-11] 【<b>HEtoSGEBench</b>】<i>Benchmarking the translational potential of spatial gene expression prediction from histology. <b>NAT COMMUN</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41467-025-56618-y' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/SydneyBioX/HEtoSGEBench' target='_blank'>Code</a>
    </li>
</ul>
</details>

<details open>
<summary><b>&nbsp;2024 (2)</b></summary>
<ul>
    <li>
      [12-01] 【<b>Survey</b>】<i>Computational Methods for Breast Cancer Molecular Profiling through Routine Histopathology: A Review. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2412.10392' target='_blank'>Article</a>
    </li>
    <li>
      [09-16] 【<b>STAMP</b>】<i>From whole-slide image to biomarker prediction: end-to-end weakly supervised deep learning in computational pathology. <b>NAT PROTOC</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2412.10392' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/KatherLab/STAMP' target='_blank'>Code</a>
    </li>
</ul>
</details>

## 🔬 Research Papers List

### Hist to Genomics/Transcriptomics

<details open> <!--2025-->
  <summary><b>&nbsp;2025 (53)</b></summary>
  <ul>
    <li>
      [12-16] 【<b>SIGMMA</b>】<i>SIGMMA: Hierarchical Graph-Based Multi-Scale Multi-modal Contrastive Alignment of Histopathology Image and Spatial Transcriptome. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2511.15464' target='_blank'>Article</a>
    </li>
    <li>
      [12-14] 【<b>STPath</b>】<i>STPath: a generative foundation model for integrating spatial transcriptomics and whole-slide images. <b>NPJDM</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41746-025-02020-3' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Graph-and-Geometric-Learning/STPath' target='_blank'>Code</a>
    </li>
    <li>
      [12-07] 【<b>STRank </b>】<i>Learning Relative Gene Expression Trends from Pathology Images in Spatial Transcriptomics. <b>NeurIPS</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://openreview.net/pdf?id=X3zarVyJ5B' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/naivete5656/STRank' target='_blank'>Code</a>
    </li>
    <li>
      [12-06] 【<b>Gene-DML</b>】<i>Gene-DML: Dual-Pathway Multi-Level Discrimination for Gene Expression Prediction from Histopathology Images. <b>WACV</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2507.14670' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/YXSong000/Gene-DML' target='_blank'>Code</a>
    </li>
    <li>
      [12-03] 【<b>DenseGOAT</b>】<i>Aligning Histological Images and Spatial Gene Expression Jointly Through Densenet and Graph Ordering Attention Network. <b> CISP-BMEI</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://ieeexplore.ieee.org/abstract/document/11259187' target='_blank'>Article</a>
    </li>
    <li>
      [11-27] 【<b>HyperST</b>】<i>HyperST: Hierarchical Hyperbolic Learning for Spatial Transcriptomics Prediction. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2511.22107' target='_blank'>Article</a>
    </li>
    <li>
      [11-27] 【<b>MISO</b>】<i>A deep learning-based multiscale integration of spatial omics with tumor morphology. <b>NAT COMMUN</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41467-025-66691-y' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/owkin/miso_code' target='_blank'>Code</a>
    </li>
    <li>
      [11-25] 【<b>PixNet</b>】<i>From Spots to Pixels: Dense Spatial Gene Expression Prediction from Histology Images. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2503.01347' target='_blank'>Article</a>
    </li>
    <li>
      [11-21] 【<b>DKAN </b>】<i>Dual-Path Knowledge-Augmented Contrastive Alignment Network for Spatially Resolved Transcriptomics. <b>AAAI</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/abs/2511.17685' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/coffeeNtv/DKAN' target='_blank'>Code</a>
    </li>
    <li>
      [11-20] 【<b>SciSt</b>】<i>SciSt: single-cell reference-informed spatial gene expression prediction from pathological images. <b>BIB</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://academic.oup.com/bib/article/26/6/bbaf613/8329263' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/liyixin12139/SciSt' target='_blank'>Code</a>
    </li>
    <li>
      [11-16] 【<b>DomainST</b>】<i>Bridging imaging and genomics: Domain knowledge guided spatialtranscriptomics analysis. <b>IF</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.sciencedirect.com/science/article/pii/S1566253525008085' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/coffeeNtv/DomainST' target='_blank'>Code</a>
    </li>
    <li>
      [11-07] 【<b>Img2ST-Net</b>】<i>Img2ST-Net: efficient high-resolution spatial omics prediction from whole-slide histology images via fully convolutional image-to-image learning. <b>JMI</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1117/1.JMI.12.6.061410' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/hrlblab/Img2ST-Net' target='_blank'>Code</a>
    </li>
    <li>
      [10-13] 【<b>MMAP</b>】<i>MMAP: A Multi-Magnification and Prototype-Aware Architecture for Predicting Spatial Gene Expression. <b>PRICAI </b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2510.11344' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/pndh/MMAPattemp3' target='_blank'>Code</a>
    </li>
    <li>
      [10-08] 【<b>HisHRST</b>】<i>Geometry-informed multimodal fusion network for enhancing high-densityspatial transcriptomics from histology images. <b>EAAI</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1016/j.engappai.2025.112647' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/wenwenmin/HisHRST' target='_blank'>Code</a>
    </li>
    <li>
      [10-05] 【<b>GenAR</b>】<i>GenAR: Next-Scale Autoregressive Generation for Spatial Gene Expression Prediction. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2510.04315v1' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/oyjr/genar' target='_blank'>Code</a>
    </li>
    <li>
      [09-25] 【<b>DeepSpot2Cell</b>】<i>DeepSpot2Cell: Predicting Virtual Single-Cell Spatial Transcriptomics from H&E images using Spot-Level Supervision. <b>NeurIPS</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://openreview.net/forum?id=ofCkwXQKaz' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/ratschlab/DeepSpot' target='_blank'>Code</a>
    </li>
    <li>
      [09-21] 【<b>CoMTIP</b>】<i>LEARNING FROM GENE NAMES, EXPRESSION VALUES AND IMAGES: Contrastive Masked Text-Image Pretraining for Spatial Transcriptomics Representation Learning. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2509.16892?' target='_blank'>Article</a>
    </li>
    <li>
      [09-18] 【<b>NH²2ST</b>】<i>Spatially Gene Expression Prediction Using Dual-Scale Contrastive Learning. <b>MICCAI</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2506.23827?' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/MCPathology/NH2ST' target='_blank'>Code</a>
    </li>
    <li>
      [09-15] 【<b>iSCALE</b>】<i>Scaling up spatial transcriptomics for large-sized tissues: uncovering cellular-level tissue architecture beyond conventional platforms with iSCALE. <b>NAT Methods</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41592-025-02770-8' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/amesch441/iSCALE' target='_blank'>Code</a>
    <li>
      [09-15] 【<b>GHIST</b>】<i>Spatial gene expression at single-cell resolution from histology using deep learning with GHIST. <b>NM</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41592-025-02795-z.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/SydneyBioX/GHIST' target='_blank'>Code</a>
    </li>
    <li>
      [09-09] 【<b>FmH2ST</b>】<i>FmH2ST: foundation model-based spatial transcriptomics generation from histological images. <b>NAR</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://academic.oup.com/nar/article-pdf/53/17/gkaf865/64870080/gkaf865.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://www.sdu-idea.cn/codes.php?name=FmH2ST' target='_blank'>Code</a>
    </li>
    <li>
      [09-06] 【<b>SpaFoundation</b>】<i>A histology foundation model for high-resolution spatial omics prediction, tumor detection, and, clustering of spatial transcriptomics. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/biorxiv/early/2025/09/06/2025.08.07.669202.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/NingZhangCSUBio/SpaFoundation' target='_blank'>Code</a>
    </li>
    <li>
      [09-04] 【<b>stImage</b>】<i>stImage: a versatile framework for optimizing spatial transcriptomic analysis through customizable deep histology and location informed integration. <b>BIB</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1093/bib/bbaf429' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/YuWang-VUMC/stImage' target='_blank'>Code</a>
    </li>
    <li>
      [08-21] 【<b>SpatialFinder</b>】<i>SpatialFinder: A Human-in-the-Loop Vision-Language Framework for Prioritizing High-Value Regions in Spatial Transcriptomics. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/biorxiv/early/2025/08/21/2025.08.16.670684.full.pdf' target='_blank'>Article</a>
    </li>
    <li>
      [08-20] 【<b>DANet</b>】<i>DANet: spatial gene expression prediction from H&E histology images through dynamic alignment. <b>BIB</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1093/bib/bbaf422' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/202324131016T/DANet' target='_blank'>Code</a>
    </li>
    <li>
      [08-10] 【<b>HaDM-ST</b>】<i>HaDM-ST: Histology-Assisted Differential Modeling for Spatial Transcriptomics Generation. <b>CMMCA </b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2508.07225?' target='_blank'>Article</a>
    </li>
    <li>
      [07-22] 【<b>MVHybrid</b>】<i>MVHybrid: Hybrid State Space-Vision Transformer for Pathology Foundation Models. <b>MICCAI </b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2508.00383' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/deepnoid-ai/MVHybrid' target='_blank'>Code</a>
    </li>
    <li>
      [07-22] 【<b>GenST</b>】<i>GenST: A Generative Cross-Modal Model for Predicting Spatial Transcriptomics from Histology Images. <b>MICCAI</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://openreview.net/forum?id=LHVSSaCKL6' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/ox-ibme-bio-imaging/GenST-workshop-version' target='_blank'>Code</a>
    </li>
    <li>
      [07-20] 【<b>STimage </b>】<i>Robust and interpretable prediction of gene markers and cell types from spatial transcriptomics data. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/10.1101/2023.05.14.540710v2.full' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/BiomedicalMachineLearning/STimage' target='_blank'>Code</a>
    </li>
    <li>
      [07-18] 【<b>SpotWhisperer </b>】<i>Molecularly informed analysis of histopathology images using natural language. <b>ICML</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/10.1101/2025.07.14.664402v1.full.pdf' target='_blank'>Article</a>
    </li>
    <li>
      [07-08] 【<b>PAST</b>】<i>PAST: A multimodal single-cell foundation model for histopathology and spatial transcriptomics in cancer. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2507.06418' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Changchun-Yang/past_sc' target='_blank'>Code</a>
    </li>
    <li>
      [07-07] 【<b>SPATIA </b>】<i>SPATIA: Multimodal Model for Prediction and Generation of Spatial Cell Phenotypes. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2507.04704v1' target='_blank'>Article</a>
    </li>
    <li>
      [07-06] 【<b>Magic</b>】<i>Spatial histology and gene-expression representation and generative learning via online self-distillation contrastive learning. <b>BIB</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1093/bib/bbaf317' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/cat-moom/Magic' target='_blank'>Code</a>
    </li>
    <li>
      [07-04] 【<b>PathCLAST</b>】<i>PATHCLAST: PATHWAY-AUGMENTED CONTRASTIVELEARNING WITH ATTENTION FOR SPATIAL TRANSCRIPTOMICS. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/10.1101/2025.06.30.662247v1.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/sslim-aidrug/PathCLAST' target='_blank'>Code</a>
    </li>
    <li>
      [06-26] 【<b>HECLIP</b>】<i>HECLIP: histology-enhanced contrastive learning for imputation of transcriptomics profiles. <b>Bioinfo</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://academic.oup.com/bioinformatics/advance-article-abstract/doi/10.1093/bioinformatics/btaf363/8174905' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/QSong-github/HECLIP' target='_blank'>Code</a>
    </li>
    <li>
      [06-19] 【<b>CarHE </b>】<i>Predicting Spatial Transcriptomics from H&E Image by Pretrained Contrastive Alignment Learning. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/10.1101/2025.06.15.659438v1.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Jwzouchenlab/CarHE' target='_blank'>Code</a>
    </li>
    <li>
      [06-18] 【<b>Vispro</b>】<i>Vispro improves imaging analysis for Visium spatial transcriptomics. <b>GB</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://link.springer.com/article/10.1186/s13059-025-03648-w' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/HuifangZJU/Vispro' target='_blank'>Code</a>
    </li>
    <li>
      [06-17] 【<b>HistoTME-v2</b>】<i>Towards interpretable molecular and spatial analysis of the tumor microenvironment from digital histopathology images with HistoTME-v2. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/10.1101/2025.06.11.658673v1.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/spatkar94/HistoTME' target='_blank'>Code</a>
    </li>
    <li>
      [05-30] 【<b>M2TGLGO</b>】<i>Multi-modal Topology-embedded Graph Learning for Spatially Resolved Genes Prediction from Pathology Images with Prior Gene Similarity Information. <b>CVPR</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://openaccess.thecvf.com/content/CVPR2025/papers/Shi_Multi-modal_Topology-embedded_Graph_Learning_for_Spatially_Resolved_Genes_Prediction_from_CVPR_2025_paper.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/shihangjs/M2TGLGO' target='_blank'>Code</a>
    </li>
    <li>
      [05-29] 【<b>OmiCLIP</b>】<i>A visual–omics foundation model to bridge histopathology image with transcriptomics. <b>NM</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41592-025-02707-1' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/GuangyuWangLab2021/Loki' target='_blank'>Code</a>
    </li>
    <li>
      [05-25] 【<b>STFlow</b>】<i>Scalable Generation of Spatial Transcriptomics from Histology Images via Whole-Slide Flow Matching. <b>ICML</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2506.05361' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Graph-and-Geometric-Learning/STFlow' target='_blank'>Code</a>
    </li>
    <li>
      [04-23] 【<b>VRI</b>】<i>Histology-Based Virtual RNA Inference Identifies Pathways Associated with Metastasis Risk in Colorectal Cancer. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.medrxiv.org/content/10.1101/2025.04.22.25326170.abstract' target='_blank'>Article</a>
    </li>
    <li>
      [04-20] 【<b>PH2ST</b>】<i>PH2ST: Prompt-Guided Hypergraph Learning for Spatial Transcriptomics Prediction in Whole Slide Images. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2503.16816' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/NIUYI0511/PH2ST/' target='_blank'>Code</a>
    </li>
    <li>
      [04-11] 【<b>M2OST </b>】<i>M2OST: Many-to-one Regression for Predicting Spatial Transcriptomics from Digital Pathology Images. <b>AAAI</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://ojs.aaai.org/index.php/AAAI/article/view/32830' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Dootmaan/M2OST' target='_blank'>Code</a>
    </li>
    <li>
      [03-16] 【<b>Path2Omics</b>】<i>Path2Omics: Enhanced transcriptomic and methylation prediction accuracy from tumor histopathology. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/biorxiv/early/2025/03/16/2025.02.26.640189.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://doi.org/10.5281/zenodo.15016142' target='_blank'>Code</a>
    </li>
    <li>
      [03-13] 【<b>AGP-Net</b>】<i>AGP-Net: A Universal Network for Gene Expression Prediction of Spatial Transcriptomics. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/biorxiv/early/2025/03/13/2025.03.09.642276.full.pdf' target='_blank'>Article</a>
    </li>
    <li>
      [02-28] 【<b>MagNet</b>】<i>MagNet: Multi-Level Attention Graph Network for Predicting High-Resolution Spatial Transcriptomics. <b>MIDL</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2502.21011?' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Junchao-Zhu/MagNet' target='_blank'>Code</a>
    </li>
    <li>
      [02-22] 【<b>Path2Space</b>】<i>AI-Driven Spatial Transcriptomics Unlocks Large-Scale Breast Cancer Biomarker Discovery from Histopathology. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/biorxiv/early/2025/02/22/2024.10.16.618609.full.pdf' target='_blank'>Article</a>
    </li>
    <li>
      [02-09] 【<b>DeepSpot</b>】<i>DeepSpot: Leveraging Spatial Context for Enhanced Spatial Transcriptomics Prediction from H&E Images. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.medrxiv.org/content/10.1101/2025.02.09.25321567v1.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/ratschlab/DeepSpot' target='_blank'>Code</a>
    </li>
    <li>
      [01-26] 【<b>Stem</b>】<i>Diffusion Generative Modeling for Spatially Resolved Gene Expression Inference from Histology Images. <b>ICLR</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2501.15598v1' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/SichenZhu/Stem' target='_blank'>Code</a>
    </li>
    <li>
      [01-10] 【<b>BG-TRIPLEX</b>】<i>Boundary-Guided Learning for Gene Expression Prediction in Spatial Transcriptomics. <b>BIBM</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2412.04072?' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/WcloudC0416/BG-TRIPLEX' target='_blank'>Code</a>
    </li>
    <li>
      [01-10] 【<b>HisToSGE</b>】<i>High-Resolution Spatial Transcriptomics from Histology Images using HisToSGE. <b>BIBM</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2407.20518?' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/wenwenmin/HisToSGE' target='_blank'>Code</a>
    </li>
    <li>
      [01-06] 【<b>STMCL</b>】<i>Inferring multi-slice spatially resolved gene expression from H&E-stained histology images with STMCL. <b>Methods</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.sciencedirect.com/science/article/pii/S1046202324002834' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/wenwenmin/STMCL' target='_blank'>Code</a>
    </li>
  </ul>
</details>

<details open> <!--2024-->
  <summary><b>&nbsp;2024 (19)</b></summary>
  <ul>
    <li>
      [12-19] 【<b>HistoTME</b>】<i>Predicting the tumor microenvironment composition and immunotherapy response in non-small cell lung cancer from digital histopathology images. <b>NPJPO</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41698-024-00765-w.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/spatkar94/HistoTME' target='_blank'>Code</a>
    </li>
    <li>
      [12-17] 【<b>STFormer </b>】<i>STFormer: Learning to Explore Spot Relationships for Spatial Transcriptomics Prediction from Histology of Colorectal Cancer. <b>EMBC</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://ieeexplore.ieee.org/abstract/document/10782295' target='_blank'>Article</a>
    </li>
    <li>
      [12-03] 【<b>MERGE</b>】<i>MERGE: Multi-faceted Hierarchical Graph-based GNN for Gene Expression Prediction from Whole Slide Histopathology Images. <b>CVPR</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://openaccess.thecvf.com/content/CVPR2025/html/Ganguly_MERGE_Multi-faceted_Hierarchical_Graph-based_GNN_for_Gene_Expression_Prediction_from_CVPR_2025_paper.html' target='_blank'>Article</a>
    </li>
    <li>
      [11-27] 【<b>GeneQuery</b>】<i>GeneQuery: A General QA-based Framework for Spatial Gene Expression Predictions from Histology Images. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2411.18391?' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/xy-always/GeneQuery' target='_blank'>Code</a>
    </li>
    <li>
      [11-25] 【<b>ST-Align</b>】<i>ST-Align: A Multimodal Foundation Model for Image-Gene Alignment in Spatial Transcriptomics. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2411.16793' target='_blank'>Article</a>
    </li>
    <li>
      [11-15] 【<b>HistoSPACE</b>】<i>HistoSPACE: Histology-inspired spatial transcriptome prediction and characterization engine. <b>Methods</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1016/j.ymeth.2024.11.002' target='_blank'>Article</a>
    </li>
    <li>
      [11-14] 【<b>SEQUOIA </b>】<i>Digital profiling of gene expression from histology images with linearized attention. <b>NAT COMMUN</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41467-024-54182-5' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/gevaertlab/sequoia-pub' target='_blank'>Code</a>
    </li>
    <li>
      [11-08] 【<b>sCellST</b>】<i>sCellST: a Multiple Instance Learning approach to predict single-cell gene expression from H&E images using spatial transcriptomics. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/biorxiv/early/2024/11/08/2024.11.07.622225.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/loicchadoutaud/sCellST' target='_blank'>Code</a>
    </li>
    <li>
      [10-29] 【<b>mclSTExp</b>】<i>Multimodal contrastive learning for spatial gene expression prediction using histology images. <b>BIB</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1093/bib/bbae551' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/shizhiceng/mclSTExp' target='_blank'>Code</a>
    </li>
    <li>
      [10-14] 【<b>HGGEP</b>】<i>Gene expression prediction from histology images via hypergraph neural networks. <b>BIB</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1093/bib/bbae500' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/QSong-github/HGGEP' target='_blank'>Code</a>
    </li>
    <li>
      [09-26] 【<b>HEMIT</b>】<i>HEMIT: H&E to Multiplex-immunohistochemistry Image Translation with Dual-Branch Pix2pix Generator. <b>Bioinfo</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2403.18501' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/BianChang/HEMIT-DATASET' target='_blank'>Code</a>
    </li>
    <li>
      [09-04] 【<b>asGNN</b>】<i>Predicting spatially resolved gene expression via tissue morphology using adaptive spatial GNNs. <b>Bioinfo</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1093/bioinformatics/btae383' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/song0309/asGNN/' target='_blank'>Code</a>
    </li>
    <li>
      [08-09] 【<b>ResSAT </b>】<i>ResSAT: Enhancing Spatial Transcriptomics Prediction from H&E- Stained Histology Images with Interactive Spot Transformer. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.researchsquare.com/article/rs-4707959/v1' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Wonderangela/ResSAT' target='_blank'>Code</a>
    </li>
    <li>
      [07-03] 【<b>DeepPT</b>】<i>A deep-learning framework to predict cancer treatment response from histopathology images through imputed transcriptomics. <b>NCancer</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s43018-024-00793-2' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://doi.org/10.5281/zenodo.11125591' target='_blank'>Code</a>
    </li>
    <li>
      [06-22] 【<b>RedeHist </b>】<i>Spatial Transcriptomics Prediction from Histology Images at Single-cellResolution using RedeHist. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/10.1101/2024.06.17.599464v1.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Roshan1992/RedeFISH' target='_blank'>Code</a>
    </li>
    <li>
      [06-05] 【<b>HE2Gene</b>】<i>HE2Gene: image-to-RNA translation via multi-task learning for spatial transcriptomics data. <b>Bioinfo</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1093/bioinformatics/btae343' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Microbiods/HE2Gene' target='_blank'>Code</a>
    </li>
    <li>
      [04-25] 【<b>TRIPLEX</b>】<i>Accurate spatial gene expression prediction by integrating multi-resolution features. <b>CVPR</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://openaccess.thecvf.com/content/CVPR2024/papers/Chung_Accurate_Spatial_Gene_Expression_Prediction_by_Integrating_Multi-Resolution_Features_CVPR_2024_paper.pdf' target='_blank'>Article</a>
    </li>
    <li>
      [04-22] 【<b>STAGE</b>】<i>High-density generation of spatial transcriptomics withSTAGE. <b>NAR</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1093/nar/gkae294' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/zhanglabtools/STAGE' target='_blank'>Code</a>
    </li>
    <li>
      [01-02] 【<b>iStar</b>】<i>Inferring super-resolution tissue architecture by integrating spatial transcriptomics with histology. <b>NBiotech</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41587-023-02019-9' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/daviddaiweizhang/istar' target='_blank'>Code</a>
    </li>
  </ul>
</details>

<details open> <!--2023-->
  <summary><b>&nbsp;2023 (6)</b></summary>
  <ul>
    <li>
      [12-25] 【<b>THIToGene</b>】<i>THItoGene: a deep learning method for predicting spatial transcriptomics from histological images. <b>BIB</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://academic.oup.com/bib/article-pdf/25/1/bbad464/54826450/bbad464.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/yrjia1015/THItoGene' target='_blank'>Code</a>
    </li>
    <li>
      [11-25] 【<b>TCGN</b>】<i>Transformer with convolution and graph-node co-embedding: An accurate and interpretable vision backbone for predicting gene expressions from local histopathological image. <b>MEDIA</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.sciencedirect.com/science/article/pii/S1361841523003006' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/lugia-xiao/TCGN' target='_blank'>Code</a>
    </li>
    <li>
      [09-26] 【<b>EGGN </b>】<i>Spatial transcriptomics analysis of gene expression prediction using exemplar guided graph neural network. <b>PR</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.sciencedirect.com/science/article/pii/S0031320323006647' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Yan98/EGN' target='_blank'>Code</a>
    </li>
    <li>
      [09-22] 【<b>BLEEP </b>】<i>Spatially Resolved Gene Expression Prediction from H&E Histology Images via Bi-modal Contrastive Learning. <b>NeurIPS</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://proceedings.neurips.cc/paper_files/paper/2023/hash/df656d6ed77b565e8dcdfbf568aead0a-Abstract-Conference.html' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/bowang-lab/BLEEP' target='_blank'>Code</a>
    </li>
    <li>
      [09-02] 【<b>SEPAL</b>】<i>SEPAL: Spatial Gene Expression Prediction from Local Graphs. <b>ICCV</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://openaccess.thecvf.com/content/ICCV2023W/CVAMD/papers/Mejia_SEPAL_Spatial_Gene_Expression_Prediction_from_Local_Graphs_ICCVW_2023_paper.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/BCV-Uniandes/SEPAL' target='_blank'>Code</a>
    </li>
    <li>
      [08-21] 【<b>BrST-Net</b>】<i>Breast cancer histopathology image‑based gene expression prediction using spatial transcriptomics data and deep learning. <b>Sci. Rep.</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41598-023-40219-0.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Mamunur-20/BrSTNet' target='_blank'>Code</a>
    </li>
  </ul>
</details>

<details open> <!--2022-->
  <summary><b>&nbsp;2022 (4)</b></summary>
  <ul>
    <li>
      [10-30] 【<b>EGN</b>】<i>Exemplar Guided Deep Neural Network for Spatial Transcriptomics Analysis of Gene Expression Prediction. <b>WACV</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2210.16721' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Yan98/EGN' target='_blank'>Code</a>
    </li>
    <li>
      [07-17] 【<b>Hist2ST</b>】<i>Spatial transcriptomics prediction from histology jointly through Transformer and graph neural networks. <b>BIB</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://academic.oup.com/bib/article/23/5/bbac297/6645485' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/biomed-AI/Hist2ST' target='_blank'>Code</a>
    </li>
    <li>
      [03-08] 【<b>DeepSpaCE</b>】<i>Efficient prediction of a spatial transcriptomics profile better characterizes breast cancer tissue sections without costly experimentation. <b>Sci. Rep.</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41598-022-07685-4' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/tmonjo/DeepSpaCE' target='_blank'>Code</a>
    </li>
    <li>
      [02-18] 【<b>NSL</b>】<i>All You Need is Color: Image Based Spatial Gene Expression Prediction Using Neural Stain Learning. <b>ECML PKDD </b>.</i>
      <img src='./assets/paper.png' /> <a href='https://link.springer.com/chapter/10.1007/978-3-030-93733-1_32' target='_blank'>Article</a>
    </li>
  </ul>
</details>

<details open> <!--2021-->
  <summary><b>&nbsp;2021 (1)</b></summary>
  <ul>
    <li>
      [11-28] 【<b>HisToGene</b>】<i>Leveraging information in spatial transcriptomics to predict super-resolution gene expression from histology images in tumors. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/10.1101/2021.11.28.470212v1.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/maxpmx/HisToGene' target='_blank'>Code</a>
    </li>
  </ul>
</details>

<details open> <!--2020-->
  <summary><b>&nbsp;2020 (3)</b></summary>
  <ul>
    <li>
      [08-03] 【<b>HE2RNA</b>】<i>A deep learning model to predict RNA-Seq expression of tumours from whole slide images. <b>NAT COMMUN</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41467-020-17678-4' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/owkin/HE2RNA_code' target='_blank'>Code</a>
    </li>
    <li>
      [07-27] 【<b>DeepHistologyV2</b>】<i>Pan-cancer image-based detection of clinically actionable genetic alterations. <b>NCancer</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s43018-020-0087-6' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/jnkather/DeepHistology/releases/tag/v0.2' target='_blank'>Code</a>
    </li>
    <li>
      [06-22] 【<b>ST-Net</b>】<i>Integrating spatial gene expression and breast tumour morphology via deep learning. <b>NAT BIOMED ENG‌</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41551-020-0578-x' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/bryanhe/ST-Net' target='_blank'>Code</a>
    </li>
  </ul>
</details>

<details open> <!--2018-->
  <summary><b>&nbsp;2018 (1)</b></summary>
  <ul>
    <li>
      [09-17] 【<b>DeepPATH</b>】<i>Classification and mutation prediction from non–small cell lung cancer histopathology images using deep learning. <b>NMedicine</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41591-018-0177-5' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/ncoudray/DeepPATH' target='_blank'>Code</a>
    </li>
  </ul>
</details>

### Hist to Proteomics

<details open> <!--2026-->
  <summary><b>&nbsp;2026 (1)</b></summary>
  <ul>
    <li>
      [01-05] 【<b>HEX</b>】<i>AI-enabled virtual spatial proteomics from histopathology for interpretable biomarker discovery in lung cancer. <b>NMedicine</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41591-025-04060-4' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/lilab-stanford/HEX' target='_blank'>Code</a>
    </li>
  </ul>
</details>

<details open> <!--2025-->
  <summary><b>&nbsp;2025 (5)</b></summary>
  <ul>
    <li>
      [08-16] 【<b>ROISE</b>】<i>ROSIE: AI generation of multiplex immunofluorescence staining from histopathology images. <b>NAT COMMUN</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41467-025-62346-0.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://gitlab.com/enable-medicine-public/rosie' target='_blank'>Code</a>
    </li>
    <li>
      [08-04] 【<b>HistoPlexer</b>】<i>Histopathology-based protein multiplex generation using deep learning. <b>NMI</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s42256-025-01074-y' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/ratschlab/HistoPlexer' target='_blank'>Code</a>
    </li>
    <li>
      [12-12] 【<b>Eva</b>】<i>Modeling patient tissues at molecular resolution with Eva. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/10.64898/2025.12.10.693553v1' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/YAndrewL/Eva' target='_blank'>Code</a>
    </li>
    <li>
      [12-09] 【<b>GigaTIME</b>】<i>Multimodal AI generates virtual population for tumormicroenvironment modeling. <b>Cell</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1016/j.cell.2025.11.016' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://aka.ms/gigatime_code' target='_blank'>Code</a>
    </li>
    <li>
      [05-15] 【<b>MIPHEI</b>】<i>MIPHEI-ViT: Multiplex Immunofluorescence Prediction from H&E Images using ViT Foundation Models. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2505.10294' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/sanofi-public/miphei-vit' target='_blank'>Code</a>
    </li>
  </ul>
</details>

<details open> <!--2024-->
  <summary><b>&nbsp;2024 (2)</b></summary>
  <ul>
    <li>
      [09-13] 【<b>HIPI</b>】<i>HIPI: Spatially Resolved Multiplexed Protein Expression Inferred from H&E WSIs. <b>PLOSCB</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012501' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/RonZeira/HIPI/' target='_blank'>Code</a>
    </li>
    <li>
      [09-09] 【<b>VirtualMultiplexer </b>】<i>Accelerating histopathology workflows with generative AI-based virtually multiplexed tumour profiling. <b>NMI</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s42256-024-00889-5' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/AI4SCR/VirtualMultiplexer' target='_blank'>Code</a>
    </li>
  </ul>
</details>

### Hist to Multi-Omics

<details open> <!--2025-->
  <summary><b>&nbsp;2025 (2)</b></summary>
  <ul>
    <li>
      [12-17] 【<b>SpatialEx/SpatialEx+</b>】<i>High-parameter spatial multi-omics through histology-anchored integration. <b>NAT Methods</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41592-025-02926-6' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/KEAML-JLU/SpatialEx' target='_blank'>Code</a>
    </li>
    <li>
      [12-13] 【<b>TissueCraftAI </b>】<i>Query-driven generative AI synthesizes multi-modal spatial omics from histology. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/10.64898/2025.12.11.693669v1.full.pdf' target='_blank'>Article</a>
    </li>
  </ul>
</details>

### Hist to Cell

<details open> <!--2025-->
  <summary><b>&nbsp;2025 (4)</b></summary>
  <ul>
    <li>
      [02-21] 【<b>HistoCell</b>】<i>Systematic inference of super-resolution cell spatial profiles from histology images. <b>NAT COMMUN</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.nature.com/articles/s41467-025-57072-6.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/recolyce/HistoCell' target='_blank'>Code</a>
    </li>
    <li>
      [09-02] 【<b>HistoPLUS </b>】<i>Towards Comprehensive Cellular Characterisation of H&E slides. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://arxiv.org/pdf/2508.09926v3' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/owkin/histoplus/' target='_blank'>Code</a>
    </li>
    <li>
      [07-25] 【<b>CUCA </b>】<i>Predicting fine-grained cell types from histology images through cross-modal learning in spatial transcriptomics . <b>Bioinfo</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://doi.org/10.1093/bioinformatics/btaf201' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/lyotvincent/CUCA' target='_blank'>Code</a>
    </li>
    <li>
      [09-03] 【<b>HPCell </b>】<i>Accurately Predicting Cell Type Abundance from Spatial Histology Image Through HPCell. <b>ISC</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://link.springer.com/article/10.1007/s12539-025-00757-9' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/VitaIntelli-CQU/HPCell' target='_blank'>Code</a>
    </li>
  </ul>
</details>

<details open> <!--2024-->
  <summary><b>&nbsp;2024 (1)</b></summary>
  <ul>
    <li>
      [11-27] 【<b>Hist2Cell</b>】<i>Hist2Cell: Deciphering Fine-grained Cellular Architectures from Histology Images. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/10.1101/2024.02.17.580852v3.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/Weiqin-Zhao/Hist2Cell' target='_blank'>Code</a>
    </li>
  </ul>
</details>

### Hist to Pathology

<details open> <!--2025-->
  <summary><b>&nbsp;2025 (1)</b></summary>
  <ul>
    <li>
      [11-28] 【<b>DeepPathway</b>】<i>DeepPathway: Predicting Pathway Expression from Histopathology Images. <b>PrePrint</b>.</i>
      <img src='./assets/paper.png' /> <a href='https://www.biorxiv.org/content/biorxiv/early/2025/11/28/2025.07.21.665956.full.pdf' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='https://github.com/aahsan045/DeepPathway' target='_blank'>Code</a>
    </li>
  </ul>
</details>

## 🔗 Related Repositories

- [computer_vision_spatial_omics](https://github.com/hrlblab/computer_vision_spatial_omics)

- [awesome_spatial_omics](https://github.com/crazyhottommy/awesome_spatial_omics)

- [Awesome-HistoPathology-to-Spatial-Transcriptomics-Translation](https://github.com/ZZhangsm/Awesome-HistoPathology-to-Spatial-Transcriptomics-Translation)

- [Awesome-Computational-Pathology-Papers](https://github.com/DearCaat/Awesome-Computational-Pathology-Papers)

- [awesome-pathology](https://github.com/open-pathology/awesome-pathology)

- [Awesome-Foundation-Models-for-Pathology-Image-Analysis](https://github.com/dmhdmhdmh/Awesome-Foundation-Models-for-Pathology-Image-Analysis)

- [Medical-Foundation-Models](https://github.com/WuLabMDA/Medical-Foundation-Models)

- [Awesome-AI-Pathology](https://github.com/wyh196646/Awesome-AI-Pathology)

- [Awesome-Spatial-Transcriptomics-Pathology-Large-Models](https://github.com/2BF-Club/Awesome-Spatial-Transcriptomics-Pathology-Large-Models)

## ❤️ Contributing​

Contributions are welcome! Please follow these guidelines:​

1. Fork the repository​
2. Create a new branch (git checkout -b yourname/add-paper)​
3. Make your changes​. Please ensure your code follows the project's coding standards.
4. Commit your changes (git commit -m 'Add some papers')​
5. Push to the branch (git push origin yourname/add-paper)​
6. Open a Pull Request

- If a year section does not exist, create a new one:

```html
<details open> <!--2026-->
  <summary><b>&nbsp;[YEAR] ([Numbers])</b></summary>
  <ul>
    <li>
      [MM-DD] <b>【[Abbreviation]】</b><i>[Title]. <b>[Publication]</b>.</i>
      <img src='./assets/paper.png' /> <a href='[PaperURL]' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='[CodeURL]' target='_blank'>Code</a>
    </li>
  </ul>
</details>
```

- If a year section already exists, add the paper to the existing list:

```html
    <li>
      [MM-DD] <b>【[Abbreviation]】</b><i>[Title]. <b>[Publication]</b>.</i>
      <img src='./assets/paper.png' /> <a href='[PaperURL]' target='_blank'>Article</a>
      <img src='./assets/code.png' /> <a href='[CodeURL]' target='_blank'>Code</a>
    </li>
```

> **Note**: 
> - Please replace [MM-DD], [YEAR], [Numbers], [Abbreviation], [Title], [Publication], [PaperURL], [CodeURL] with the actual information. '[' and ']' are placeholders, please remove them except [MM-DD].
> - It is recommended to use abbreviations for the source of the papar.
> - Please ensure the URLs are valid and accessible. If the paper PDF is not available for all, please provide the DOI or official website. If the code is not available, please remove code: 
`<img src='./assets/code.png' /> <a href='[CodeURL]' target='_blank'>Code</a>`
> - If the paper does not provide an abbreviation for their method, please use `【-】`.

## ⭐ Citation
​
If you find this repository useful in your research, please consider citing:
```bibtex
Please Stay Tuned for More Updates!
Please star this repository if you find it helpful!
```

## 📧 Contact

For any questions or suggestions, feel free to open an issue or contact me at [bywu109@gmail.com](mailto:bywu109@gmail.com).