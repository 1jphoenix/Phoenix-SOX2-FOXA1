# Phoenix-SOX2-FOXA1
Phoenix, et. al | SOX2 utilizes FOXA1 as a heteromeric transcriptional partner to drive proliferation in therapy-resistant prostate cancer
# SOX2 utilizes FOXA1 as a heteromeric transcriptional partner to drive proliferation in therapy-resistant prostate cancer

This repository contains code used in the analyses presented in the manuscript:  
**"SOX2 utilizes FOXA1 as a heteromeric transcriptional partner to drive proliferation in therapy-resistant prostate cancer"**  
(*Authors*, Year)

> Code includes transcription factor binding analysis, ChIP-seq peak overlaps, UpSet plotting, RNA-seq visualization, and ChIP-seq signal heatmaps using BigWig files.

---

## Repository Contents

- `Fig3and4_Venn.ipynb`  
  Generates 2-way and 3-way Venn diagrams from BED files to visualize overlaps of SOX2 and FOXA1 binding events.

- `Fig6and7_UpSet_1bp.ipynb`  
  Compares binding regions across multiple treatment conditions using 1bp overlap criteria and visualizes intersections with UpSet plots.

- `Fig6_RNA_seq_TPM_heatmaps.ipynb`  
  Processes TPM-normalized RNA-seq expression data and produces annotated heatmaps and gene expression visualizations.

- `FigX_ChIPseq_Heatmap.ipynb`  
  Generates a ChIP-seq signal intensity heatmap centered on the top 1000 peak summits. Uses `deeptools` to compute the matrix and plot the heatmap across BigWig tracks from different treatment conditions.

---

## Dependencies

These notebooks were developed in **Google Colab** and require the following Python packages:
pandas
numpy
matplotlib
matplotlib-venn
seaborn
upsetplot
pybedtools
pyranges
biothings-client
deeptools

You can install these locally via pip:

```bash
pip install -r requirements.txt

Alternatively, open the notebooks directly in Colab.

License
This project is licensed under the MIT License.

Citation
If you use this code, please cite our manuscript:
"SOX2 utilizes FOXA1 as a heteromeric transcriptional partner to drive proliferation in therapy-resistant prostate cancer"
[Phoenix, et. al (2025)].
A DOI or preprint link will be added once available.
