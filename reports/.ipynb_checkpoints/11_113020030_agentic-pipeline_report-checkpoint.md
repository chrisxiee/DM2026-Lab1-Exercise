**1. Data Loading (Result ID: load_dataset_2)**
I loaded the built-in 20-newsgroups dataset and filtered it to include two categories, `sci.med` and `sci.space`, for analysis. A total of 1,187 text documents were successfully retrieved.

**2. Building the Document-Term Matrix (Result ID: dtm_3)**
Next, I executed the `build_dtm_tool` to convert the text into a Document-Term Matrix (DTM). The resulting matrix contains 25,638 feature terms with 199,266 non-zero elements, resulting in a high overall sparsity of 99.34%.

**3. Dimensionality Reduction and Visualization (Result ID: reduction_4)**
Finally, to observe the distribution of texts across different topics, I applied PCA (Principal Component Analysis) to reduce the high-dimensional matrix to 2 dimensions and generated a scatter plot. The resulting plot visualizes the distribution and separation of the two document categories.

![PCA Result](../plots/my_pca_result.png)
