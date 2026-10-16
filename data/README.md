# Data

Raw data were committed via CLI (the two count matrices are ~96 MB and ~71 MB).

Required files (Tabula Muris, FACS-sorted cells, Smart-seq2) placed in the **repository root** next to the notebook:

| File | Description |
|---|---|
| `Lung-counts.csv` | Gene × cell count matrix, mouse lung (1,923 cells × 23,433 genes) |
| `Trachea-counts.csv` | Gene × cell count matrix, mouse trachea (1,391 cells × 23,433 genes) |
| `metadata_FACS.csv` | Per-plate metadata (tissue, subtissue, mouse.id, mouse.sex, plate.barcode, FACS.selection) |

Source: Tabula Muris Consortium (2018), *Nature* 562, 367–372, https://doi.org/10.1038/s41586-018-0590-4 — data portal: https://tabula-muris.ds.czbiohub.org/

The notebook also writes `data.pickle.gz`, `metadata.pickle.gz` and `metadata_with_clusters.pickle.gz`; these are git-ignored.
