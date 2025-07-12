
# Evolution of Antibiotic Resistance in Bacterial Metapopulations

This SLiM simulation models the evolution of **antibiotic resistance** in a clonal bacterial population structured into granuloma-like subpopulations. It includes:

- Mutation accumulation (neutral and deleterious) using Non-Fisher Right Model
- Density-dependent migration
- Antibiotic exposure events
- Selection for resistant genotypes

## 🧬 Biological Context

This project explores how **mutation supply**, **population structure**, and **migration dynamics** influence the emergence and spread of **resistant alleles** under intermittent antibiotic pressure. The model is loosely inspired by *Mycobacterium tuberculosis* infection dynamics.

## 📁 Project Structure

## ⚙️ Model Features

- **Clonal reproduction**: Asexual bacterial populations
- **Granuloma-like subpopulations**: Discrete demes with local density regulation
- **Deleterious mutations**: Weakly deleterious background mutation load
- **Resistance alleles**: Gain-of-function mutations at resistance loci
- **Antibiotic pulses**: External selective pressure introduced periodically
- **Migration**: Between demes at rates modulated by population size

## 💻 Usage

### 1. Requirements

- [SLiM 3.x](https://messerlab.org/slim/)
- (Optional) Python libraries for analysis: `pyslim`, `msprime`, `numpy`, `pandas`, `matplotlib`

### 2. Run the simulation

```bash
slim resistance_sim.slim



