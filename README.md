[![Awesome](images/awesome.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)](https://github.com/joofio/awesome-data-synthesis/graphs/commit-activity)
![GitHub](https://img.shields.io/badge/Release-PROD-yellow.svg)
![GitHub](https://img.shields.io/badge/License-MIT-lightgrey.svg)
[![GitHub](https://img.shields.io/twitter/follow/4Elemento.svg?label=Follow)](https://twitter.com/4Elemento/)

Inspired by [awesome-production-machine-learning](https://github.com/EthicalML/awesome-production-machine-learning)

# Awesome Data Synthesis
This repository contains a curated list of awesome resources for creating synthetic data


# Main Content

## Data-driven methods

### Tabular
* [FakeR](https://cran.r-project.org/web/packages/fakeR/index.html) <img src="images/R_logo.svg.png" width="20" heigth=18> - Generates fake data from a dataset of different variable types
* [CTGAN](https://github.com/sdv-dev/CTGAN) <img src="images/python.png" width="20" heigth=20> - CTGAN is a GAN-based data synthesizer that can generate synthetic tabular data with high fidelity. - [Paper](https://arxiv.org/pdf/1907.00503.pdf)
* [TGAN](https://github.com/sdv-dev/TGAN) <img src="images/python.png" width="20" heigth=20> - Outdated and superseded by **CTGAN**
* [gretel](https://github.com/gretelai/gretel-synthetics) <img src="images/python.png" width="20" heigth=20> - create fake, synthetic datasets with enhanced privacy guarantees
* [On the Generation and Evaluation of Synthetic Tabular Data using GANs](https://github.com/Baukebrenninkmeijer/On-the-Generation-and-Evaluation-of-Synthetic-Tabular-Data-using-GANs) <img src="images/python.png" width="20" heigth=20> - we propose using the WGAN-GP architecture for training the GAN, which suffers less from mode-collapse and has a more meaningful loss. 
* [Synthpop](https://cran.r-project.org/web/packages/synthpop/index.html)  <img src="images/R_logo.svg.png" width="20" heigth=18> - A tool for producing synthetic versions of microdata containing confidential information so that they are safe to be released to users for exploratory analysis.
* [DataSynthesizer](https://github.com/DataResponsibly/DataSynthesizer) - DataSynthesizer generates synthetic data that simulates a given dataset. It applies Differential Privacy techniques to achieve strong privacy guarantee.
* [MedGAN](https://github.com/mp2893/medgan) - medGAN is a generative adversarial network for generating multi-label discrete patient records. It can generate both binary and count variables (i.e. medical codes such as diagnosis codes, medication codes or procedure codes) - [Paper](https://arxiv.org/abs/1703.06490)
* [MC-MedGAN](https://github.com/rcamino/multi-categorical-gans) - Multi-Categorical GANs - [Paper](https://arxiv.org/pdf/1807.01202.pdf)
* [tableGAN](https://github.com/mahmoodm2/tableGAN) - tableGAN is a synthetic data generation technique (Data Synthesis based on Generative Adversarial Networks paper) based on Generative Adversarial Network architecture (DCGAN). - [Paper](http://www.vldb.org/pvldb/vol11/p1071-park.pdf)
* [VEEGAN](https://akashgit.github.io/VEEGAN/) - Reducing Mode Collapse in GANs using Implicit Variational Learning - [Paper](https://arxiv.org/abs/1705.07761)
* [DP-WGAN](https://github.com/nesl/nist_differential_privacy_synthetic_data_challenge) - The solution trains a wasserstein generative adversarial network (w-GAN) that is trained on the real private dataset. Differentially private training is applied by santizing (norm clipping and adding Gaussian noise) the gradients of the discriminator. Once the model is trained, it can be used to generate sytnethic dataset by feeding random noise into the generator. 
* [DP-GAN](https://github.com/alps-lab/dpgan) - Differentially private release of semantic rich data - [Paper](https://arxiv.org/abs/1801.01594)
* [DP-GAN 2](https://github.com/illidanlab/dpgan) - Source code of paper "Differentially Private Generative Adversarial Network" - [Paper](https://arxiv.org/abs/1802.06739)
* [PateGAN] -  Our method modifies the Private Aggregation of Teacher Ensembles (PATE) framework and applies it to GANs - [Paper](https://openreview.net/forum?id=S1zk9iRqF7)
* [bnomics](https://bitbucket.org/77D/bnomics/src/master/) - Synthetic data generation with probabilistic Bayesian Networks - [Paper](https://www.biorxiv.org/content/10.1101/2020.06.14.151084v1.full.pdf)
* [MPoM] - [Paper](https://www.tandfonline.com/doi/abs/10.1198/jasa.2009.tm08439)
* [CLGP](https://github.com/yaringal/CLGP) - categorical latent Gaussian process is a generative model for multivariate categorical data - [Paper](http://proceedings.mlr.press/v37/gala15.html)
* [COR-GAN](https://github.com/astorfi/cor-gan) - Correlation-Capturing Convolutional Neural Networks for Generating Synthetic Healthcare Records - [Paper](https://arxiv.org/pdf/2001.09346v2.pdf)
* [synergetr](https://github.com/avirkki/synergetr) - An R package to generate synthetic data with empirical probability distributions  - [Paper]()
* [DPautoGAN](https://github.com/DPautoGAN/DPautoGAN) - Code for the paper Differentially Private Mixed-Type Data Generation for Unsupervised Learning - [Paper]()
* [SynC](https://github.com/winstonll/SynC) - SynC: A Unified Framework for Generating Synthetic Population with Gaussian Copula - [Paper]()
* [NIST-PSCR](https://github.com/ClaireMcKayBowen/Code-for-NIST-PSCR-Differential-Privacy-Synthetic-Data-Challenge) - Code and Data for NIST PSCR Differential Privacy Synthetic Data Challenge - [Paper]()
* [Bn-learn Latent Model](https://github.com/zhenchenwang/latent_model) - Generating High-Fidelity Synthetic Patient Data for Assessing Machine Learning Healthcare Software - [Paper](https://www.nature.com/articles/s41746-020-00353-9)
* [SAP Security research sample](https://github.com/SAP-samples/security-research-differentially-private-generative-models/blob/master/Tutorial_dp-VAE.ipynb) - SAP Security research sample code and tutorials for generating differentially private synthetic datasets using generative deep learning models
* [Python synthpop](https://github.com/hazy/synthpop) - Python implementation of the R package synthpop.
* [UCLANesl ](https://github.com/nesl/nist_differential_privacy_synthetic_data_challenge) - UCLANesl - NIST Differential Privacy Challenge (Match 3)
* [Repo on generating synthetic data using GAN](https://github.com/datasciencecampus/synthetic-data) - Repo on generating synthetic data using GAN
* [synthia](https://github.com/dmey/synthia) - 📈 🐍 Multidimensional synthetic data generation in Python
* [Synthetic_Data_System](https://github.com/SDS-Architect/Synthetic_Data_System) - The Alpha Build of the SDS for ideas gathering, testing and commentary
* [QUIPP](https://github.com/alan-turing-institute/QUIPP-pipeline) - Privacy preserving synthetic data generation workflows
* [MSFT synthetic data showcase](https://github.com/microsoft/synthetic-data-showcase) - Generates synthetic data and user interfaces for privacy-preserving data sharing and analysis.
* [extended-MedGan](https://github.com/marcolussetti/extended-medgan) - Synthetic patient data using generative adversarial networks.
* [Synthesizing quality open data](https://github.com/TheRensselaerIDEA/synthetic_data) - Synthesizing Quality Open Data Assets from Private Health Research Studies
* [bayesian-synthetic-generator](https://github.com/ITMO-NSS-team/bayesian-synthetic-generator) - Repository of a software system for generating synthetic personal data based on the Bayesian network block structure
* [Generating-Synthetic-data-using-GANs](https://github.com/vibhavps/Generating-Synthetic-data-using-GANs) - How can we safely and efficiently share encrypted data that is also useful. We use the mechanism of GANs used to generate fake images to generate synthetic tabular data
* [synthetic health data](https://github.com/albert-kevin/SyntheticHealthData2020) 
* [Synthetic data Copula](https://github.com/superyang713/Synthetic_Data_Generation)
* [PrivBayes](https://sourceforge.net/projects/privbayes/) - 
* [pategan](https://bitbucket.org/mvdschaar/mlforhealthlabpub/src/master/alg/pategan/)
* [HoloClean](https://github.com/HoloClean/holoclean/) - A Machine Learning System for Data Enrichment.
* [SYNDATA](https://github.com/LLNL/SYNDATA) - Generation and evaluation of synthetic patient data - [Paper](https://bmcmedresmethodol.biomedcentral.com/track/pdf/10.1186/s12874-020-00977-1.pdf)

### Multiple formats
* [SDV](https://github.com/sdv-dev/SDV) <img src="images/python.png" width="20" heigth=20>

### Time Series
* [mtss-gan](https://github.com/firmai/mtss-gan) <img src="images/python.png" width="20" heigth=20>
* [data-generator](https://github.com/KDD-OpenSource/data-generation)
* [RGAN](https://github.com/ratschlab/RGAN)
* [Machine-learning for trading Ch21](https://github.com/stefan-jansen/machine-learning-for-trading/tree/master/21_gans_for_synthetic_time_series)
* [tsBNgen](https://github.com/manitadayon/tsBNgen) - - [Paper](https://arxiv.org/pdf/2009.04595.pdf)
* [Sythetic Data Generation](https://github.com/stefan-jansen/synthetic-data-for-finance) - Material for QuantUniversity talk on Sythetic Data Generation for Finance.
* [LSTM GAN model](https://github.com/StoicGilgamesh/LSTM-GAN-) - The LSTM GAN model can be used for generation of synthetic multi-dimension time series data.


### Sensor data
* [synsys](https://github.com/jb3dahmen/SynSys-Updated) - create sensor data 

## Process-driven methods

### Tabular
* [bindata](https://cran.r-project.org/web/packages/bindata/index.html) <img src="images/R_logo.svg.png" width="20" heigth=18>
* [GenOrd](https://cran.r-project.org/web/packages/GenOrd/index.html) <img src="images/R_logo.svg.png" width="20" heigth=18>
* [MultiOrd](https://cran.r-project.org/web/packages/MultiOrd/index.html) <img src="images/R_logo.svg.png" width="20" heigth=18>
* [PoisBinOrdNonNor](https://cran.r-project.org/web/packages/PoisBinOrdNonNor/index.html) <img src="images/R_logo.svg.png" width="20" heigth=18>
* [SimMultiCorrData](https://cran.r-project.org/web/packages/SimMultiCorrData/index.html) <img src="images/R_logo.svg.png" width="20" heigth=18>
* [plaitpy](https://github.com/plaitpy/plaitpy) 
* [pySyntheticDatasetGenerator](https://github.com/EDS-APHP/pySyntheticDatasetGenerator)
* [SimPop](https://cran.r-project.org/web/packages/simPop/index.html) - Tools and methods to simulate populations for surveys based on auxiliary data. The tools include model-based methods, calibration and combinatorial optimization algorithms. 
* [datasynthR](https://github.com/jknowles/datasynthR)
* [synner](https://github.com/huda-lab/synner) -Generating Realistic Synthetic Data
* [pySyntheticDatasetGenerator](https://github.com/EDS-APHP/pySyntheticDatasetGenerator) - Generate relational fictive dataset from a simple yaml description



#### Students
* [OpenSDPsynthR](https://github.com/opensdp/OpenSDPsynthR) <img src="images/R_logo.svg.png" width="20" heigth=18>

#### Population
* [charlatan](https://cran.r-project.org/web/packages/charlatan/index.html) <img src="images/R_logo.svg.png" width="20" heigth=18>
* [fabricatr](https://cran.r-project.org/web/packages/fabricatr/index.html) <img src="images/R_logo.svg.png" width="20" heigth=18>
* [genstar](https://github.com/ANRGenstar/genstar)  
* [synthetico](https://github.com/marcovisibelli/synthetico)  
* [conjurer](https://github.com/SidharthMacherla/conjurer) - R Package to generate synthetic data.


#### Patients & Medical Data
* [synthea](https://github.com/synthetichealth/synthea)
* [BadMedicine](https://github.com/HicServices/BadMedicine)

## Metrics and dataset evaluation 
* [datagene](https://github.com/firmai/datagene) <img src="images/python.png" width="20" heigth=20>
* [SDMetrics](https://github.com/sdv-dev/SDMetrics) <img src="images/python.png" width="20" heigth=20>
* [SDV evaluation functions](https://github.com/sdv-dev/SDV) <img src="images/python.png" width="20" heigth=20>
* [table-evaluator](https://github.com/Baukebrenninkmeijer/table-evaluator) <img src="images/python.png" width="20" heigth=20>
* [Statistical-Similarity-Measurement](https://github.com/Olliang/Statistical-Similarity-Measurement) <img src="images/python.png" width="20" heigth=20>
* [SDGym](https://github.com/sdv-dev/SDGym) <img src="images/python.png" width="20" heigth=20> - Synthetic Data Gym (SDGym) is a framework to benchmark the performance of synthetic data generators for tabular data. SDGym is a project of the Data to AI Laboratory at MIT.
* [Statistical-Similarity-Measurement](https://github.com/Olliang/Statistical-Similarity-Measurement) - A methodology designed to validate the statistical similarity of synthetic data generated by GAN models. The metrics contain Auto-encoder, PCA, t-SNE, KL-divergence, Clustering, and Cosine Similarity.
* [virtualdatalab](https://github.com/mostly-ai/virtualdatalab) - Benchmarking synthetic data generators for sequential data in terms of accuracy and **privacy.**



## other 
https://github.com/jmschrei/pomegranate  
https://github.com/Pushkar-v/Generating-Synthetic-Data-using-GANs  
https://github.com/ydataai/ydata-synthetic   
https://github.com/DPBayes/data-sharing-examples     
https://github.com/jclymo/DataGen_NPBE   
https://github.com/theodi/synthetic-data-tutorial  
https://github.com/tirthajyoti/Synthetic-data-gen  
https://github.com/jhajagos/SynthMedTopia  
https://github.com/spiros/tofu  
https://github.com/ewvanwinkle/SyntheticDataVault  
https://github.com/chasebos91/GAN-for-Synthetic-EEG-Data  
https://github.com/jgalilee/data  
https://github.com/blt2114/overpruning_in_variational_bnns  
https://github.com/avensolutions/synthetic-cdc-data-generator  
https://github.com/nikk-nikaznan/SSVEP-Neural-Generative-Models  
https://github.com/MertNacar/create-synthetic-data
