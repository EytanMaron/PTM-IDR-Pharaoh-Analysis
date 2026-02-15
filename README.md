# PTM Landscape in Disordered Regions & Aging-Related Sites (PHARAOH)

## Scientific Background
Post-translational modifications (PTMs) are critical regulators of protein function. A significant portion of these modifications occurs within **Intrinsically Disordered Regions (IDRs)**—segments that lack a fixed three-dimensional structure. The high conformational flexibility and accessibility of IDRs make them ideal substrates for enzymatic modifications, such as phosphorylation and acetylation.

This project investigates whether specific PTMs are significantly enriched in IDRs and explores their relationship with sites identified by the **PHARAOH algorithm**. PHARAOH sites are of particular interest as they have been identified as functionally significant in the context of **aging and longevity**.

## Research Objectives
1. **Structural Enrichment Analysis:** Determine if PTMs are disproportionately located within IDRs compared to ordered domains across the proteome.
2. **Aging-Site Correlation:** Analyze the spatial distribution of PHARAOH sites relative to IDRs and PTM clusters.
3. **Statistical Significance:** Evaluate if PHARAOH sites exhibit a unique structural "signature" (e.g., higher disorder preference) compared to general PTMs, suggesting a specific regulatory mechanism in aging.

## Methodology
- **Disorder Prediction:** Utilizing state-of-the-art predictors (e.g., `metapredict`, AlphaFold pLDDT scores) to map IDRs.
- **Data Integration:** Cross-referencing PTM databases with PHARAOH algorithmic outputs.
- **Statistical Framework:** - Enrichment analysis using Fisher's Exact Test / Hypergeometric tests.
    - Spatial clustering analysis of modification sites.

## Project Structure
- `notebooks/`: Modular analysis pipelines (Preprocessing, Statistics, Visualization).
- `data/`: (Local/Drive) Curated datasets including PTM locations and PHARAOH scores (Excluded from Git via `.gitignore`).
- `src/`: Core Python modules for bioinformatics processing.
- `results/`: Summary statistics and publication-quality figures.

## Environment & Requirements
This project is optimized for **Google Colab** to leverage high-performance computing for large-scale genomic/proteomic data.
- Python 3.x
- Pandas, NumPy, Scipy (Statistical Analysis)
- Metapredict (IDR Prediction)
- Matplotlib/Seaborn (Visualization)

## How to Cite
Research conducted at **Prof. Haim Cohen's Lab**, focusing on the molecular mechanisms of aging.
