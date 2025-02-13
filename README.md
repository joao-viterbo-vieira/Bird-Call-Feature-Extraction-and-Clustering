# Bird Call Feature Extraction and Clustering

This repository focuses on the feature extraction and clustering of bird calls to identify their respective families. The project involves four bird species:

- **King Penguin**
- **Red-tailed Hawk**
- **Greater Prairie Chicken**
- **Magpie Goose**

## Overview

We explored audio data from these bird species and applied feature extraction techniques in both the time and frequency domains. The extracted features were used for clustering and analysis, helping to distinguish bird families based on their calls.

### Extracted Features

1. **Time Domain Features**:
   - **Zero Crossing Rate (ZCR)**: Measures the rate of sign changes in the signal, representing the temporal complexity of the call.

2. **Frequency Domain Features**:
   - **Spectral Features**:
     - Centroid
     - Bandwidth
     - Roll-off
     - Flux
   - **Mel-Frequency Cepstral Coefficients (MFCCs)**: Captures the power spectrum of the call in a way that approximates human auditory perception.

### Clustering Methodology

- **K-Means Clustering**:
  The extracted features were used as inputs for the K-Means algorithm, grouping the bird calls into clusters corresponding to their respective families.

### Tools and Libraries

- Python
- Libraries:
  - NumPy
  - SciPy
  - Librosa
  - Matplotlib
  - scikit-learn

## Results

The analysis demonstrated clear distinctions among the families based on their calls, validated through clustering outputs. K-Means clustering provided meaningful groupings that align with biological classifications.

## Contributors

- [@jcns1107](https://github.com/jcns1107)
- [@jameslime214](https://github.com/jameslime214)

## Future Work

- Integrating additional species and families for a more extensive dataset.
- Exploring other clustering algorithms, such as hierarchical clustering or DBSCAN.
- Applying supervised learning techniques for species classification.

---

This project is an exciting step towards understanding the acoustic patterns of birds and their family classification. Contributions and suggestions are welcome!
