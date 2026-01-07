<h1 align="center" id="awesome-histopathology-to-omics">🧬 Awesome-Histopathology-to-Omics</h1>

<p align="center">
  <img src="https://awesome.re/badge.svg" alt="Awesome">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/UPDATE-2026--01--07-orange" alt="Update">
</p>

## 🚀 Introduction

A curated collection of papers, codes, and resources for cross-modal translation/prediction/generation between
histopathological imaging and omics (genomics, proteomics, etc.), including histopathology-to-mIF image generation,
histopathology-to-genomic prediction, etc.

## 📋 Table of Contents

- 🔎 [Survey/Review/Benchmark/Protocol Papers List](#-surveyreviewbenchmark-protocol-papers-list)
- 🔬 [Research Papers List](#-research-papers-list)
  - [Hist to Genomics/Transcriptomics](#hist-to-genomicstranscriptomics)
  - [Hist to Proteomics](#hist-to-proteomics)
  - [Hist to Multi-omics](#hist-to-multi-omics)
  - [Hist to Cell](#hist-to-cell)
  - [Hist to Pathology](#hist-to-pathology)
- 🔗 [Related Repositories](#-related-repositories)
- ❤️ [Contributing](#-contributing)
- ⭐ [Citation](#-citation)
- 📧 [Contact](#-contact)

## 🔎 Survey/Review/Benchmark/Protocol Papers List

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2025 (6)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">6</td>
        <td align="center">10/28</td>
        <td align="center">Survey</td>
        <td align="center"><i>Content Generation Models in Computational Pathology: A Comprehensive Survey on Methods, Applications, and Challenges</i></td>
        <td align="center">IEEE Rev Biomed Eng</td>
        <td align="center"><a href='https://oar.a-star.edu.sg/storage/o/ozokdvm7xw/content-generation-models-in-computational-pathology.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">5</td>
        <td align="center">10/14</td>
        <td align="center">Survey</td>
        <td align="center"><i>Computer Vision Methods for Spatial Transcriptomics: A Survey</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/10.1101/2025.10.13.682148v1.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/hrlblab/computer_vision_spatial_omics' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">4</td>
        <td align="center">09/09</td>
        <td align="center">Data-quality Benchmark</td>
        <td align="center"><i>Impact of Data Quality on Deep Learning Prediction of Spatial Transcriptomics from Histology Images</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/10.1101/2025.09.04.674228v1.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/calebhallinan/dataquality_geneprediction' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">3</td>
        <td align="center">08/19</td>
        <td align="center">SpaCKLE</td>
        <td align="center"><i>Completing spatial transcriptomics data for gene expression prediction benchmarking</i></td>
        <td align="center">MEDIA</td>
        <td align="center"><a href='https://www.sciencedirect.com/science/article/pii/S1361841525003019' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/calebhallinan/SpaCKLE' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">2</td>
        <td align="center">05/13</td>
        <td align="center">Survey</td>
        <td align="center"><i>Combining spatial transcriptomics with tissue morphology</i></td>
        <td align="center">NAT COMMUN</td>
        <td align="center"><a href='https://doi.org/10.1038/s41467-025-58989-8' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">1</td>
        <td align="center">02/11</td>
        <td align="center">HEtoSGEBench</td>
        <td align="center"><i>Benchmarking the translational potential of spatial gene expression prediction from histology</i></td>
        <td align="center">NAT COMMUN</td>
        <td align="center"><a href='https://www.nature.com/articles/s41467-025-56618-y' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/SydneyBioX/HEtoSGEBench' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2024 (2)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">2</td>
        <td align="center">12/01</td>
        <td align="center">Survey</td>
        <td align="center"><i>Computational Methods for Breast Cancer Molecular Profiling through Routine Histopathology: A Review</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2412.10392' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">1</td>
        <td align="center">09/16</td>
        <td align="center">STAMP</td>
        <td align="center"><i>From whole-slide image to biomarker prediction: end-to-end weakly supervised deep learning in computational pathology</i></td>
        <td align="center">NAT PROTOC</td>
        <td align="center"><a href='https://arxiv.org/pdf/2412.10392' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/KatherLab/STAMP' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

## 🔬 Research Papers List

### Hist to Genomics/Transcriptomics

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2025 (53)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">53</td>
        <td align="center">12/16</td>
        <td align="center">SIGMMA</td>
        <td align="center"><i>SIGMMA: Hierarchical Graph-Based Multi-Scale Multi-modal Contrastive Alignment of Histopathology Image and Spatial Transcriptome</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2511.15464' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">52</td>
        <td align="center">12/14</td>
        <td align="center">STPath</td>
        <td align="center"><i>STPath: a generative foundation model for integrating spatial transcriptomics and whole-slide images</i></td>
        <td align="center">NPJDM</td>
        <td align="center"><a href='https://www.nature.com/articles/s41746-025-02020-3' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Graph-and-Geometric-Learning/STPath' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">51</td>
        <td align="center">12/07</td>
        <td align="center">STRank</td>
        <td align="center"><i>Learning Relative Gene Expression Trends from Histopathology Images in Spatial Transcriptomics</i></td>
        <td align="center">NeurIPS</td>
        <td align="center"><a href='https://openreview.net/pdf?id=X3zarVyJ5B' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/naivete5656/STRank' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">50</td>
        <td align="center">12/06</td>
        <td align="center">Gene-DML</td>
        <td align="center"><i>Gene-DML: Dual-Pathway Multi-Level Discrimination for Gene Expression Prediction from Histopathology Images</i></td>
        <td align="center">WACV</td>
        <td align="center"><a href='https://arxiv.org/pdf/2507.14670' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/YXSong000/Gene-DML' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr></td>
      </tr>
      <tr>
        <td align="center">49</td>
        <td align="center">12/03</td>
        <td align="center">DenseGOAT</td>
        <td align="center"><i>Aligning Histological Images and Spatial Gene Expression Jointly Through Densenet and Graph Ordering Attention Network</i></td>
        <td align="center">CISP-BMEI</td>
        <td align="center"><a href='https://ieeexplore.ieee.org/abstract/document/11259187' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">48</td>
        <td align="center">11/27</td>
        <td align="center">HyperST</td>
        <td align="center"><i>HyperST: Hierarchical Hyperbolic Learning for Spatial Transcriptomics Prediction</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2511.22107' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">47</td>
        <td align="center">11/27</td>
        <td align="center">MISO</td>
        <td align="center"><i>A deep learning-based multiscale integration of spatial omics with tumor morphology</i></td>
        <td align="center">NAT COMMUN</td>
        <td align="center"><a href='https://www.nature.com/articles/s41467-025-66691-y' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/owkin/miso_code' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">46</td>
        <td align="center">11/25</td>
        <td align="center">PixNet</td>
        <td align="center"><i>From Spots to Pixels: Dense Spatial Gene Expression Prediction from Histology Images</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2503.01347' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">45</td>
        <td align="center">11/21</td>
        <td align="center">DKAN</td>
        <td align="center"><i>Dual-Path Knowledge-Augmented Contrastive Alignment Network for Spatially Resolved Transcriptomics</i></td>
        <td align="center">AAAI</td>
        <td align="center"><a href='https://arxiv.org/abs/2511.17685' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/coffeeNtv/DKAN' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">44</td>
        <td align="center">11/20</td>
        <td align="center">SciSt</td>
        <td align="center"><i>SciSt: single-cell reference-informed spatial gene expression prediction from pathological images</i></td>
        <td align="center">BIB</td>
        <td align="center"><a href='https://academic.oup.com/bib/article/26/6/bbaf613/8329263' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/liyixin12139/SciSt' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">43</td>
        <td align="center">11/16</td>
        <td align="center">DomainST</td>
        <td align="center"><i>Bridging imaging and genomics: Domain knowledge guided spatial transcriptomics analysis</i></td>
        <td align="center">IF</td>
        <td align="center"><a href='https://www.sciencedirect.com/science/article/pii/S1566253525008085' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/coffeeNtv/DomainST' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">42</td>
        <td align="center">11/07</td>
        <td align="center">Img2ST-Net</td>
        <td align="center"><i>Img2ST-Net: efficient high-resolution spatial omics prediction from whole-slide histology images via fully convolutional image-to-image learning</i></td>
        <td align="center">JMI</td>
        <td align="center"><a href='https://doi.org/10.1117/1.JMI.12.6.061410' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/hrlblab/Img2ST-Net' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">41</td>
        <td align="center">10/13</td>
        <td align="center">MMAP</td>
        <td align="center"><i>MMAP: A Multi-Magnification and Prototype-Aware Architecture for Predicting Spatial Gene Expression</i></td>
        <td align="center">PRICAI</td>
        <td align="center"><a href='https://arxiv.org/pdf/2510.11344' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/pndh/MMAPattemp3' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">40</td>
        <td align="center">10/08</td>
        <td align="center">HisHRST</td>
        <td align="center"><i>Geometry-informed multimodal fusion network for enhancing high-densityspatial transcriptomics from histology images</i></td>
        <td align="center">EAAI</td>
        <td align="center"><a href='https://doi.org/10.1016/j.engappai.2025.112647' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/wenwenmin/HisHRST' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">39</td>
        <td align="center">10/05</td>
        <td align="center">GenAR</td>
        <td align="center"><i>GenAR: Next-Scale Autoregressive Generation for Spatial Gene Expression Prediction</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2510.04315v1' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/oyjr/genar' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">38</td>
        <td align="center">09/25</td>
        <td align="center">DeepSpot2Cell</td>
        <td align="center"><i>DeepSpot2Cell: Predicting Virtual Single-Cell Spatial Transcriptomics from H&E images using Spot-Level Supervision</i></td>
        <td align="center">NeurIPS</td>
        <td align="center"><a href='https://openreview.net/forum?id=ofCkwXQKaz' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/ratschlab/DeepSpot' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">37</td>
        <td align="center">09/21</td>
        <td align="center">CoMTIP</td>
        <td align="center"><i> Learning from Gene Names, Expression Values and Images: Contrastive Masked Text-Image Pretraining for Spatial Transcriptomics Representation Learning</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2509.16892?' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">36</td>
        <td align="center">09/18</td>
        <td align="center">NH²2ST</td>
        <td align="center"><i>Spatially Gene Expression Prediction Using Dual-Scale Contrastive Learning</i></td>
        <td align="center">MICCAI</td>
        <td align="center"><a href='https://arxiv.org/pdf/2506.23827?' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/MCPathology/NH2ST' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">35</td>
        <td align="center">09/15</td>
        <td align="center">iSCALE</td>
        <td align="center"><i>Scaling up spatial transcriptomics for large-sized tissues: uncovering cellular-level tissue architecture beyond conventional platforms with iSCALE</i></td>
        <td align="center">NAT Methods</td>
        <td align="center"><a href='https://www.nature.com/articles/s41592-025-02770-8' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/amesch441/iSCALE' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">34</td>
        <td align="center">09/15</td>
        <td align="center">GHIST</td>
        <td align="center"><i>Spatial gene expression at single-cell resolution from histology using deep learning with GHIST</i></td>
        <td align="center">NM</td>
        <td align="center"><a href='https://www.nature.com/articles/s41592-025-02795-z.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/SydneyBioX/GHIST' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">33</td>
        <td align="center">09/09</td>
        <td align="center">FmH2ST</td>
        <td align="center"><i>FmH2ST: foundation model-based spatial transcriptomics generation from histological images</i></td>
        <td align="center">NAR</td>
        <td align="center"><a href='https://academic.oup.com/nar/article-pdf/53/17/gkaf865/64870080/gkaf865.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://www.sdu-idea.cn/codes.php?name=FmH2ST' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">32</td>
        <td align="center">09/06</td>
        <td align="center">SpaFoundation</td>
        <td align="center"><i>A histology foundation model for high-resolution spatial omics prediction, tumor detection, and, clustering of spatial transcriptomics</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/biorxiv/early/2025/09/06/2025.08.07.669202.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/NingZhangCSUBio/SpaFoundation' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">31</td>
        <td align="center">09/04</td>
        <td align="center">stImage</td>
        <td align="center"><i>stImage: a versatile framework for optimizing spatial transcriptomic analysis through customizable deep histology and location informed integration</i></td>
        <td align="center">BIB</td>
        <td align="center"><a href='https://doi.org/10.1093/bib/bbaf429' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/YuWang-VUMC/stImage' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">30</td>
        <td align="center">08/21</td>
        <td align="center">SpatialFinder</td>
        <td align="center"><i>SpatialFinder: A Human-in-the-Loop Vision-Language Framework for Prioritizing High-Value Regions in Spatial Transcriptomics</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/biorxiv/early/2025/08/21/2025.08.16.670684.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">29</td>
        <td align="center">08/20</td>
        <td align="center">DANet</td>
        <td align="center"><i>DANet: spatial gene expression prediction from H&E histology images through dynamic alignment</i></td>
        <td align="center">BIB</td>
        <td align="center"><a href='https://doi.org/10.1093/bib/bbaf422' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/202324131016T/DANet' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">28</td>
        <td align="center">08/10</td>
        <td align="center">HaDM-ST</td>
        <td align="center"><i>HaDM-ST: Histology-Assisted Differential Modeling for Spatial Transcriptomics Generation</i></td>
        <td align="center">CMMCA</td>
        <td align="center"><a href='https://arxiv.org/pdf/2508.07225?' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">27</td>
        <td align="center">07/22</td>
        <td align="center">MVHybrid</td>
        <td align="center"><i>MVHybrid: Hybrid State Space-Vision Transformer for Pathology Foundation Models</i></td>
        <td align="center">MICCAI</td>
        <td align="center"><a href='https://arxiv.org/pdf/2508.00383' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/deepnoid-ai/MVHybrid' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">26</td>
        <td align="center">07/22</td>
        <td align="center">GenST</td>
        <td align="center"><i>GenST: A Generative Cross-Modal Model for Predicting Spatial Transcriptomics from Histology Images</i></td>
        <td align="center">MICCAI</td>
        <td align="center"><a href='https://openreview.net/forum?id=LHVSSaCKL6' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/ox-ibme-bio-imaging/GenST-workshop-version' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">25</td>
        <td align="center">07/20</td>
        <td align="center">STimage</td>
        <td align="center"><i>Robust and interpretable prediction of gene markers and cell types from spatial transcriptomics data</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/10.1101/2023.05.14.540710v2.full' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/BiomedicalMachineLearning/STimage' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">24</td>
        <td align="center">07/18</td>
        <td align="center">SpotWhisperer</td>
        <td align="center"><i>Molecularly informed analysis of histopathology images using natural language</i></td>
        <td align="center">ICML</td>
        <td align="center"><a href='https://www.biorxiv.org/content/10.1101/2025.07.14.664402v1.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">23</td>
        <td align="center">07/08</td>
        <td align="center">PAST</td>
        <td align="center"><i>PAST: A multimodal single-cell foundation model for histopathology and spatial transcriptomics in cancer</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2507.06418' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Changchun-Yang/past_sc' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">22</td>
        <td align="center">07/07</td>
        <td align="center">SPATIA</td>
        <td align="center"><i>SPATIA: Multimodal Model for Prediction and Generation of Spatial Cell Phenotypes</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2507.04704v1' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">21</td>
        <td align="center">07/06</td>
        <td align="center">Magic</td>
        <td align="center"><i>Spatial histology and gene-expression representation and generative learning via online self-distillation contrastive learning</i></td>
        <td align="center">BIB</td>
        <td align="center"><a href='https://doi.org/10.1093/bib/bbaf317' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/cat-moom/Magic' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">20</td>
        <td align="center">07/04</td>
        <td align="center">PathCLAST</td>
        <td align="center"><i>PathCLAST: Pathway-Augmented Contrastive Learning with Attention for Spatial Transcriptomics</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/10.1101/2025.06.30.662247v1.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/sslim-aidrug/PathCLAST' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">19</td>
        <td align="center">06/26</td>
        <td align="center">HECLIP</td>
        <td align="center"><i>HECLIP: histology-enhanced contrastive learning for imputation of transcriptomics profiles</i></td>
        <td align="center">Bioinfo</td>
        <td align="center"><a href='https://academic.oup.com/bioinformatics/advance-article-abstract/doi/10.1093/bioinformatics/btaf363/8174905' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/QSong-github/HECLIP' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">18</td>
        <td align="center">06/19</td>
        <td align="center">CarHE</td>
        <td align="center"><i>Predicting Spatial Transcriptomics from H&E Image by Pretrained Contrastive Alignment Learning</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/10.1101/2025.06.15.659438v1.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Jwzouchenlab/CarHE' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">17</td>
        <td align="center">06/18</td>
        <td align="center">Vispro</td>
        <td align="center"><i>Vispro improves imaging analysis for Visium spatial transcriptomics</i></td>
        <td align="center">GB</td>
        <td align="center"><a href='https://link.springer.com/article/10.1186/s13059-025-03648-w' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/HuifangZJU/Vispro' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">16</td>
        <td align="center">06/17</td>
        <td align="center">HistoTME-v2</td>
        <td align="center"><i>Towards interpretable molecular and spatial analysis of the tumor microenvironment from digital histopathology images with HistoTME-v2</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/10.1101/2025.06.11.658673v1.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/spatkar94/HistoTME' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">15</td>
        <td align="center">05/30</td>
        <td align="center">M2TGLGO</td>
        <td align="center"><i>Multi-modal Topology-embedded Graph Learning for Spatially Resolved Genes Prediction from Pathology Images with Prior Gene Similarity Information</i></td>
        <td align="center">CVPR</td>
        <td align="center"><a href='https://openaccess.thecvf.com/content/CVPR2025/papers/Shi_Multi-modal_Topology-embedded_Graph_Learning_for_Spatially_Resolved_Genes_Prediction_from_CVPR_2025_paper.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/shihangjs/M2TGLGO' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">14</td>
        <td align="center">05/29</td>
        <td align="center">OmiCLIP</td>
        <td align="center"><i>A visual–omics foundation model to bridge histopathology image with transcriptomics</i></td>
        <td align="center">NM</td>
        <td align="center"><a href='https://www.nature.com/articles/s41592-025-02707-1' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/GuangyuWangLab2021/Loki' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">13</td>
        <td align="center">05/25</td>
        <td align="center">STFlow</td>
        <td align="center"><i>Scalable Generation of Spatial Transcriptomics from Histology Images via Whole-Slide Flow Matching</i></td>
        <td align="center">ICML</td>
        <td align="center"><a href='https://arxiv.org/pdf/2506.05361' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Graph-and-Geometric-Learning/STFlow' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">12</td>
        <td align="center">04/23</td>
        <td align="center">VRI</td>
        <td align="center"><i>Histology-Based Virtual RNA Inference Identifies Pathways Associated with Metastasis Risk in Colorectal Cancer</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.medrxiv.org/content/10.1101/2025.04.22.25326170.abstract' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">11</td>
        <td align="center">04/20</td>
        <td align="center">PH2ST</td>
        <td align="center"><i>PH2ST: Prompt-Guided Hypergraph Learning for Spatial Transcriptomics Prediction in Whole Slide Images</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2503.16816' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/NIUYI0511/PH2ST/' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">10</td>
        <td align="center">04/11</td>
        <td align="center">M2OST</td>
        <td align="center"><i>M2OST: Many-to-one Regression for Predicting Spatial Transcriptomics from Digital Pathology Images</i></td>
        <td align="center">AAAI</td>
        <td align="center"><a href='https://ojs.aaai.org/index.php/AAAI/article/view/32830' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Dootmaan/M2OST' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">9</td>
        <td align="center">03/16</td>
        <td align="center">Path2Omics</td>
        <td align="center"><i>Path2Omics: Enhanced transcriptomic and methylation prediction accuracy from tumor histopathology</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/biorxiv/early/2025/03/16/2025.02.26.640189.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://doi.org/10.5281/zenodo.15016142' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">8</td>
        <td align="center">03/13</td>
        <td align="center">AGP-Net</td>
        <td align="center"><i>AGP-Net: A Universal Network for Gene Expression Prediction of Spatial Transcriptomics</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/biorxiv/early/2025/03/13/2025.03.09.642276.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">7</td>
        <td align="center">02/28</td>
        <td align="center">MagNet</td>
        <td align="center"><i>MagNet: Multi-Level Attention Graph Network for Predicting High-Resolution Spatial Transcriptomics</i></td>
        <td align="center">MIDL</td>
        <td align="center"><a href='https://arxiv.org/pdf/2502.21011?' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Junchao-Zhu/MagNet' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">6</td>
        <td align="center">02/22</td>
        <td align="center">Path2Space</td>
        <td align="center"><i>AI-Driven Spatial Transcriptomics Unlocks Large-Scale Breast Cancer Biomarker Discovery from Histopathology</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/biorxiv/early/2025/02/22/2024.10.16.618609.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">5</td>
        <td align="center">02/09</td>
        <td align="center">DeepSpot</td>
        <td align="center"><i>DeepSpot: Leveraging Spatial Context for Enhanced Spatial Transcriptomics Prediction from H&E Images</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.medrxiv.org/content/10.1101/2025.02.09.25321567v1.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/ratschlab/DeepSpot' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">4</td>
        <td align="center">01/26</td>
        <td align="center">Stem</td>
        <td align="center"><i>Diffusion Generative Modeling for Spatially Resolved Gene Expression Inference from Histology Images</i></td>
        <td align="center">ICLR</td>
        <td align="center"><a href='https://arxiv.org/pdf/2501.15598v1' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/SichenZhu/Stem' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">3</td>
        <td align="center">01/10</td>
        <td align="center">BG-TRIPLEX</td>
        <td align="center"><i>Boundary-Guided Learning for Gene Expression Prediction in Spatial Transcriptomics</i></td>
        <td align="center">BIBM</td>
        <td align="center"><a href='https://arxiv.org/pdf/2412.04072?' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/WcloudC0416/BG-TRIPLEX' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">2</td>
        <td align="center">01/10</td>
        <td align="center">HisToSGE</td>
        <td align="center"><i>High-Resolution Spatial Transcriptomics from Histology Images using HisToSGE</i></td>
        <td align="center">BIBM</td>
        <td align="center"><a href='https://arxiv.org/pdf/2407.20518?' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/wenwenmin/HisToSGE' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">1</td>
        <td align="center">01/06</td>
        <td align="center">STMCL</td>
        <td align="center"><i>Inferring multi-slice spatially resolved gene expression from H&E-stained histology images with STMCL</i></td>
        <td align="center">Methods</td>
        <td align="center"><a href='https://www.sciencedirect.com/science/article/pii/S1046202324002834' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/wenwenmin/STMCL' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2024 (19)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">19</td>
        <td align="center">12/19</td>
        <td align="center">HistoTME</td>
        <td align="center"><i>Predicting the tumor microenvironment composition and immunotherapy response in non-small cell lung cancer from digital histopathology images</i></td>
        <td align="center">NPJPO</td>
        <td align="center"><a href='https://www.nature.com/articles/s41698-024-00765-w.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/spatkar94/HistoTME' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">18</td>
        <td align="center">12/17</td>
        <td align="center">STFormer</td>
        <td align="center"><i>STFormer: Learning to Explore Spot Relationships for Spatial Transcriptomics Prediction from Histology of Colorectal Cancer</i></td>
        <td align="center">EMBC</td>
        <td align="center"><a href='https://ieeexplore.ieee.org/abstract/document/10782295' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">17</td>
        <td align="center">12/03</td>
        <td align="center">MERGE</td>
        <td align="center"><i>MERGE: Multi-faceted Hierarchical Graph-based GNN for Gene Expression Prediction from Whole Slide Histopathology Images</i></td>
        <td align="center">CVPR</td>
        <td align="center"><a href='https://openaccess.thecvf.com/content/CVPR2025/html/Ganguly_MERGE_Multi-faceted_Hierarchical_Graph-based_GNN_for_Gene_Expression_Prediction_from_CVPR_2025_paper.html' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">16</td>
        <td align="center">11/27</td>
        <td align="center">GeneQuery</td>
        <td align="center"><i>GeneQuery: A General QA-based Framework for Spatial Gene Expression Predictions from Histology Images</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2411.18391?' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/xy-always/GeneQuery' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">15</td>
        <td align="center">11/25</td>
        <td align="center">ST-Align</td>
        <td align="center"><i>ST-Align: A Multimodal Foundation Model for Image-Gene Alignment in Spatial Transcriptomics</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2411.16793' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">14</td>
        <td align="center">11/15</td>
        <td align="center">HistoSPACE</td>
        <td align="center"><i>HistoSPACE: Histology-inspired spatial transcriptome prediction and characterization engine</i></td>
        <td align="center">Methods</td>
        <td align="center"><a href='https://doi.org/10.1016/j.ymeth.2024.11.002' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">13</td>
        <td align="center">11/14</td>
        <td align="center">SEQUOIA</td>
        <td align="center"><i>Digital profiling of gene expression from histology images with linearized attention</i></td>
        <td align="center">NAT COMMUN</td>
        <td align="center"><a href='https://www.nature.com/articles/s41467-024-54182-5' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/gevaertlab/sequoia-pub' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">12</td>
        <td align="center">11/08</td>
        <td align="center">sCellST</td>
        <td align="center"><i>sCellST: a Multiple Instance Learning approach to predict single-cell gene expression from H&E images using spatial transcriptomics</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/biorxiv/early/2024/11/08/2024.11.07.622225.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/loicchadoutaud/sCellST' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">11</td>
        <td align="center">10/29</td>
        <td align="center">mclSTExp</td>
        <td align="center"><i>Multimodal contrastive learning for spatial gene expression prediction using histology images</i></td>
        <td align="center">BIB</td>
        <td align="center"><a href='https://doi.org/10.1093/bib/bbae551' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/shizhiceng/mclSTExp' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">10</td>
        <td align="center">10/14</td>
        <td align="center">HGGEP</td>
        <td align="center"><i>Gene expression prediction from histology images via hypergraph neural networks</i></td>
        <td align="center">BIB</td>
        <td align="center"><a href='https://doi.org/10.1093/bib/bbae500' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/QSong-github/HGGEP' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">9</td>
        <td align="center">09/26</td>
        <td align="center">HEMIT</td>
        <td align="center"><i>HEMIT: H&E to Multiplex-immunohistochemistry Image Translation with Dual-Branch Pix2pix Generator</i></td>
        <td align="center">Bioinfo</td>
        <td align="center"><a href='https://arxiv.org/pdf/2403.18501' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/BianChang/HEMIT-DATASET' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">8</td>
        <td align="center">09/04</td>
        <td align="center">asGNN</td>
        <td align="center"><i>Predicting spatially resolved gene expression via tissue morphology using adaptive spatial GNNs</i></td>
        <td align="center">Bioinfo</td>
        <td align="center"><a href='https://doi.org/10.1093/bioinformatics/btae383' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/song0309/asGNN/' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">7</td>
        <td align="center">08/09</td>
        <td align="center">ResSAT</td>
        <td align="center"><i>ResSAT: Enhancing Spatial Transcriptomics Prediction from H&E- Stained Histology Images with Interactive Spot Transformer</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.researchsquare.com/article/rs-4707959/v1' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Wonderangela/ResSAT' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">6</td>
        <td align="center">07/03</td>
        <td align="center">DeepPT</td>
        <td align="center"><i>A deep-learning framework to predict cancer treatment response from histopathology images through imputed transcriptomics</i></td>
        <td align="center">NCancer</td>
        <td align="center"><a href='https://www.nature.com/articles/s43018-024-00793-2' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://doi.org/10.5281/zenodo.11125591' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">5</td>
        <td align="center">06/22</td>
        <td align="center">RedeHist</td>
        <td align="center"><i>Spatial Transcriptomics Prediction from Histology Images at Single-cellResolution using RedeHist</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/10.1101/2024.06.17.599464v1.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Roshan1992/RedeFISH' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">4</td>
        <td align="center">06/05</td>
        <td align="center">HE2Gene</td>
        <td align="center"><i>HE2Gene: image-to-RNA translation via multi-task learning for spatial transcriptomics data</i></td>
        <td align="center">Bioinfo</td>
        <td align="center"><a href='https://doi.org/10.1093/bioinformatics/btae343' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Microbiods/HE2Gene' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">3</td>
        <td align="center">04/25</td>
        <td align="center">TRIPLEX</td>
        <td align="center"><i>Accurate spatial gene expression prediction by integrating multi-resolution features</i></td>
        <td align="center">CVPR</td>
        <td align="center"><a href='https://openaccess.thecvf.com/content/CVPR2024/papers/Chung_Accurate_Spatial_Gene_Expression_Prediction_by_Integrating_Multi-Resolution_Features_CVPR_2024_paper.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
      <tr>
        <td align="center">2</td>
        <td align="center">04/22</td>
        <td align="center">STAGE</td>
        <td align="center"><i>High-density generation of spatial transcriptomics withSTAGE</i></td>
        <td align="center">NAR</td>
        <td align="center"><a href='https://doi.org/10.1093/nar/gkae294' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/zhanglabtools/STAGE' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">1</td>
        <td align="center">01/02</td>
        <td align="center">iStar</td>
        <td align="center"><i>Inferring super-resolution tissue architecture by integrating spatial transcriptomics with histology</i></td>
        <td align="center">NBiotech</td>
        <td align="center"><a href='https://www.nature.com/articles/s41587-023-02019-9' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/daviddaiweizhang/istar' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2023 (6)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">6</td>
        <td align="center">12/25</td>
        <td align="center">THIToGene</td>
        <td align="center"><i>THItoGene: a deep learning method for predicting spatial transcriptomics from histological images</i></td>
        <td align="center">BIB</td>
        <td align="center"><a href='https://academic.oup.com/bib/article-pdf/25/1/bbad464/54826450/bbad464.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/yrjia1015/THItoGene' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">5</td>
        <td align="center">11/25</td>
        <td align="center">TCGN</td>
        <td align="center"><i>Transformer with convolution and graph-node co-embedding: An accurate and interpretable vision backbone for predicting gene expressions from local histopathological image</i></td>
        <td align="center">MEDIA</td>
        <td align="center"><a href='https://www.sciencedirect.com/science/article/pii/S1361841523003006' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/lugia-xiao/TCGN' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">4</td>
        <td align="center">09/26</td>
        <td align="center">EGGN</td>
        <td align="center"><i>Spatial transcriptomics analysis of gene expression prediction using exemplar guided graph neural network</i></td>
        <td align="center">PR</td>
        <td align="center"><a href='https://www.sciencedirect.com/science/article/pii/S0031320323006647' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Yan98/EGN' target='_blank'><img src='./assets/code.png' /></a>
        </td>
      </tr>
      <tr>
        <td align="center">3</td>
        <td align="center">09/22</td>
        <td align="center">BLEEP</td>
        <td align="center"><i>Spatially Resolved Gene Expression Prediction from H&E Histology Images via Bi-modal Contrastive Learning</i></td>
        <td align="center">NeurIPS</td>
        <td align="center"><a href='https://proceedings.neurips.cc/paper_files/paper/2023/hash/df656d6ed77b565e8dcdfbf568aead0a-Abstract-Conference.html' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/bowang-lab/BLEEP' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">2</td>
        <td align="center">09/02</td>
        <td align="center">SEPAL</td>
        <td align="center"><i>SEPAL: Spatial Gene Expression Prediction from Local Graphs</i></td>
        <td align="center">ICCV</td>
        <td align="center"><a href='https://openaccess.thecvf.com/content/ICCV2023W/CVAMD/papers/Mejia_SEPAL_Spatial_Gene_Expression_Prediction_from_Local_Graphs_ICCVW_2023_paper.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/BCV-Uniandes/SEPAL' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">1</td>
        <td align="center">08/21</td>
        <td align="center">BrST-Net</td>
        <td align="center"><i>Breast cancer histopathology image‑based gene expression prediction using spatial transcriptomics data and deep learning</i></td>
        <td align="center">Sci. Rep.</td>
        <td align="center"><a href='https://www.nature.com/articles/s41598-023-40219-0.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Mamunur-20/BrSTNet' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2022 (4)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">4</td>
        <td align="center">10/30</td>
        <td align="center">EGN</td>
        <td align="center"><i>Exemplar Guided Deep Neural Network for Spatial Transcriptomics Analysis of Gene Expression Prediction</i></td>
        <td align="center">WACV</td>
        <td align="center"><a href='https://arxiv.org/pdf/2210.16721' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Yan98/EGN' target='_blank'><img src='./assets/code.png' /></a>
        </td>
      </tr>
      <tr>
        <td align="center">3</td>
        <td align="center">07/17</td>
        <td align="center">Hist2ST</td>
        <td align="center"><i>Spatial transcriptomics prediction from histology jointly through Transformer and graph neural networks</i></td>
        <td align="center">BIB</td>
        <td align="center"><a href='https://academic.oup.com/bib/article/23/5/bbac297/6645485' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/biomed-AI/Hist2ST' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">2</td>
        <td align="center">03/08</td>
        <td align="center">DeepSpaCE</td>
        <td align="center"><i>Efficient prediction of a spatial transcriptomics profile better characterizes breast cancer tissue sections without costly experimentation</i></td>
        <td align="center">Sci. Rep.</td>
        <td align="center"><a href='https://www.nature.com/articles/s41598-022-07685-4' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/tmonjo/DeepSpaCE' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">1</td>
        <td align="center">02/18</td>
        <td align="center">NSL</td>
        <td align="center"><i>All You Need is Color: Image Based Spatial Gene Expression Prediction Using Neural Stain Learning</i></td>
        <td align="center">ECML PKDD</td>
        <td align="center"><a href='https://link.springer.com/chapter/10.1007/978-3-030-93733-1_32' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
    </tbody>
  </table>
</details>

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2021 (1)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">1</td>
        <td align="center">11/28</td>
        <td align="center">HisToGene</td>
        <td align="center"><i>Leveraging information in spatial transcriptomics to predict super-resolution gene expression from histology images in tumors</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/10.1101/2021.11.28.470212v1.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/maxpmx/HisToGene' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2020 (3)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">3</td>
        <td align="center">08/03</td>
        <td align="center">HE2RNA</td>
        <td align="center"><i>A deep learning model to predict RNA-Seq expression of tumours from whole slide images</i></td>
        <td align="center">NAT COMMUN</td>
        <td align="center"><a href='https://www.nature.com/articles/s41467-020-17678-4' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/owkin/HE2RNA_code' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">2</td>
        <td align="center">07/27</td>
        <td align="center">DeepHistologyV2</td>
        <td align="center"><i>Pan-cancer image-based detection of clinically actionable genetic alterations</i></td>
        <td align="center">NCancer</td>
        <td align="center"><a href='https://www.nature.com/articles/s43018-020-0087-6' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/jnkather/DeepHistology/releases/tag/v0.2' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">1</td>
        <td align="center">06/22</td>
        <td align="center">ST-Net</td>
        <td align="center"><i>Integrating spatial gene expression and breast tumour morphology via deep learning</i>
        </td>
        <td align="center">NAT BIOMED ENG</td>
        <td align="center"><a href='https://www.nature.com/articles/s41551-020-0578-x' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/bryanhe/ST-Net' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2018 (1)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">1</td>
        <td align="center">09/17</td>
        <td align="center">DeepPATH</td>
        <td align="center"><i>Classification and mutation prediction from non–small cell lung cancer histopathology images using deep learning</i></td>
        <td align="center">NMedicine</td>
        <td align="center"><a href='https://www.nature.com/articles/s41591-018-0177-5' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/ncoudray/DeepPATH' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

### Hist to Proteomics
<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2026 (1)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">1</td>
        <td align="center">01/05</td>
        <td align="center">HEX</td>
        <td align="center"><i>AI-enabled virtual spatial proteomics from histopathology for interpretable biomarker discovery in lung cancer</i></td>
        <td align="center">NMedicine</td>
        <td align="center"><a href='https://www.nature.com/articles/s41591-025-04060-4' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/lilab-stanford/HEX' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2025 (5)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">5</td>
        <td align="center">12/12</td>
        <td align="center">Eva</td>
        <td align="center"><i>Modeling patient tissues at molecular resolution with Eva</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/10.64898/2025.12.10.693553v1' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/YAndrewL/Eva' target='_blank'><img src='./assets/code.png' /></a>
        </td>
      </tr>
      <tr>
        <td align="center">4</td>
        <td align="center">12/09</td>
        <td align="center">GigaTIME</td>
        <td align="center"><i>Multimodal AI generates virtual population for tumormicroenvironment modeling</i></td>
        <td align="center">Cell</td>
        <td align="center"><a href='https://doi.org/10.1016/j.cell.2025.11.016' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://aka.ms/gigatime_code' target='_blank'><img src='./assets/code.png' /></a>
        </td>
      </tr>
      <tr>
        <td align="center">3</td>
        <td align="center">08/16</td>
        <td align="center">ROISE</td>
        <td align="center"><i>ROSIE: AI generation of multiplex immunofluorescence staining from histopathology images</i></td>
        <td align="center">NAT COMMUN</td>
        <td align="center"><a href='https://www.nature.com/articles/s41467-025-62346-0.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://gitlab.com/enable-medicine-public/rosie' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">2</td>
        <td align="center">08/04</td>
        <td align="center">HistoPlexer</td>
        <td align="center"><i>Histopathology-based protein multiplex generation using deep learning</i></td>
        <td align="center">NMI</td>
        <td align="center"><a href='https://www.nature.com/articles/s42256-025-01074-y' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/ratschlab/HistoPlexer' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">1</td>
        <td align="center">05/15</td>
        <td align="center">MIPHEI</td>
        <td align="center"><i>MIPHEI-ViT: Multiplex Immunofluorescence Prediction from H&E Images using ViT Foundation Models</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2505.10294' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/sanofi-public/miphei-vit' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2024 (2)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">2</td>
        <td align="center">09/13</td>
        <td align="center">HIPI</td>
        <td align="center"><i>HIPI: Spatially Resolved Multiplexed Protein Expression Inferred from H&E WSIs</i></td>
        <td align="center">PLOSCB</td>
        <td align="center"><a href='https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012501' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/RonZeira/HIPI/' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">1</td>
        <td align="center">09/09</td>
        <td align="center">VirtualMultiplexer</td>
        <td align="center"><i>Accelerating histopathology workflows with generative AI-based virtually multiplexed tumour profiling</i></td>
        <td align="center">NMI</td>
        <td align="center"><a href='https://www.nature.com/articles/s42256-024-00889-5' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/AI4SCR/VirtualMultiplexer' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2022 (1)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">1</td>
        <td align="center">04/07</td>
        <td align="center">DeepLIIF</td>
        <td align="center"><i>Deep learning-inferred multiplex immunofluorescence for immunohistochemical image quantification</i></td>
        <td align="center">NMI</td>
        <td align="center"><a href='https://www.nature.com/articles/s42256-022-00471-x' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/nadeemlab/DeepLIIF' target='_blank'><img src='./assets/code.png' /></a>
        </td>
      </tr>
    </tbody>
  </table>
</details>

### Hist to Multi-Omics

<details open>
<summary><b><span style="font-size: 1.3em;">&nbsp;2025 (2)</span></b></summary>
<table>
  <thead>
    <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">2</td>
        <td align="center">12/17</td>
        <td align="center">SpatialEx+</td>  
        <td align="center"><i>High-parameter spatial multi-omics through histology-anchored integration</i></td>
        <td align="center">NAT Methods</td>
        <td align="center"><a href='https://www.nature.com/articles/s41592-025-02926-6' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/KEAML-JLU/SpatialEx' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">1</td>
        <td align="center">12/13</td>
        <td align="center">TissueCraftAI</td>
        <td align="center"><i>Query-driven generative AI synthesizes multi-modal spatial omics from histology</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/10.64898/2025.12.11.693669v1.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center">❌</td>
      </tr>
</tbody>
</table>
</details>

### Hist to Cell

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2025 (4)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">4</td>
        <td align="center">09/03</td>
        <td align="center">HPCell</td>
        <td align="center"><i>Accurately Predicting Cell Type Abundance from Spatial Histology Image Through HPCell</i></td>
        <td align="center">ISC</td>
        <td align="center"><a href='https://link.springer.com/article/10.1007/s12539-025-00757-9' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/VitaIntelli-CQU/HPCell' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">3</td>
        <td align="center">09/02</td>
        <td align="center">HistoPLUS</td>
        <td align="center"><i>Towards Comprehensive Cellular Characterisation of H&E slides</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://arxiv.org/pdf/2508.09926v3' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/owkin/histoplus/' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">2</td>
        <td align="center">07/25</td>
        <td align="center">CUCA</td>
        <td align="center"><i>Predicting fine-grained cell types from histology images through cross-modal learning in spatial transcriptomics</i></td>
        <td align="center">Bioinfo</td>
        <td align="center"><a href='https://doi.org/10.1093/bioinformatics/btaf201' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/lyotvincent/CUCA' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
      <tr>
        <td align="center">1</td>
        <td align="center">02/21</td>
        <td align="center">HistoCell</td>
        <td align="center"><i>Systematic inference of super-resolution cell spatial profiles from histology images</i></td>
        <td align="center">NAT COMMUN</td>
        <td align="center"><a href='https://www.nature.com/articles/s41467-025-57072-6.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/recolyce/HistoCell' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2024 (1)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">1</td>
        <td align="center">11/27</td>
        <td align="center">Hist2Cell</td>
        <td align="center"><i>Hist2Cell: Deciphering Fine-grained Cellular Architectures from Histology Images</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/10.1101/2024.02.17.580852v3.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/Weiqin-Zhao/Hist2Cell' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>

### Hist to Pathology

<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;2025 (1)</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">1</td>
        <td align="center">11/28</td>
        <td align="center">DeepPathway</td>
        <td align="center"><i>DeepPathway: Predicting Pathway Expression from Histopathology Images</i></td>
        <td align="center">PrePrint</td>
        <td align="center"><a href='https://www.biorxiv.org/content/biorxiv/early/2025/11/28/2025.07.21.665956.full.pdf' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='https://github.com/aahsan045/DeepPathway' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
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
<details open>
  <summary><b><span style="font-size: 1.3em;">&nbsp;[YEAR] ([Numbers])</span></b></summary>
  <table>
    <thead>
      <tr>
        <th>No.</th>
        <th>Date</th>
        <th>Method</th>
        <th>Title</th>
        <th>Source</th>
        <th>Paper</th>
        <th>Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">[No.(descending order)]</td>
        <td align="center">[MM/DD]</td>
        <td align="center">[Method(abbreviation)]</td>
        <td align="center"><i>[Title]</i></td>
        <td align="center">[Source]</td>
        <td align="center"><a href='[PaperURL]' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='[CodeURL]' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
    </tbody>
  </table>
</details>
```

- If a year section already exists, add the paper to the existing list:

```html
      <tr>
        <td align="center">[No.(descend)]</td>
        <td align="center">[MM/DD]</td>
        <td align="center">[Method(abbreviation)]</td>
        <td align="center"><i>[Title]</i></td>
        <td align="center">[Source]</td>
        <td align="center"><a href='[PaperURL]' target='_blank'><img src='./assets/paper.png' /></a></td>
        <td align="center"><a href='[CodeURL]' target='_blank'><img src='./assets/code.png' /></a></td>
      </tr>
```

> **Note**:
> - Please replace [YEAR], [Numbers], [No.(descend)], [MM/DD], [Numbers], [Abbreviation], [Title], [Source], [PaperURL], [CodeURL] with the
actual information. '[' and ']' are placeholders, please remove them.
> - It is recommended to use abbreviations for the source of the papar.
> - Please ensure the URLs are valid and accessible. If the paper PDF is not available for all, please provide the DOI or official website. If the code is not available, please use `❌`.
> - If the paper does not provide an abbreviation for their method, please use `-`.
> - Please strictly follow the format provided in the template.

## ⭐ Citation
​
If you find this repository useful in your research, please consider citing:
```bibtex
Please Stay Tuned for More Updates!
Please star this repository if you find it helpful!
```

## 📧 Contact

For any questions or suggestions, feel free to open an issue or contact me at
[bywu109@gmail.com](mailto:bywu109@gmail.com).

<p align='right'>(<a href='#awesome-histopathology-to-omics'>Back to Top</a>)</p>