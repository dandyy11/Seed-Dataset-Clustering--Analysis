# Seed Dataset Clustering Analysis
Clustering analysis on the Seed dataset using agglomerative clustering, k-means clustering, and model-based clustering (GPCM). The project includes comparative analysis, cluster visualizations, and model evaluation using Adjusted Rand Index (ARI) to identify the optimal clustering technique.

### Dataset
**Seed Dataset:** The dataset contains measurements of geometrical properties of kernels belonging to three different varieties of wheat: Kama, Rosa, and Canadian. The dataset includes features like area, perimeter, compactness, and asymmetry coefficient.

### Objectives
1. **Agglomerative Clustering:** Apply hierarchical clustering using single, complete, and average linkage methods to explore the structure of the Seed dataset.
2. **K-Means Clustering:** Determine the optimal number of clusters using the Elbow method and silhouette analysis.
3. **Model-Based Clustering:** Use Gaussian finite mixture models to identify the best model using Bayesian Information Criterion (BIC).
4. **Overall Comparison:** Evaluate and compare the performance of different clustering methods using classification tables and the Adjusted Rand Index (ARI).

### Repository Structure
- `Seed_Clustering_Analysis.Rmd` - R Markdown file containing the complete analysis and code for agglomerative clustering, k-means clustering, model-based clustering, and overall comparison.
- `Detailed_Report.pdf` - PDF file with the comprehensive report of the clustering analysis.

### Findings
1. **Agglomerative Clustering:** The average linkage method provided the most distinct clusters, balancing the sensitivity of single linkage and the strictness of complete linkage.
2. **K-Means Clustering:** The optimal number of clusters was determined to be 3, aligning with the three known varieties in the Seed dataset.
3. **Model-Based Clustering (GPCM):** The GPCM approach with 2 components was identified as the best model, capturing the complex structure of the data.
4. **Overall Comparison:** GPCM showed the highest Adjusted Rand Index (ARI) at 0.737, indicating its superior performance in clustering the seed varieties compared to k-means and hierarchical clustering.

### Conclusion
The clustering analysis on the Seed dataset provides insights into the natural groupings of wheat varieties. Model-based clustering (GPCM) was found to be the most effective method, as indicated by the highest ARI, followed by k-means clustering and hierarchical clustering. This analysis demonstrates the importance of choosing the appropriate clustering technique for accurate data segmentation.

### How to Use
To reproduce the analyses, clone this repository and open the R Markdown files (`.Rmd`). You can knit these files in RStudio to generate the HTML or Markdown outputs.
```bash
# Clone the repository
https://github.com/dandyy11/Seed-Dataset-Clustering--Analysis.git

### Contact
For questions or suggestions, please contact Salman Imtiaz at salman.imtiaz414@gmail.com
