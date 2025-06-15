
# This repository contains data tables used for plotting figures in the article *Cross-platform DNA motif discovery and benchmarking to explore binding specificities of poorly studied human transcription factors*
Ilya E. Vorontsov, Ivan Kozin, Sergey Abramov, Alexandr Boytsov, Arttu Jolma, Mihai Albu, Giovanna Ambrosini, Katerina Faltejskova, Antoni J. Gralak, Nikita Gryzunov, Sachi Inukai, Semyon Kolmykov, Pavel Kravchenko, Judith F. Kribelbauer-Swietek, Kaitlin U. Laverty, Vladimir Nozdrin, Zain M. Patel, Dmitry Penzar, Marie-Luise Plescher, Sara E. Pour, Rozita Razavi, Ally W.H. Yang, Ivan Yevshin, Arsenii Zinkevich, Matthew T. Weirauch, Philipp Bucher, Bart Deplancke, Oriol Fornes, Jan Grau, Ivo Grosse, Fedor A. Kolpakov, The Codebook/GRECO-BIT Consortium, Vsevolod J. Makeev, Timothy R. Hughes, Ivan V. Kulakovskiy
bioRxiv 2024.11.11.619379; doi: https://doi.org/10.1101/2024.11.11.619379


---

## **Figure F1:**

**Motif discovery and benchmarking pipeline and the collection of top-ranking motifs**

* **F1B\_experiments.csv**, **F1B\_tools.csv** – Contributions of different tools and experimental methods to:

  * Top-ranking motif collection (TF count)
  * Complete MEX set of benchmarked motifs (percentage)

* **F1C** – *ADD A DESCRIPTION*

* **F1D** – *ADD A DESCRIPTION*

---

## **Figure F2:**

* **F2A.csv** – Highest overall performance of the best motifs (one per TF) when training and testing on the same experiment type.

* **F2B.csv** – Highest performance in cross-platform evaluation.

  * **Color scale**: Median performance (higher = better)
  * **Box size**: IQR (lower = better)
  * **Numbers**: Number of tested TFs per tool and experiment combination

---

## **Figure F3:**

**Performance of motifs from artificial sequences in genomic prediction**

* **F3A.csv**, **F3B.csv** – Difference in best auROC values for genomic data (ChIP-Seq vs artificial: HT-SELEX, SMiLE-Seq, PBM)

* **F3C\_ChIP-Seq\_train.csv**, **F3C\_GHT-SELEX\_train.csv** – Correlation of training vs test performance: ChIP-Seq, GHT-SELEX

* **F3D\_ChIP-Seq\_test.csv**, **F3D\_GHT-SELEX\_test.csv** – Correlation of artificial training vs genomic test performance

---

## **Supplementary Figure SF1:**

* **SF1A.csv** – Number of experiments processed per motif discovery tool

* **SF1B.csv** – Number of motifs per experiment type and tool

* **SF1C\_tools.csv**, **SF1C\_experiments.csv** – Composition of overall top-20 motif collection, same as Figure F1 representation

---

## **Supplementary Figure SF2:**

**Top-ranking motif counts from tools in intra-/cross-platform benchmarking**

* **SF2A.csv** – Top-ranking motifs by tool, trained and tested on the same experiment type

* **SF2B.csv** – Top-ranking motifs by tool, trained on other types, tested on a given experiment type


---

## **Supplementary Figure SF3:**

**Intra-/cross-platform benchmarking for GHT-SELEX and HT-SELEX subtypes**

* **SF3A.csv** – Training and testing on the same experiment type

* **SF3B.csv** – Training and testing across platforms and within GHT/HT-SELEX subtypes (IVT, Lysate, GFPIVT)

---

## **Supplementary Figure SF4:**

* **SF4A.csv** – Fraction of cases where 1st/2nd/3rd motif from a tool run ranked highest overall

* **SF4B\_ChIP-Seq.csv**, **SF4B\_GHT-SELEX.csv** – Distributions of pseudo-auROC values for top-ranking motifs across TFs

* **SF4C\_ChIP-Seq.csv**, **SF4C\_GHT-SELEX.csv** – auROC distributions for zinc-finger TFs

* **SF4D.csv** – Scatterplots of auROC (GHT-SELEX vs ChIP-Seq) for zinc-finger TFs

---

## **Supplementary Figure SF5:**

* **SF5.csv** – Correlation of motif performance within the same vs across different experiment types

---

## **Supplementary Figure SF6:**

* **SF6.csv** – Distributions of motif properties (length, GC%, info content)

  * A: By discovery tool
  * B: By experiment type

---

## **Supplementary Figure SF7:**

* **SF7A.csv** – Correlation of performance metrics with motif properties (length, GC%, info content) for ChIP-Seq & GHT-SELEX

* **SF7B.csv** – Same as A for HT-SELEX and SMiLE-Seq benchmarks

* **SF7C.csv** – Violin plots of info content variation (top 10 motifs/TF), split by experiment type

---

## **Supplementary Figure SF11:**

**Metric correlation plots across motifs/datasets with Pearson’s rho**

* **SF11A.csv** – ChIP-Seq

* **SF11B.csv** – GHT-SELEX

---

