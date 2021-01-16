# PCA-from-Scratch
We have implemented PCA on the basis of the minimization of the reconstruction error. Reconstruction error is defined as the Frobenius norm of the difference between the original and reconstructed matrix. Specifically, of all possible linear projections from n to m dimensions, taking the first k components of the PCA transformation of X minimizes the reconstruction error.

## Content

    ├── Data                                  # Contains the dataset we used

    ├── src                                   # Source files for all the results
        .
        ├── GDP_capita_spanish_regions.csv      #dataset of the Nominal GDP per Capita in Spain.
        ├── pca.py      #module in which we implemented PCA from scratch.
        ├── pca_gdp.py      #uses pca.py to finally implement the Cluster Analysis.
        ├── visualizations.py       #data analysis on various aspects of the dataset.
        
## Implementation
We first perform the PCA for feature extraction and reduce the dimensionality for cluster analysis. This part is implemented in the PCA module. Using the PCA module we transform the dataset to generate the first 3 components of PCA. Using this transformed data we perform the cluster analysis with the K-means clustering Algorithm.

## Team/Contributors

[Aronya Baksy](https://github.com/abaksy) <br>
[Ansh Sarkar](https://github.com/anshsarkar) <br>
[Ruchika Shashidhara](https://github.com/RuchikaShashidhara)
