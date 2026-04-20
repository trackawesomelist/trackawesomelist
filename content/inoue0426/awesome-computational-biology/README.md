# Track Awesome Computational Biology Updates Daily

Awesome list of computational biology.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/inoue0426/awesome-computational-biology/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 inoue0426/awesome-computational-biology](https://github.com/inoue0426/awesome-computational-biology) · ⭐ 126 · 🏷️ Miscellaneous

[ Daily / [Weekly](/content/inoue0426/awesome-computational-biology/week/README.md) / [Overview](/content/inoue0426/awesome-computational-biology/readme/README.md) ]

## [Apr 20, 2026](/content/2026/04/20/README.md)

### Benchmarks & Datasets

*   [DUD-E (Directory of Useful Decoys, Enhanced)](http://dude.docking.org/) — Structure-based virtual screening benchmark with active ligands and challenging decoy sets across diverse protein targets.

## [Apr 18, 2026](/content/2026/04/18/README.md)

### Benchmarks & Datasets

*   [JUMP Cell Painting Datasets (⭐184)](https://github.com/jump-cellpainting/datasets) — Consortium-scale cell imaging perturbation datasets (chemical and genetic) for phenotypic profiling and drug discovery research.
*   [scPerturb (⭐172)](https://github.com/sanderlab/scPerturb) — Curated and continuously updated single-cell perturbation data resource spanning CRISPR and drug perturbation studies.

### Drug Response Prediction

*   [chemCPA (⭐148)](https://github.com/theislab/chemCPA) — Compositional perturbation autoencoder for predicting single-cell transcriptional responses to unseen drug perturbations and dose combinations.
*   [cycleCDR (⭐3)](https://github.com/hliulab/cycleCDR) — Interpretable cycle-consistency framework for modeling cellular responses to drug perturbations.

## [Apr 17, 2026](/content/2026/04/17/README.md)

### GitHub Pages UI

*   Search matches `name`, `description`, `tasks`, `modalities`, and `tags`.
*   The **Task**, **Modality**, and **Type** filters map directly to `tasks`, `modalities`, and `type` in `docs/data/resources.json`.
*   Clicking badges on cards applies the corresponding filter.

### Curation Criteria (Strict) / Protein Structure Prediction and Design

*   The resource is trustworthy and relevant to computational biology.
*   The primary link points to an official source (official docs, organization site, maintained repository, or official dataset page).
*   The resource has evidence of technical substance: ideally a peer-reviewed paper; at minimum a preprint or official technical documentation.
*   The description is factual and concise (no marketing copy).
*   Duplicate or near-duplicate entries should be avoided.

### Update & Link Rot Policy / Protein Structure Prediction and Design

*   Link validity is monitored by the [Link Check workflow](https://github.com/inoue0426/awesome-computational-biology/blob/main/README.md/./.github/workflows/link-check.yml).
*   If a link repeatedly fails, maintainers may replace it with an official mirror/canonical URL or remove the entry until a stable URL is available.
*   Contributions fixing broken links are welcome and encouraged.

### Data Schema & Contribution Workflow / Protein Structure Prediction and Design

*   Data schema reference: [`docs/data/SCHEMA.md`](https://github.com/inoue0426/awesome-computational-biology/blob/main/README.md/./docs/data/SCHEMA.md).
*   Source-of-truth workflow:
    1.  Edit/add resources in `README.md`.
    2.  Regenerate machine-readable artifacts:
        *   `python scripts/sync_resources_from_readme.py`
        *   `python scripts/build_resources.py`
    3.  Commit updated data files (`data/resources.yml`, `data/resources.json`, `data/resources.csv`, `docs/data/resources.json`) with your README change.
*   Contribution guide: [`contributing.md`](https://github.com/inoue0426/awesome-computational-biology/blob/main/README.md/./contributing.md).

## [Apr 16, 2026](/content/2026/04/16/README.md)

### Preprocessing Tools

*   [Numbat (⭐211)](https://github.com/kharchenkolab/numbat) — Haplotype-aware copy number variation inference from single-cell RNA-seq using hidden Markov models.
*   [CaSpER (⭐87)](https://github.com/akdess/CaSpER) — CNV identification and visualization by integrative analysis of single-cell or bulk RNA-seq data.
*   [CellCharter (⭐168)](https://github.com/CSOgroup/cellcharter) — Identification and characterization of spatial cell niches from spatial transcriptomics using VAEs and Gaussian mixture models.
*   [STAGATE (⭐51)](https://github.com/RucDongLab/STAGATE) — Adaptive graph attention auto-encoder for spatial domain identification in spatial transcriptomics.
*   [NCEM (⭐117)](https://github.com/theislab/ncem) — GNN-based model for learning intercellular communication from spatial graphs of cells.
*   [DeepTalk (⭐29)](https://github.com/JiangBioLab/DeepTalk) — Graph attention network for deciphering cell-cell communication from spatial transcriptomics data.
*   [COMMOT (⭐136)](https://github.com/zcang/COMMOT) — Optimal transport-based framework for screening cell-cell communication in spatial transcriptomics.
*   [TIGON (⭐57)](https://github.com/yutongo/TIGON) — Neural optimal transport method for reconstructing growth and dynamic trajectories from single-cell transcriptomics.
*   [LINGER (⭐127)](https://github.com/Durenlab/LINGER) — Neural network for gene regulatory network inference from single-cell multiome (RNA+ATAC-seq) data with bulk data pretraining.
*   [sciPENN (⭐18)](https://github.com/jlakkis/sciPENN) — RNN-based method for simultaneous protein expression prediction, uncertainty estimation, and cell-type label transfer from CITE-seq and scRNA-seq data.
*   [MOGONET (⭐179)](https://github.com/txWang/MOGONET) — Multi-omics graph convolutional network framework for patient classification and biomarker identification.

### Drug Response Prediction

*   [PRNet (⭐78)](https://github.com/Perturbation-Response-Prediction/PRnet) — Deep generative model for predicting transcriptional responses to novel chemical perturbations for drug discovery.
*   [DRUML (⭐11)](https://github.com/CutillasLab/DRUMLR) — Ensemble machine learning framework combining standard ML with deep learning to systematically rank anti-cancer drugs from proteomics and RNA-seq data.

### Drug Repurposing

*   [TranSiGen (⭐34)](https://github.com/myzhengSIMM/TranSiGen) — Dual-VAE architecture for ligand-based virtual screening, drug response prediction, and drug repurposing using chemical-induced transcriptional profiles.

### Molecular Generation

*   [DiffSBDD (⭐500)](https://github.com/arneschneuing/DiffSBDD) — Equivariant diffusion model for structure-based drug design that generates molecules and binding conformations for protein targets.
*   [ReLeaSE (⭐367)](https://github.com/isayev/ReLeaSE) — Deep reinforcement learning framework for de novo drug design combining a generative and predictive model.
*   [PaccMannRL (⭐10)](https://github.com/PaccMann/paccmann_generator) — Reinforcement learning-based generative model for de novo hit-like anticancer molecule design from transcriptomic data.

### Single-cell Foundation Models / Transcriptomics Foundation Models

*   [SATURN (⭐164)](https://github.com/snap-stanford/SATURN) — Transformer-based model integrating gene expression and protein sequences via a protein language model to learn unified multi-species cell embeddings.
*   [CancerFoundation (⭐29)](https://github.com/BoevaLab/CancerFoundation) — Single-cell RNA-seq foundation model trained exclusively on a curated dataset of malignant cells to learn cancer-specific embeddings.

### Single-cell Foundation Models / Spatial Foundation Models

*   [Nicheformer (⭐159)](https://github.com/theislab/nicheformer) — Foundation model for single-cell and spatial omics using a transformer architecture with positional embeddings to encode spatial cell information.
*   [scGPT-spatial (⭐133)](https://github.com/bowang-lab/scGPT-spatial) — Extension of scGPT for spatial transcriptomics with continual pretraining and a mixture-of-experts decoder for spatial gene expression analysis.

### Single-cell Foundation Models / Multi-Omics Foundation Models

*   [Concerto (⭐40)](https://github.com/melobio/Concerto-reproducibility) — Contrastive self-supervised learning framework for single-cell multimodal data integration, batch correction, and reference-query mapping.
*   [scButterfly (⭐28)](https://github.com/BioX-NKU/scButterfly) — Dual-aligned variational autoencoder for single-cell cross-modality translation between paired and unpaired multiomics data.
*   [JAMIE (⭐16)](https://github.com/Oafish1/JAMIE) — Joint variational autoencoder for multimodal single-cell data imputation and embedding.
*   [scPair (⭐10)](https://github.com/quon-titative-biology/scPair) — Bidirectional feedforward network for single-cell multimodal analysis with cross-modality prediction leveraging single-cell atlases.

### Multi-Modal Foundation Models / Protein Structure Prediction and Design

*   [PORPOISE (⭐241)](https://github.com/mahmoodlab/PORPOISE) — Pan-cancer integrative histology-genomic analysis framework using multimodal deep learning for patient stratification.
*   [PathomicFusion (⭐330)](https://github.com/mahmoodlab/PathomicFusion) — Integrated framework fusing histopathology and genomic features via CNN, GNN, and attention gating for cancer diagnosis and prognosis.
*   [Virchow](https://huggingface.co/paige-ai/Virchow) — Million-slide digital pathology foundation model using a vision transformer and self-supervised distillation for tile-level pathology image representation.
*   [TOAD (⭐182)](https://github.com/mahmoodlab/TOAD) — Tumor Origin Assessment via Deep-learning; weakly-supervised multi-task model predicting cancer primary origin from H\&E whole-slide images.
*   [PLIP (⭐375)](https://github.com/PathologyFoundation/plip) — Vision-language foundation model for pathology trained with contrastive learning on pathology image–text pairs for image classification and text-to-image retrieval.
*   [MUSK (⭐226)](https://github.com/lilab-stanford/MUSK) — Vision-language foundation model for precision oncology analyzing multimodal paired text and pathology image data for biomarker prediction and retrieval.

## [Mar 31, 2026](/content/2026/03/31/README.md)

### Compound

*   [DrugTargetCommons](https://drugtargetcommons.fimm.fi/) — Community platform for curating and integrating experimental bioactivity data across drugs and targets.

### Protein

*   [UniRef](https://www.uniprot.org/uniref/) — Non-redundant sequence database clustering UniProtKB entries at multiple sequence identity thresholds.
*   [InterPro](https://www.ebi.ac.uk/interpro/) — Protein families, domains, and functional sites database integrating 14 member databases including Pfam and PROSITE.
*   [Pfam](https://www.ebi.ac.uk/interpro/entry/pfam/) — Database of protein families described by multiple sequence alignments and hidden Markov models.
*   [NeXtProt](https://www.nextprot.org/) — Expert knowledge base on human proteins with deep functional annotation, complementary to UniProt.

### Genome

*   [ROADMAP Epigenomics](http://www.roadmapepigenomics.org/) — Reference epigenome maps for 111 primary human cell types and tissues, including histone modifications, chromatin accessibility, and DNA methylation.
*   [FANTOM5](https://fantom.gsc.riken.jp/5/) — Functional annotation of mammalian genome; comprehensive atlas of active enhancers, promoters, and transcription start sites across human and mouse cell types.

### Disease

*   [Open Targets Platform](https://platform.opentargets.org/) — Systematic target identification and prioritization platform integrating genetics, genomics, and drug data for drug discovery.
*   [Human Phenotype Ontology (HPO)](https://hpo.jax.org/) — Standardized vocabulary of phenotypic abnormalities in human disease, linking genes, variants, and clinical features.
*   [DISEASES](https://diseases.jensenlab.org/) — Gene–disease association database integrating evidence from text mining, curated databases, and experimental data.

### Chemical-Protein Interaction

*   [Davis kinase inhibitors DB](http://staff.cs.utu.fi/~aijrinas/dti/) — Experimental kinase inhibitor binding affinity dataset for protein–ligand interaction research.
*   [Kinase Inhibitor Bioactivity Data (KIBA)](https://janeliascicomp.github.io/KIBA/) — Integrated bioactivity scores for kinase inhibitors combining Ki, Kd, and IC50 measurements.

### Gene Regulatory Network

*   [TRRUST](https://www.grnpedia.org/trrust/) — Manually curated database of human and mouse transcriptional regulatory interactions between transcription factors and their target genes.
*   [RegNetwork](http://www.regnetworkweb.org/) — Database of gene regulatory networks covering transcription factor–target gene and miRNA–gene interaction data across multiple species.
*   [miRBase](https://www.mirbase.org/) — Reference repository for microRNA gene annotations, sequences, and experimentally validated targets.

### Benchmarks & Datasets

*   [PK-DB](https://pk-db.com/) — Open database of experimental pharmacokinetics (PK) and ADME data from clinical and preclinical studies.

### Preprocessing Tools

*   [STAR (⭐2.2k)](https://github.com/alexdobin/STAR) — Ultrafast universal RNA-seq aligner with support for spliced alignment and single-cell quantification via STARsolo.
*   [kallisto](https://pachterlab.github.io/kallisto/) — Near-optimal RNA-seq quantification using pseudoalignment for fast transcript abundance estimation.
*   [Harmony (⭐635)](https://github.com/immunogenomics/harmony) — Fast and scalable integration of single-cell data across datasets, conditions, technologies, and species.
*   [Monocle3](https://cole-trapnell-lab.github.io/monocle3/) — Single-cell trajectory analysis tool for learning developmental trajectories and ordering cells in pseudotime.
*   [CellChat (⭐776)](https://github.com/sqjin/CellChat) — Inference and analysis of cell-cell communication ligand-receptor networks from single-cell transcriptomics data.
*   [SCENIC (⭐481)](https://github.com/aertslab/SCENIC) — Single-cell regulatory network inference and clustering linking transcription factors to co-expressed gene modules.
*   [DoubletFinder (⭐540)](https://github.com/chris-mcginnis-ucsf/DoubletFinder) — Machine learning approach for detecting multiplet (doublet) artifacts in single-cell RNA-seq data.

### Drug Response Prediction

*   [TGSA (⭐23)](https://github.com/violet-sto/TGSA) — Tumor gene set and attention-based model leveraging biological pathway knowledge for drug response prediction.
*   [HiDRA](https://github.com/bsml320/HiDRA) — Hierarchical network model incorporating gene and pathway-level information for cancer drug response prediction.

### Molecular Generation

*   [JTVAE (⭐555)](https://github.com/wengong-jin/icml18-jtnn) — Junction tree variational autoencoder for molecular graph generation that guarantees chemical validity via a hierarchical tree decomposition.

### LLM for Biology

*   [MolT5 (⭐192)](https://github.com/blender-nlp/MolT5) — Language model for molecular tasks bridging text and SMILES, enabling molecule captioning and text-driven molecule generation.
*   [ChatDrug (⭐161)](https://github.com/chao1224/ChatDrug) — LLM-based conversational pipeline for drug discovery, using natural language prompts for iterative drug editing and optimization.

### Protein Foundation Models / Pre-trained Embedding

*   [ProtTrans (⭐1.3k)](https://github.com/agemagician/ProtTrans) — Suite of protein language models (ProtBERT, ProtT5, ProtXLNet) trained on billions of protein sequences from UniRef and BFD.
*   [ProGen2 (⭐697)](https://github.com/salesforce/progen) — Protein language model trained on diverse protein families for sequence generation and fitness prediction.
*   [Ankh (⭐246)](https://github.com/agemagician/Ankh) — Efficient protein language model optimized for downstream prediction tasks including secondary structure, localization, and function annotation.

### Genomics Foundation Models / Protein Structure Prediction and Design

*   [DeepSEA](http://deepsea.princeton.edu/) — Deep learning framework for predicting chromatin effects of sequence alterations with single-nucleotide sensitivity across thousands of chromatin features.
*   [Sei (⭐113)](https://github.com/FunctionLab/sei-framework) — Sequence-to-function framework learning a genome-wide regulatory activity code from DNA sequences for variant effect prediction.
*   [GPN (Genomic Pre-trained Network) (⭐338)](https://github.com/songlab-cal/gpn) — Masked language model for DNA sequences enabling zero-shot variant effect prediction without requiring functional annotations.

## [Mar 13, 2026](/content/2026/03/13/README.md)

### Protein Foundation Models / Protein Structure Prediction and Design

*   [EvoDiff (⭐666)](https://github.com/microsoft/evodiff) — Discrete diffusion framework for protein sequence generation trained on evolutionary-scale data, supporting unconditional generation, disordered region design, and functional motif scaffolding. \[ [paper-2023](https://www.biorxiv.org/content/10.1101/2023.09.11.556673v1) ]

## [Mar 11, 2026](/content/2026/03/11/README.md)

### Benchmarks & Datasets

*   [1000 Genomes Project](https://www.internationalgenome.org/) — Reference panel of human genetic variation from 2,504 individuals across 26 populations.
*   [BACE](https://www.kaggle.com/datasets/gokturkkoch/bace) — Binary classification and regression dataset for β-secretase 1 (BACE-1) inhibitor binding affinity.
*   [BEAT AML](https://biodev.github.io/BeatAML2/) — Functional ex vivo drug sensitivity measurements paired with genomics for acute myeloid leukemia.
*   [ClinTox](https://tdcommons.ai/single_pred_tasks/tox/#clintox) — Clinical toxicity dataset contrasting FDA-approved drugs with those that failed clinical trials due to toxicity.
*   [CPTAC (Clinical Proteomic Tumor Analysis Consortium)](https://proteomics.cancer.gov/programs/cptac) — Multi-omic proteogenomic datasets for multiple cancer types linking proteomics with genomics.
*   [FLIP (Fitness Landscape Inference for Proteins) (⭐120)](https://github.com/J-SNACKKB/FLIP) — Benchmark collection of protein fitness landscape datasets for evaluating protein ML models.
*   [LINCS L1000](https://lincsproject.org/LINCS/tools/workflows/find-the-best-place-to-obtain-the-lincs-l1000-data) — Gene expression profiles (978 landmark genes) for >20,000 chemical and genetic perturbations across cell lines.
*   [OGB (Open Graph Benchmark)](https://ogb.stanford.edu/) — Large-scale graph ML benchmark suite including biological datasets such as ogbl-ppa (protein-protein associations) and ogbg-molhiv.
*   [PharmGKB](https://www.pharmgkb.org/) — Curated pharmacogenomics dataset linking genetic variants to drug response phenotypes across thousands of drugs.
*   [PRISM](https://depmap.org/portal/prism/) — Cancer drug sensitivity profiling of >4,500 drugs across >900 cancer cell lines using pooled-cell-line barcoding.
*   [ProteinGym (⭐415)](https://github.com/OATML-Markslab/ProteinGym) — Large-scale benchmark of deep mutational scanning assays for evaluating protein fitness landscape models.
*   [QM9](https://figshare.com/collections/Quantum_chemistry_structures_and_properties_of_134_kilo_molecules/978904) — Quantum chemistry properties for 134K stable small organic molecules computed at DFT level.
*   [scIB (Single-cell Integration Benchmarks) (⭐410)](https://github.com/theislab/scib) — Comprehensive benchmarking framework for single-cell data integration methods.
*   [SIDER (Side Effect Resource)](http://sideeffects.embl.de/) — Database of 1,430 approved drugs with their recorded adverse drug reactions across 27 system-organ classes.
*   [Tabula Muris](https://tabula-muris.ds.czbiohub.org/) — Comprehensive single-cell atlas of 20 mouse organs and tissues, enabling cross-tissue and cross-species comparisons.
*   [Tabula Sapiens](https://tabula-sapiens-portal.ds.czbiohub.org/) — Comprehensive human single-cell atlas of \~500K cells from 24 organs and tissues across multiple donors.
*   [TAPE (Tasks Assessing Protein Embeddings) (⭐736)](https://github.com/songlab-cal/tape) — Benchmark suite of five biologically meaningful semi-supervised learning tasks for evaluating protein representations.
*   [The Cancer Genome Atlas (TCGA)](https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga) — Comprehensive multi-omics (genomics, transcriptomics, proteomics, methylation) dataset for 33 cancer types across \~11,000 patients.
*   [Tox21](https://tripod.nih.gov/tox21/challenge/) — 12,707 compounds tested in 12 nuclear receptor and stress-response pathway biochemical assays for toxicity prediction.
*   [UK Biobank](https://www.ukbiobank.ac.uk/) — Large-scale biomedical database of \~500K participants with genetic, imaging, and health data for population genetics and disease studies.

### Preprocessing Tools

*   [scVelo (⭐496)](https://github.com/theislab/scvelo) — RNA velocity estimation for single-cell transcriptomics, inferring the direction and speed of cell differentiation.

### Drug Response Prediction

*   [RECOVER (⭐24)](https://github.com/RECOVERcoalition/Recover) — Machine learning framework for predicting synergistic drug combination responses across cell lines.

### Molecular Generation

*   [DiffDock (⭐1.5k)](https://github.com/gcorso/DiffDock) — Diffusion generative model for molecular docking, predicting the binding pose of small molecules to protein targets.

### LLM for Biology

*   [BioMedLM](https://huggingface.co/stanford-crfm/BioMedLM) — 2.7B parameter GPT-2-style language model trained exclusively on biomedical literature from PubMed for biomedical question answering and text generation.

### Single-cell Foundation Models / Transcriptomics Foundation Models

*   [UCE (⭐252)](https://github.com/snap-stanford/UCE) — Universal Cell Embeddings: zero-shot single-cell embedding model trained on 36M cells across species, tissues, and assays without fine-tuning.
*   [GEARS (⭐354)](https://github.com/snap-stanford/GEARS) — Graph-based model for predicting transcriptional responses to single and combinatorial genetic perturbations using biological priors.

### Protein Foundation Models / Protein Structure Prediction and Design

*   [OpenFold (⭐3.3k)](https://github.com/aqlaboratory/openfold) — Trainable, memory-efficient open-source reproduction of AlphaFold2 enabling custom protein structure prediction workflows.
*   [SaProt](https://github.com/westlake-reup/SaProt) — Structure-aware protein language model using structure-aware tokens that encode both sequence and backbone geometry for improved function prediction.

### Genomics Foundation Models / Protein Structure Prediction and Design

*   [Borzoi (⭐235)](https://github.com/calico/borzoi) — Extended successor to Enformer for predicting RNA-seq coverage from long genomic sequence windows (524 kb) with improved resolution.

## [Mar 03, 2026](/content/2026/03/03/README.md)

### scRNA

*   [CZ CELLxGENE](https://cellxgene.cziscience.com/) — Single-cell dataset repository and interactive explorer from the Chan Zuckerberg Initiative.
*   [Human Cell Atlas](https://www.humancellatlas.org/) — Open global atlas of all cells in the human body.

### Compound

*   [HMDB (Human Metabolome Database)](https://hmdb.ca/) — Comprehensive database of small molecule metabolites found in the human body.
*   [DrugCentral](http://drugcentral.org/) — Online drug compendium with drug mode of action and indication information.

### Protein

*   [SAbDab](https://opig.stats.ox.ac.uk/webapps/sabdab-sabpred/sabdab) — Structural Antibody Database containing all antibody structures in the PDB.
*   [OADB (Observed Antibody Space Database)](http://opig.stats.ox.ac.uk/webapps/oas/) — Database of antibody sequences from immune repertoire sequencing.

### Genome

*   [ENCODE](https://www.encodeproject.org/) — Encyclopedia of DNA Elements; regulatory and functional genomic elements across the genome.
*   [Ensembl](https://www.ensembl.org/) — Genome browser and annotation database for vertebrate and other eukaryotic genomes.
*   [gnomAD](https://gnomad.broadinstitute.org/) — Genome Aggregation Database; genetic variation from large-scale sequencing projects.
*   [Rfam](https://rfam.org/) — Database of RNA families with sequence alignments and consensus structures.

### Disease

*   [DisGeNET](https://www.disgenet.org/) — Database of gene-disease associations integrating expert-curated and GWAS data.
*   [OMIM (Online Mendelian Inheritance in Man)](https://www.omim.org/) — Comprehensive database of human genes and genetic disorders.

### Protein-Protein Interaction

*   [IntAct](https://www.ebi.ac.uk/intact/home) — Open-source molecular interaction database and analysis system from EMBL-EBI.

### Benchmarks & Datasets

*   [BindingDB Curated Sets](https://www.bindingdb.org/rwd/bind/chemsearch/marvin/SDFdownload.jsp?all_download=yes) — Curated binding affinity datasets for protein–ligand interaction benchmarking.
*   [Cancer Therapeutics Response Portal (CTRP)](https://portals.broadinstitute.org/ctrp/) — Drug sensitivity profiles across \~900 cancer cell lines for >400 compounds.
*   [GuacaMol (⭐513)](https://github.com/BenevolentAI/guacamol) — Benchmark suite for generative molecular design models.
*   [MOSES (⭐964)](https://github.com/molecularsets/moses) — Benchmarking platform for molecular generation models.
*   [Therapeutics Data Commons (TDC)](https://tdcommons.ai/) — Unified benchmark suite covering ADMET, drug-target interaction, drug response, and more.

### Preprocessing Tools

*   [Biopython](https://biopython.org/) — Collection of Python tools for biological computation including sequence analysis, structure parsing, and database access.
*   [DeepChem (⭐6.7k)](https://github.com/deepchem/deepchem) — Deep learning library for drug discovery, quantum chemistry, and materials science.
*   [scvi-tools](https://scvi-tools.org/) — Probabilistic models for single-cell omics data analysis.
*   [CellTypist (⭐470)](https://github.com/Teichlab/celltypist) — Automated cell type annotation for scRNA-seq.
*   [GROMACS](https://www.gromacs.org/) — Molecular dynamics simulation package for biochemical molecules.
*   [MDAnalysis](https://www.mdanalysis.org/) — Python library for analyzing and altering molecular dynamics simulation trajectories.
*   [OpenMM](https://openmm.org/) — High-performance toolkit for molecular simulation and GPU-accelerated MD.

### Molecular Generation

*   [REINVENT (⭐372)](https://github.com/MolecularAI/Reinvent) — Reinforcement learning for de novo drug design.
*   [MolGPT (⭐169)](https://github.com/devalab/molgpt) — Transformer-based model for molecular generation.
*   [Molecular Transformer (⭐420)](https://github.com/pschwllr/MolecularTransformer) — Sequence-to-sequence model for retrosynthesis prediction.
*   [TargetDiff (⭐333)](https://github.com/guanjq/targetdiff) — 3D equivariant diffusion model for structure-based drug design.

### LLM for Biology

*   [ClawBio (⭐717)](https://github.com/ClawBio/ClawBio) — Bioinformatics-native AI agent skill library with local-first pharmacogenomics, ancestry PCA, semantic similarity, nutrigenomics, and metagenomics skills.

### Single-cell Foundation Models / Transcriptomics Foundation Models

*   [Geneformer](https://huggingface.co/ctheodoris/Geneformer) — Context-aware, attention-based deep learning model pretrained on a large corpus of single-cell transcriptomes.
*   [scBERT (⭐356)](https://github.com/TencentAILabHealthcare/scBERT) — BERT-based foundation model pretrained on large-scale scRNA-seq data for cell type annotation.
*   [CellPLM (⭐102)](https://github.com/OmicsML/CellPLM) — Cell pre-trained language model with inter-cell transformer architecture for diverse single-cell analysis tasks.

### Single-cell Foundation Models / Spatial Foundation Models

*   [GigaPath (⭐592)](https://github.com/prov-gigapath/prov-gigapath) — Slide-level digital pathology foundation model pretrained on 1.3 billion pathology image tokens from whole-slide images.
*   [UNI (⭐712)](https://github.com/mahmoodlab/UNI) — General-purpose self-supervised pathology foundation model trained on 100K+ whole-slide images for diverse computational pathology tasks.
*   [CONCH (⭐490)](https://github.com/mahmoodlab/CONCH) — Vision-language foundation model for computational pathology trained with contrastive captioning on pathology image–text pairs.
*   [Phikon](https://huggingface.co/owkin/phikon) — ViT-based pathology foundation model pretrained with iBOT self-supervision on TCGA whole-slide images.

### Single-cell Foundation Models / Multi-Omics Foundation Models

*   [scMulan (⭐61)](https://github.com/SuperBianC/scMulan) — Single-cell multi-omic language model pretrained on \~10M cells spanning transcriptomics, epigenomics, and proteomics for cross-omics transfer tasks.
*   [totalVI (⭐1.6k)](https://github.com/scverse/scvi-tools) — Probabilistic framework for joint analysis of paired scRNA-seq and protein (CITE-seq) data enabling multi-modal cell state representation across single-cell datasets.
*   [MultiVI (⭐1.6k)](https://github.com/scverse/scvi-tools) — Multi-modal variational autoencoder for integrating paired and unpaired single-cell RNA-seq and ATAC-seq measurements into a unified latent space.
*   [MIRA (⭐68)](https://github.com/cistrome/MIRA) — Probabilistic multimodal topic model jointly modeling single-cell transcriptomics and chromatin accessibility for regulatory network inference.
*   [GLUE (⭐462)](https://github.com/gao-lab/GLUE) — Graph-Linked Unified Embedding framework for unpaired single-cell multi-omics data integration across RNA, ATAC, methylation, and protein modalities.
*   [BABEL (⭐48)](https://github.com/wukevin/babel) — Cross-modality translation model enabling prediction between scRNA-seq and scATAC-seq profiles without requiring paired single-cell measurements.
*   [Multigrate (⭐32)](https://github.com/theislab/multigrate) — Asymmetric multi-omics variational autoencoder for integrating single-cell data across RNA, ATAC, and protein modalities with missing-modality support.
*   [MOFA+ (⭐394)](https://github.com/bioFAM/MOFA2) — Multi-Omics Factor Analysis framework identifying shared axes of variation across bulk and single-cell datasets including RNA, ATAC, proteomics, methylation, and copy number.
*   [GeneCompass (⭐114)](https://github.com/xCompass-AI/GeneCompass) — Large-scale foundation model integrating DNA regulatory sequences and single-cell transcriptomics from 120M+ cells across multiple species for gene regulation prediction.
*   [UnitedNet (⭐52)](https://github.com/LiuLab-Bioelectronics-Harvard/UnitedNet) — Interpretable multi-task deep neural network for single-cell multi-omics integration spanning transcriptomics, chromatin accessibility, and proteomics.
*   [SpatialGlue](https://github.com/zhanglabtools/SpatialGlue) — Graph attention network for spatial multi-omics integration jointly embedding spatial transcriptomics with chromatin accessibility or proteomics.
*   [MIDAS (⭐64)](https://github.com/labomics/midas) — Mosaic integration and differential accessibility model for single-cell multi-omics data that handles arbitrary missing-modality combinations across transcriptomics, chromatin accessibility, and proteomics.

### Single-cell Foundation Models / Domain Alignment

*   [scArches (⭐402)](https://github.com/theislab/scarches) — Transfer learning framework for mapping new single-cell datasets onto pre-trained reference atlases across batches, conditions, and modalities.
*   [TOSICA](https://github.com/JackieHanlaopo/TOSICA) — Transformer-based framework for one-stop interpretable cell-type annotation supporting cross-dataset and cross-species transfer.

### Protein Foundation Models / Protein Structure Prediction and Design

*   [AlphaFold3 (⭐7.8k)](https://github.com/google-deepmind/alphafold3) — Predicts structures of proteins, nucleic acids, small molecules, and their complexes.
*   [Boltz-1 (⭐3.9k)](https://github.com/jwohlwend/boltz) — Open-source all-atom biomolecular structure prediction model for proteins, nucleic acids, small molecules, and their complexes achieving AlphaFold3-level accuracy.
*   [Chai-1 (⭐1.9k)](https://github.com/chaidiscovery/chai-lab) — Unified molecular structure prediction model covering proteins, nucleic acids, small molecules, and complexes.
*   [ESM3 (⭐2.3k)](https://github.com/evolutionaryscale/esm) — Multimodal protein language model that jointly reasons over sequence, structure, and function for generative protein design and engineering.
*   [ESMFold (⭐4k)](https://github.com/facebookresearch/esm) — Fast protein structure prediction using language model embeddings.
*   [RFdiffusion (⭐2.8k)](https://github.com/RosettaCommons/RFdiffusion) — Generative model for protein backbone design using diffusion.
*   [ProteinMPNN (⭐1.7k)](https://github.com/dauparas/ProteinMPNN) — Deep learning model for protein sequence design given backbone structure.
*   [OmegaFold (⭐618)](https://github.com/HeliXonProtein/OmegaFold) — High-resolution de novo protein structure prediction from sequence.
*   [RoseTTAFold (⭐2.2k)](https://github.com/RosettaCommons/RoseTTAFold) — Three-track neural network for protein structure prediction.

### Multi-Modal Foundation Models / Protein Structure Prediction and Design

*   [CHIEF (⭐703)](https://github.com/hms-dbmi/CHIEF) — Clinical Histopathology Imaging Evaluation Foundation model integrating histology images and clinical context for pan-cancer analysis.
*   [BiomedCLIP](https://huggingface.co/microsoft/BiomedCLIP-PubMedBERT_256-vit_g_14) — CLIP-based vision-language foundation model for biomedical images and text trained on PubMed figure–caption pairs.

### Genomics Foundation Models / Protein Structure Prediction and Design

*   [Nucleotide Transformer (⭐851)](https://github.com/instadeepai/nucleotide-transformer) — Foundation model for genomic sequences across multiple species.
*   [DNABERT (⭐750)](https://github.com/jerryji1993/DNABERT) — Pre-trained bidirectional encoder for DNA sequence analysis.
*   [DNABERT-2 (⭐475)](https://github.com/Zhihan1996/DNABERT_2) — Improved genome foundation model with efficient tokenization.
*   [Enformer (⭐15k)](https://github.com/deepmind/deepmind-research/tree/master/enformer) — Transformer model predicting gene expression from DNA sequence.
*   [Basenji (⭐468)](https://github.com/calico/basenji) — Sequential regulatory activity prediction from DNA sequences.
*   [Caduceus (⭐232)](https://github.com/kuleshov-group/caduceus) — Bidirectional equivariant long-range DNA sequence model based on Mamba.
*   [Evo (⭐1.5k)](https://github.com/evo-design/evo) — Long-context genomic foundation model (up to 1M tokens).
*   [HyenaDNA (⭐777)](https://github.com/HazyResearch/hyena-dna) — Long-range genomic foundation model handling sequences up to 1M tokens with sub-quadratic attention.

## [Feb 08, 2026](/content/2026/02/08/README.md)

### Pathway

*   [Reactome](https://reactome.org/) — Expert-curated, peer-reviewed pathway database with detailed reaction mechanisms.
*   [BioCyc](https://biocyc.org/) — Collection of pathway/genome databases across thousands of organisms.
*   [SIGNOR](https://signor.uniroma2.it/) — Database of causal signaling interactions and pathways.
*   [MSigDB (Molecular Signatures Database)](https://www.gsea-msigdb.org/gsea/msigdb) — Curated gene sets derived from pathways and biological processes.

### Protein

*   [PROTEIN DATA BANK (PDB)](https://www.rcsb.org/) — 3D structures of proteins, nucleic acids, complexes.
*   [RCSB Protein Data Bank](https://www.rcsb.org/) — Repository for structural data of biological molecules.

### Disease

*   [DrugBank](https://go.drugbank.com/) — Database of drugs and targets (University of Alberta).

### Drug-Gene Interaction

*   [Comparative Toxicogenomics Database](http://ctdbase.org/) — Chemical-gene interactions, chemical-disease and gene-disease associations, chemical-phenotype associations.
*   [SNAP](https://snap.stanford.edu/biodata/datasets/10002/10002-ChG-Miner.html) — Dataset of drug-gene interactions.

### Benchmarks & Datasets

*   [Genomics of Drug Sensitivity in Cancer (GDSC)](https://www.cancerrxgene.org/) — Drug sensitivity for \~1000 human cancer cell lines and hundreds of compounds.
*   [CrossDocked2020](https://arxiv.org/abs/2001.01037) — Large-scale dataset for structure-based virtual screening.
*   [OpenBioLink (⭐159)](https://github.com/OpenBioLink/OpenBioLink) — Benchmark datasets for biological knowledge graph completion.

### Drug (Cell Line) Response

*   [Cancer Cell Line Encyclopedia](https://sites.broadinstitute.org/ccle/) — Database of \~1000 cancer cell lines.
*   [CellMiner Cross Database (CellMinerCDB)](https://discover.nci.nih.gov/cellminercdb/) — Integrates multiple cancer cell line databases.

### Chemical-Protein Interaction

*   [BindingDB](https://www.bindingdb.org/rwd/bind/index.jsp) — Compounds and target database.
*   [PDBBind](https://www.pdbbind-plus.org.cn/) — Binding affinity data for biomolecular complexes.

### Protein-Protein Interaction

*   [BioGRID](https://thebiogrid.org/) — Protein, genetic, and chemical interactions.
*   [HIPPIE](http://cbdm-01.zdv.uni-mainz.de/~mschaefer/hippie/) — Human protein-protein interaction database.

### Knowledge Graph

*   [DRKG (⭐680)](https://github.com/gnn4dr/DRKG) — Large-scale biological knowledge graph for drug discovery.
*   [Hetionet (⭐350)](https://github.com/hetio/hetionet) — Heterogeneous network integrating genes, diseases, drugs, pathways, and more.
*   [PrimeKG (⭐732)](https://github.com/mims-harvard/PrimeKG) — Multi-modal precision medicine knowledge graph integrating clinical, genetic, and drug data.

### API

*   [PubMed E-utilities (esearch/efetch)](https://www.nlm.nih.gov/dataguide/edirect/esearch.html) — APIs for searching and retrieving biomedical literature from PubMed.
*   [NCBI E-utilities](https://www.ncbi.nlm.nih.gov/books/NBK25501/) — Unified APIs for accessing NCBI databases (Gene, GEO, SRA, PubChem, etc).
*   [UniProt REST API](https://www.uniprot.org/help/api) — Programmatic access to protein sequence and functional annotation data.
*   [Ensembl REST API](https://rest.ensembl.org/) — API for genomic annotations, variants, genes, and comparative genomics.
*   [KEGG REST API](https://www.kegg.jp/kegg/rest/keggapi.html) — API for accessing KEGG pathways, compounds, genes, and reactions.
*   [ChEMBL Web Services](https://www.ebi.ac.uk/chembl/ws) — REST API for bioactive molecules, targets, and bioassays.
*   [Open Targets Platform API](https://platform.opentargets.org/api) — API for target–disease associations integrating genetics, genomics, and drug data.
*   [ClinicalTrials.gov API](https://clinicaltrials.gov/api/gui) — API for querying clinical trial metadata and results.

### Drug Target Interaction

*   [DTINet (⭐188)](https://github.com/luoyunan/DTINet) — Network-based framework integrating heterogeneous biological data for DTI prediction.
*   [DeepDTA (⭐298)](https://github.com/hkmztrk/DeepDTA) — Deep learning model using CNNs on protein sequences and drug SMILES.
*   [GraphDTA (⭐297)](https://github.com/thinng/GraphDTA) — Graph neural network–based DTI prediction using molecular graphs.
*   [MolTrans (⭐229)](https://github.com/kexinhuang12345/MolTrans) — Transformer-based DTI model leveraging molecular substructures.
*   [DrugBAN (⭐143)](https://github.com/peizhenbai/DrugBAN) — Bilinear attention network for interpretable DTI prediction.

### Protein Foundation Models / Pre-trained Embedding

*   [Evolutionary Scale Modeling (ESM) (⭐4k)](https://github.com/facebookresearch/esm) — Protein embeddings.

## [Jan 07, 2026](/content/2026/01/07/README.md)

### Preprocessing Tools

*   [ChatSpatial (⭐30)](https://github.com/cafferychen777/ChatSpatial) — MCP server for spatial transcriptomics analysis via natural language.

### Single-cell Foundation Models / Transcriptomics Foundation Models

*   [scFoundation (⭐405)](https://github.com/biomap-research/scFoundation) — Large-scale foundation model for single-cell gene expression, enabling multiple downstream tasks.
*   [scGPT (⭐1.5k)](https://github.com/bowang-lab/scGPT) — Transformer-based foundation model pretrained on millions of single-cell profiles.
*   [BulkFormer (⭐54)](https://github.com/KangBoming/BulkFormer) — Foundation model for bulk RNA-seq data; learns general transcriptomic representations.

## [Jan 03, 2026](/content/2026/01/03/README.md)

### Preprocessing Tools

*   [FlashDeconv (⭐14)](https://github.com/cafferychen777/flashdeconv) — High-performance spatial transcriptomics deconvolution (\~1M spots in \~3 min).
*   [Squidpy](https://squidpy.readthedocs.io/) — Python library for spatial single-cell analysis.

## [Nov 17, 2024](/content/2024/11/17/README.md)

### Drug Response Prediction

*   [MOFGCN (⭐7)](https://github.com/weiba/MOFGCN/tree/main) — GCN + heterogeneous network.
*   [DeepDSC](https://ieeexplore-ieee-org.ezp2.lib.umn.edu/stamp/stamp.jsp?tp=\&arnumber=8723620\&tag=1) — Autoencoder + fully connected NN.
*   [DGDRP (⭐0)](https://github.com/minwoopak/heteronet) — Multi-view embedding neural network.
*   [DeepAEG (⭐3)](https://github.com/zhejiangzhuque/DeepAEG) — GNN embedding + attention mechanism.

## [Sep 01, 2024](/content/2024/09/01/README.md)

### Compound

*   [ZINC ligand discovery database](https://zinc.docking.org/) — Free database of commercially-available compounds for virtual screening.

### Protein

*   [Critical Assessment of Structure Prediction (CASP)](https://predictioncenter.org/) — Assessing methods for protein structure prediction.
*   [Uniclust](https://uniclust.mmseqs.com/) — Clustered protein sequence databases.
*   [CATH database](https://www.cathdb.info/) — Hierarchical classification of protein domain structures.

### Genome

*   [10x Genomics Dataset](https://www.10xgenomics.com/resources/datasets) — Collection of single-cell datasets.
*   [The Genotype-Tissue Expression (GTEx)](https://gtexportal.org/home/) — Human gene expression and regulation resource.
*   [Dependency Map (DepMap)](https://depmap.org/portal/) — CRISPR-Cas9 screens in cancer cell lines.
*   [Catalogue Of Somatic Mutations In Cancer (COSMIC)](https://cancer.sanger.ac.uk/cosmic) — Resource on somatic mutations in cancers.
*   [MGnify](https://www.ebi.ac.uk/metagenomics/) — Resource for metagenomic and metatranscriptomic data.
*   [JASPAR](http://jaspar.genereg.net/) — Database of transcription factor binding profiles.

### Clinical Trial

*   [ClinicalTrials.gov](https://clinicaltrials.gov/) — Privately and publicly funded clinical studies.
*   [ICD10](https://icd.who.int/browse10/2019/en) — International Classification of Diseases, 10th revision.
*   [EU Drug Regulating Authorities Clinical Trials DB (EudraCT)](https://eudract.ema.europa.eu/) — European clinical trial database.
*   [MIMIC-IV](https://mimic.mit.edu/) — Freely accessible critical care database.

### Benchmarks & Datasets

*   [MoleculeNet](http://moleculenet.ai/) — Benchmark datasets for molecular machine learning.

## [Aug 11, 2024](/content/2024/08/11/README.md)

### Compound

*   [Therapeutic Target Database](https://idrblab.net/ttd/full-data-download) — Drug-target, target-disease, and drug-disease datasets.

## [Aug 10, 2024](/content/2024/08/10/README.md)

### LLM for Biology

*   [scPRINT (⭐144)](https://github.com/cantinilab/scPRINT) — Pretrained on 50M cells for scRNA-seq denoising & zero imputation.

## [Jul 17, 2024](/content/2024/07/17/README.md)

### Knowledge Graph

*   [Drug Mechanism Database (DrugMechDB) (⭐72)](https://github.com/SuLab/DrugMechDB/tree/2.0.1) — Mechanisms of action from drug to disease.

### Drug Response Prediction

*   [drGAT (⭐1)](https://github.com/inoue0426/drGAT) — Attention-based model for drug response prediction with gene explainability.

### LLM for Biology

*   [GeneGPT (⭐424)](https://github.com/ncbi/GeneGPT) — LLM for biomedical information, integrated with various APIs.
*   [GenePT (⭐316)](https://github.com/yiqunchen/GenePT) — Foundation LLM for single-cell data.

## [Mar 17, 2024](/content/2024/03/17/README.md)

### LLM for Biology

*   [AI4Chem/ChemLLM-7B-Chat](https://huggingface.co/AI4Chem/ChemLLM-7B-Chat) — LLM for chemical & molecular science.
*   [BioGPT (⭐4.5k)](https://github.com/microsoft/BioGPT) — LLM for biomedical text generation.

### Protein Foundation Models / Pre-trained Embedding

*   [ChemBERTa-2 (⭐489)](https://github.com/seyonechithrananda/bert-loves-chemistry) — Chemical embeddings & prediction.

## [Nov 29, 2023](/content/2023/11/29/README.md)

### Compound

*   [Drug Repurposing Hub](https://repo-hub.broadinstitute.org/repurposing#download-data) — Collections of drug repurposing data (drug, MoA, target, etc).

### Protein

*   [AlphaFold Protein Structure Database](https://alphafold.ebi.ac.uk/api-docs) — 3D protein structure predictions.

### Protein-Protein Interaction

*   [STRING](https://string-db.org/) — PPI networks for multiple organisms.

## [Sep 07, 2023](/content/2023/09/07/README.md)

### Compound

*   [Rhea](https://www.rhea-db.org/) — Database of chemical reactions.

## [Jun 13, 2023](/content/2023/06/13/README.md)

### scRNA

*   [Single Cell Expression Atlas](https://www.ebi.ac.uk/gxa/sc/home) — Public database for single-cell RNA.

### Pathway

*   [PathwayCommons](https://www.pathwaycommons.org/) — Database of pathways and interactions.

### Genome

*   [cBioPortal](https://www.cbioportal.org/) — Cancer genomics database; aggregating many patient datasets.

### Preprocessing Tools

*   [Scanpy](https://scanpy.readthedocs.io/en/stable/) — Python library for scRNA-seq analysis.
*   [Seurat](https://satijalab.org/seurat/) — R library for scRNA-seq analysis.

## [Apr 17, 2023](/content/2023/04/17/README.md)

### scRNA

*   [Gene Expression Omnibus](https://www.ncbi.nlm.nih.gov/geo/) — Public functional genomics database.
*   [Single Cell PORTAL](https://singlecell.broadinstitute.org/single_cell) — Public database for single-cell RNA.

## [Dec 29, 2022](/content/2022/12/29/README.md)

### Benchmarks & Datasets

*   [NCI60](https://dtp.cancer.gov/discovery_development/nci-60/) — Drug sensitivity benchmark across 60 diverse human cancer cell lines.

## [May 18, 2022](/content/2022/05/18/README.md)

### Compound

*   [ChEBI](https://www.ebi.ac.uk/chebi/) — Database focused on small chemical compounds.

## [May 15, 2022](/content/2022/05/15/README.md)

### Compound

*   [PubChem](https://pubchem.ncbi.nlm.nih.gov/) — One of the largest chemical databases (compounds, genes, and proteins).
*   [ChEMBL](https://www.ebi.ac.uk/chembl/) — Bioactive molecules with drug-like properties.
*   [ChemSpider](http://www.chemspider.com/) — Chemical structure database.
*   [KEGG COMPOUND](https://www.genome.jp/kegg/compound/) — Collection of small molecules and biopolymers.
*   [LIPID MAPS](https://www.lipidmaps.org/databases/lmsd/overview) — Database of lipids.

### Pathway

*   [KEGG PATHWAY](https://www.genome.jp/kegg/pathway.html) — Collection of pathway maps.
*   [WikiPathways](https://wikipathways.org/) — Database of biological pathways.

### Mass Spectra

*   [MassBank](http://www.massbank.jp/) — Open source databases and tools for mass spectrometry reference spectra.
*   [MoNA MassBank of North America](https://mona.fiehnlab.ucdavis.edu/) — Meta-database of metabolite mass spectra, metadata, and associated compounds.

### Protein

*   [THE HUMAN PROTEIN ATLAS](https://www.proteinatlas.org/) — Comprehensive human protein database (cells, tissues, organs).
*   [UniProt](https://www.uniprot.org/) — Functional information on proteins.

### Genome

*   [Human Genome Resources at NCBI](https://www.ncbi.nlm.nih.gov/projects/genome/guide/human/index.shtml) — Database for genomics, proteomics, transcriptomics, and systems biology.
*   [GenBank](https://www.ncbi.nlm.nih.gov/genbank/) — NCBI's database of genetic sequences.
*   [UCSC Genome Browser](https://genome.ucsc.edu/) — UCSC's genome browser.

### Disease

*   [KEGG DRUG](https://www.genome.jp/kegg/drug/) — Comprehensive, approved drug information.

### Preprocessing Tools

*   [Chemistry Development Kit (⭐579)](https://github.com/cdk/cdk) — Cheminformatics software & machine learning tools.
*   [RDKit (⭐3.4k)](https://github.com/rdkit/rdkit) — Cheminformatics software & machine learning toolkit.

### Drug Repurposing

*   [DeepPurpose (⭐1.1k)](https://github.com/kexinhuang12345/DeepPurpose) — Deep learning library for drug repurposing.

### Drug Target Interaction

*   [NeoDTI (⭐77)](https://github.com/FangpingWan/NeoDTI) — Library for drug-target interaction prediction.

### Compound-Protein Interaction

*   [MCPINN (⭐3)](https://github.com/mhlee0903/multi_channels_PINN) — Drug discovery via compound-protein interaction and machine learning.
*   [TransformerCPI (⭐155)](https://github.com/lifanchen-simm/transformerCPI) — CPI prediction using Transformer.

## [Feb 22, 2022](/content/2022/02/22/README.md)

### Drug-Gene Interaction

*   [DGIdb](https://www.dgidb.org/) — Drug-gene interactions and the druggable genome.

### Chemical-Protein Interaction

*   [STITCH](http://stitch.embl.de/) — Chemical-protein interactions.