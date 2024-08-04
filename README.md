# Exploratory Data Analysis

# Exploratory Data Analysis (EDA) for Process Monitoring

## Overview

For developing an effective process monitoring model, it's crucial to have a deep understanding of your process data. This practice is formally known as Exploratory Data Analysis (EDA). In this repository, we will guide you through the process of evaluating four critical characteristics of a dataset to ensure that your monitoring model is based on a solid understanding of your data.

## Key Characteristics Explored

1. **Nonlinearity**: 
   - Nonlinearity in a dataset indicates that the relationship between variables cannot be described by a straight line. Identifying nonlinearity is essential as it affects the choice of modeling techniques.
   - For detecting nonlinearity, scatter plots between each pair of variables are often used. However, this approach can become cumbersome for high-dimensional datasets.

2. **Non-Gaussianity**: 
   - Non-Gaussianity refers to the distribution of data deviating from a Gaussian (normal) distribution. Understanding the distribution helps in selecting appropriate statistical methods and transformations.

3. **Multimodality**: 
   - Multimodality describes a dataset with multiple peaks or modes in its distribution. Recognizing multimodal characteristics helps in identifying different underlying processes or states in the data.

## Why EDA is Important

Effective EDA allows us to:
- Gain insights into the nature and structure of the data.
- Identify potential issues and anomalies.
- Inform the selection of suitable modeling techniques.
- Improve the overall performance and accuracy of process monitoring models.

## Getting Started

To begin your exploratory data analysis, follow these steps:

1. **Data Collection**: Gather the dataset that you want to analyze.
2. **Preprocessing**: Clean and preprocess the data to handle missing values, outliers, and other issues.
3. **Visualization**: Create scatter plots, histograms, and other visualizations to assess nonlinearity, non-Gaussianity, and multimodality.
4. **Dynamic Analysis**: Analyze time-series data to understand the dynamics and temporal dependencies in the dataset.

## Resources

- **[Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)**: Useful for implementing various data analysis techniques.
- **[Matplotlib Documentation](https://matplotlib.org/stable/contents.html)**: For creating visualizations.
- **[Seaborn Documentation](https://seaborn.pydata.org/)**: For advanced data visualization.

## Contributing

If you have suggestions or improvements, feel free to contribute to this repository. Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

## Nota:
dataset from:https://github.com/giovannimen/cpcad-bench.

@INPROCEEDINGS{9926420,

  author={Menegozzo, Giovanni and Dall’Alba, Diego and Fiorini, Paolo},

  booktitle={2022 IEEE 18th International Conference on Automation Science and Engineering (CASE)}, 

  title={CIPCaD-Bench: Continuous Industrial Process datasets for benchmarking Causal Discovery methods}, 

  year={2022},

  volume={},

  number={},

  pages={2124-2131},

  doi={10.1109/CASE49997.2022.9926420}}

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

By thoroughly understanding the characteristics of your data through EDA, you lay a strong foundation for building a robust and effective process monitoring model. Happy analyzing!

