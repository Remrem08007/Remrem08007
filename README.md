# Hi, I'm Rémi-Antoine Joron 👋

**Bioinformatics · Scientific Computing · HPC**

I build reproducible computational workflows for genomics and biological data analysis, with an emphasis on **Nextflow, SLURM, scientific Python, containerized execution, and research-computing reliability**.

My background combines bioinformatics, software engineering, statistics, and high-performance computing. I enjoy turning complex analyses into workflows that are transparent, testable, portable, and practical to run on real research infrastructure.

## 🔬 Featured projects

### [Metagenomics HPC Workflow](https://github.com/Remrem08007/metagenomics-hpc-workflow)

A reusable **Nextflow DSL2 workflow for host depletion and broad non-human taxonomic screening** of paired-end sequencing data.

Highlights:
- FastQC + fastp preprocessing
- STAR-based host subtraction
- strict extraction of pairs where both mates are unmapped
- complementary Kraken2 nucleotide and Kaiju protein classification
- classifier-specific taxonomy preserved side-by-side
- SLURM execution with Apptainer / Singularity
- offline-friendly analysis for restricted-network HPC systems
- preflight validation, resource profiles, resumable execution, and CI
- committed deterministic 100-pair biological mock community with per-pair ground truth
- **validated end-to-end biological smoke test: `BIOLOGICAL TEST: PASS`**

The repository is deliberately generic: no lab-specific paths, sample conventions, scheduler accounts, or study-specific interpretation logic are built into the workflow.

### [CQDG De Novo Variant Pipeline](https://github.com/Remrem08007/cqdg-denovo-pipeline)

A reusable **Nextflow genomics workflow** for family-based de novo variant analysis.

The workflow supports:
- WGS and WES data
- joint genotyping
- VQSR and hard filtering
- VEP annotation
- reproducible and containerized execution

## 🧬 What I work on

### Bioinformatics & genomics
- NGS workflow development and troubleshooting
- variant processing, filtering, and annotation
- metagenomics and taxonomic classification
- host-depletion and read-processing workflows
- reproducible analysis pipelines and validation fixtures

### HPC & research computing
- Nextflow pipeline development
- SLURM-based execution
- Linux research environments
- Apptainer / Singularity containers
- restricted-network / offline compute workflows
- resource planning, resumability, preflight validation, and workflow debugging

### Scientific programming & data analysis
- Python and Bash automation
- statistical modelling and machine learning
- biological data analysis and visualization
- testing, validation, and reproducible research tooling

## 🛠️ Technical toolkit

**Languages:** Python · Bash · C++ · JavaScript · SQL  
**Workflow & HPC:** Nextflow · SLURM · Linux · Apptainer / Singularity · Docker  
**Bioinformatics:** GATK · VEP · STAR · samtools · Kraken2 · Kaiju · BLAST  
**Engineering:** Git · CI/testing · reproducible environments · workflow validation

## 🧪 Selected experience

- Developed bioinformatics pipelines and research tools for large-scale biological datasets
- Worked on computational immunology using statistical analysis, machine learning, and mathematical modelling
- Professional software-development and software quality-assurance experience
- **MIT Fusion Program internship** — particle simulation work using **C++ and Geant4**

## 🎓 Background

- **B.Sc. in Bioinformatics** — Université de Montréal
- **Certificate in Programming** — Université de Montréal
- Fluent in **French and English**

## 💼 Collaboration

I’m interested in selected research and consulting projects involving:

- bioinformatics pipeline development
- NGS workflow troubleshooting
- Nextflow development
- HPC / SLURM deployment and optimization
- scientific Python and Bash automation
- genomics and metagenomics workflows
- reproducible research computing
