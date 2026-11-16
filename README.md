
# 🧬 AMR SCOPE

### Antimicrobial Resistance Genomic Surveillance Observatory

**Understanding Resistance Through Genomics.**

AMR SCOPE is a developing public-genome-based genomic surveillance platform designed to monitor antimicrobial resistance determinants, bacterial lineages, virulence-associated markers and plasmid replicons across priority bacterial pathogens.

The platform aims to establish a reproducible and automated bioinformatics framework for genomic surveillance, beginning with *Klebsiella pneumoniae* in West Bengal, India.

---

## 🎯 Project Objectives

- Monitor antimicrobial resistance genes in publicly available bacterial genomes.
- Identify and track important bacterial sequence types and genomic lineages.
- Characterise virulence-associated genetic markers.
- Investigate plasmid replicons associated with antimicrobial resistance.
- Explore temporal and geographical patterns in genomic deposits.
- Develop an automated and reproducible genomic surveillance pipeline.
- Build a scalable framework for analysing multiple bacterial pathogens.

## 🔬 Initial Surveillance Focus

| Parameter | Current scope |
|---|---|
| Pathogen | *Klebsiella pneumoniae* |
| Geography | West Bengal, India |
| Initial city of interest | Kolkata |
| Study period | 2018–2026 |
| Data sources | NCBI, BV-BRC |
| Data type | Public bacterial genomic data |

## 🦠 Future Pathogen Coverage

The long-term objective is to extend surveillance to all six ESKAPE pathogens:

1. *Enterococcus faecium*
2. *Staphylococcus aureus*
3. *Klebsiella pneumoniae*
4. *Acinetobacter baumannii*
5. *Pseudomonas aeruginosa*
6. *Enterobacter* spp.

## 🧪 Planned Bioinformatics Workflow

1. Public genome data acquisition and metadata retrieval.
2. Geographic and source-based eligibility filtering.
3. Raw sequencing read quality control.
4. Genome assembly where required.
5. Antimicrobial resistance gene identification.
6. Sequence typing and lineage analysis.
7. Virulence-associated marker analysis.
8. Plasmid replicon identification.
9. Data integration and statistical analysis.
10. Genomic surveillance dashboard development.

## 🛠️ Planned Technology Stack

- Python
- FastQC
- fastp
- SPAdes
- Kleborate
- ResFinder
- CARD
- MLST
- PlasmidFinder
- Pandas
- Streamlit
- Plotly
- GitHub Actions

## 🌍 Geographical Expansion Roadmap

**Phase 1:** Kolkata and West Bengal — *Klebsiella pneumoniae*

**Phase 2:** Expansion across India.

**Phase 3:** Integration of additional ESKAPE pathogens.

**Phase 4:** Future expansion across South Asia.

## 🔐 Data Policy

AMR SCOPE will use publicly available, de-identified bacterial genomic data.

- No patient records.
- No hospital records.
- No private institutional datasets.
- No individual clinical information.

## ⚠️ Scientific Limitations

Public genomic databases are subject to sampling, sequencing, submission and geographical biases.

The proportion of resistance genes detected among deposited genomes must not be interpreted as population-level AMR prevalence.

Genotypic detection of resistance determinants does not independently establish phenotypic antimicrobial resistance.

## 🚧 Development Status

**Currently in the initial development and pilot-design stage.**

Pipeline implementation, genomic data validation and dashboard development are planned milestones.

## 📚 Project Vision

To develop a scalable and reproducible genomic surveillance resource that supports the understanding of antimicrobial resistance patterns through publicly available bacterial genomic data.

---

**Project:** AMR SCOPE

**Research area:** Antimicrobial Resistance · Microbial Genomics · Bioinformatics · Genomic Surveillance
