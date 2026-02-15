# Bioinformatics Fundamentals Portfolio 🧬

This repository serves as a growing collection of fundamental bioinformatics algorithms and simulations, implemented in Python.

## 📂 Projects

### 1. Central Dogma Simulation (DNA -> Protein)
* **File:** `01_central_dogma_simulation.ipynb`
* **Description:** A simulation of the biological information flow. Converts DNA sequences to mRNA and then translates them into protein chains using the standard genetic code.
* **Key Concepts:** Transcription, Translation, Codon Mapping.

### 2. SARS-CoV-2 Genome Analysis 🦠
* **File:** `02_covid_genome_analysis.ipynb`
* **Description:** Analysis of the SARS-CoV-2 Spike Protein gene using the **Sliding Window Algorithm**.
* **Visualization:** Plots GC content fluctuations to identify genetically stable vs. unstable regions (potential mutation zones).
* **Tech Stack:** `Biopython`, `Matplotlib`, `NumPy`.

### 3. NGS Data Quality Control (FASTQ Analysis) 🧬
* **File:** `03_ngs_data_quality_control.ipynb`
* **Description:** A Quality Control (QC) pipeline for Next-Generation Sequencing (NGS) data.
    * **Simulation:** Generates synthetic FASTQ reads mimicking Illumina sequencing errors (quality drop-off at read ends).
    * **Analysis:** Calculates **Phred Quality Scores** per base position to assess sequencing reliability.
* **Visualization:** Generates boxplots to identify low-quality reads that require trimming (similar to FastQC reports).
* **Tech Stack:** `Biopython`, `Seaborn`, `Pandas`.

---

## 🛠️ Tools & Libraries
* **Python:** 3.13.9
* **Biopython:** For biological sequence manipulation.
* **Matplotlib:** For data visualization.
* **VSCode Notebook:** For interactive analysis.

## 👨‍💻 Author
**Emre Engin** | Developer & Aspiring Bioinformatician
*Goal: Bridging Biology and Computer Science.*
