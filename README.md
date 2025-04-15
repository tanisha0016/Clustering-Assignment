# Clustering-Assignment
Comparitive performance study of different clustering algorithms using different pre-processing techniques with different numbers of clusters on different evaluation parameters.
# Clustering Performance Summary: Iris Dataset

## Dataset Details
- **Name**: Iris Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- **Rows**: 150
- **Features**: 4

## Clustering Algorithms Evaluated
- KMeans  
- Hierarchical Clustering  
- MeanShift  

## Preprocessing Techniques Tested
- None  
- Normalization (`StandardScaler`)  
- Power Transformation (`PowerTransformer`)  
- PCA (2D)  
- Transform + Normalize (`PowerTransformer + StandardScaler`)  
- Transform + Normalize + PCA  

## Best Results
| Metric | Value |
|--------|-------|
| **Best Algorithm** | Hierarchical |
| **Best Preprocessing** | Normalization |
| **Best Number of Clusters** | 4 |
| **Best Silhouette Score** | 0.979 |
| **Best CH Score** | 719 (with PCA, Hierarchical) |
| **Lowest DB Score** | 0.331 (with Normalization, Hierarchical) |

