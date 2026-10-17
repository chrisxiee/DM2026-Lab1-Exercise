# Reddit Stock Sentiment Analysis Report

**1. Data Loading (Result ID: load_dataset_1)**
I loaded the `Reddit-stock-sentiment.csv` dataset, using the `text` column for content and the `sentiment` column for labels. The dataset contains a total of 847 documents across three sentiment categories (0.0, 1.0, and -1.0).

**2. Document-Term Matrix (Result ID: dtm_2)**
I applied the `build_dtm_tool` to convert the text into a numerical matrix. The resulting DTM consists of 4,346 feature terms with 17,193 non-zero elements, yielding a high sparsity of 99.53%. 

**3. Dimensionality Reduction (Result ID: reduction_3)**
Finally, I used the `reduce_dimensions_tool` to perform PCA, reducing the high-dimensional data into 2D space for visualization. The scatter plot below shows the distribution of Reddit posts colored by their sentiment labels.

![PCA Result](../plots/11_homework_plot_reduction_3.png)
