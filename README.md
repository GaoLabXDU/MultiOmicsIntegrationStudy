## Experimental evaluation and comparison of multi-omics data integration methods for cancer subtyping

Computational integrative analysis has become a significant approach in the data-driven exploration of biological problems. Many integration methods for cancer subtyping have been proposed, but evaluating these methods has become a complicated problem due to the lack of gold standards. **Moreover, questions of practical importance remain to be addressed regarding the impact of selecting appropriate data types and combinations on the performance of integrative studies.** Here, we constructed three classes of benchmarking datasets of five cancers in TCGA by considering all the eleven combinations of four multi-omics data types. Using these datasets, we conducted a comprehensive evaluation of five representative integration methods for cancer subtyping in terms of accuracy measured by combining both clustering accuracy and clinical significance, robustness, and computational efficiency. We subsequently investigated the influence of different omics data on cancer subtyping and the effectiveness of their combinations. **Refuting the widely held intuition that incorporating more types of omics data always produces better results, our analyses showed that there are situations where integrating more omics data negatively impacts the performance of integration methods. Our analyses also suggested several effective combinations for most cancers under our studies, which may be of particular interest to researchers in omics data analysis.**



### Key points

- We constructed three classes of benchmarking datasets of five cancers in TCGA by considering all the eleven combinations of four multi-omics data types.
- We conducted a comprehensive evaluation of five representative integration methods for cancer subtyping in terms of accuracy measured by combining both clustering accuracy and clinical significance, robustness, and computational efficiency.
- Refuting the widely held intuition that incorporating more types of omics data always helps produce better results, our analyses showed that there are situations where integrating more types of omics data negatively impacts the performance of the integration methods.
- The influence of different omics data types varies in cancer subtyping.
- Our analyses suggested several effective combinations of omics data types for most cancers under our studies (e.g. mRNA + CNV and mRNA + miRNA) that can indeed improve the accuracy on cancer subtyping.



### Datasets description

The Cancer Genome Atlas Program (TCGA) has collected a large number of different types of omics data from more than 30 types of cancers. In this study, four types of omics data were chosen, including **copy number variation (CNV)** in genome level, **DNA methylation** and **miRNA expression** in epigenome level, and **mRNA expression** in transcriptome level. 

To decide the cancer types to be used in this studies, we focused on those cancers which had a sufficient number of samples of the four types of omics data in the TCGA collection and had been used in previous studies on cancer subtyping. As a result, five common cancers were chosen, including Breast Invasive Carcinoma (**BRCA**), Colon Adenocarcinoma (**COAD**), Kidney Renal Clear Cell Carcinoma (**KIRC**), Lung Adenocarcinoma (**LUAD**), and Lung Squamous Cell Carcinoma (**LUSC**). 

To make a comprehensive evaluation and comparison, we constructed three different classes of benchmarking datasets using the four types of omics data of the five cancers, including **Dataset #1: Five-cancer datasets**, **Dataset #2: Noise datasets**, and **Dataset #3: Gold standards datasets**.

Because of the inconsistency of the data combinations used in previous studies and the lack of a common guideline, we enumerated all the possible combinations of the four types of omics data. Therefore, there are six two-omic combinations (m+mi, m+me, m+cnv, mi+me, mi+cnv, me+cnv), four three-omic combinations (m+mi+me, m+mi+cnv, m+me+cnv, mi+me+cnv), and one four-omic combination (m+mi+me+cnv), giving a total of 11 possible combinations. We used each of these combinations to construct the three classes of benchmarking datasets illustrated above and these datasets were all used in our experiments.

For the details of the **Data pre-processing** and **Datasets construction**, please see our paper.



### Availability of datasets

As the size of the whole datasets exceeds the file size limitation of GitHub, we are so sorry that we can not upload the datasets to GitHub. We have uploaded the datasets to figshare, Dropbox, and OneDrive. You can click the links in the table below to download the datasets from figshare. The sources from Dropbox and OneDrive will be available soon.

| Datasets                    | figshare | Dropbox | OneDrive |
| :-------------------------- | -------- | ------- | -------- |
| Dataset #1 BRCA Complete    | [Link](https://figshare.com/s/2773784f1d94260a4a2e)     | Link    | Link     |
| Dataset #1 BRCA Significant | [Link](https://figshare.com/s/bb469b06fe969fa34b64)     | Link    | Link     |
| Dataset #1 COAD Complete    | [Link](https://figshare.com/s/7cd48631c14df2046b16)     | Link    | Link     |
| Dataset #1 COAD Significant | [Link](https://figshare.com/s/c21e5bd52f0838d91674)     | Link    | Link     |
| Dataset #1 KIRC Complete    | [Link](https://figshare.com/s/030c22d72ed78fe92770)     | Link    | Link     |
| Dataset #1 KIRC Significant | [Link](https://figshare.com/s/b4b0438fa2580007b88c)     | Link    | Link     |
| Dataset #1 LUAD Complete    | [Link](https://figshare.com/s/1449ae077871f836891e)     | Link    | Link     |
| Dataset #1 LUAD Significant | [Link](https://figshare.com/s/1e7ad8f03248f74fb572)     | Link    | Link     |
| Dataset #1 LUSC Complete    | [Link](https://figshare.com/s/e3cdad2d2f8f1d0f0e1f)     | Link    | Link     |
| Dataset #1 LUSC Significant | [Link](https://figshare.com/s/55694443ea5bdd613293)     | Link    | Link     |
| Dataset #2 BRCA 0.5         | [Link](https://figshare.com/s/2280a954c5d2b911add6)     | Link    | Link     |
| Dataset #2 BRCA 1           | [Link](https://figshare.com/s/19aa8c5c419bcd29d3b5)     | Link    | Link     |
| Dataset #2 BRCA 2           | [Link](https://figshare.com/s/5927110c594f5f6b97f8)     | Link    | Link     |
| Dataset #2 BRCA 3           | [Link](https://figshare.com/s/35a8738724385f490f9a)     | Link    | Link     |
| Dataset #2 BRCA 4           | [Link](https://figshare.com/s/8e668698a5712a81f238)     | Link    | Link     |
| Dataset #2 COAD 0.5         | [Link](https://figshare.com/s/5416db4edfe9081e7554)     | Link    | Link     |
| Dataset #2 COAD 1           | [Link](https://figshare.com/s/02a17f5b62a979c3223b)     | Link    | Link     |
| Dataset #2 COAD 2           | [Link](https://figshare.com/s/6462b2230c94299666ef)     | Link    | Link     |
| Dataset #2 COAD 3           | [Link](https://figshare.com/s/dc551de7ca8a521ae4d4)     | Link    | Link     |
| Dataset #2 COAD 4           | [Link](https://figshare.com/s/eb3ae8f8770ec48f925b)     | Link    | Link     |
| Dataset #3 BRCA Complete    | [Link](https://figshare.com/s/b0d8c68133e8afa8b880)     | Link    | Link     |
| Dataset #3 BRCA Significant | [Link](https://figshare.com/s/c472f60152dc55f01634)     | Link    | Link     |
| Dataset #3 COAD Complete    | [Link](https://figshare.com/s/0dd604647efc5e7e0d49)     | Link    | Link     |
| Dataset #3 COAD Significant | [Link](https://figshare.com/s/8b92e955ead4c5a187fe)     | Link    | Link     |
| Dataset #3 Pan-cancer       | [Link](https://figshare.com/s/d2658236fe0dcf3ccd10)     | Link    | Link     |



### Results

Here, we provide all the results of different methods in this work. The calculations of different metrics based on the clustering results are also provided. Please click the hyperlinks below for downloading.

Method Results:
Dataset #1 ([Complete Datasets](https://github.com/GaoLabXDU/MultiOmicsIntegrationStudy/raw/master/Method%20Results/Dataset%20%231%20Complete%20%20Datasets.rar),  [Significant Datasets](https://github.com/GaoLabXDU/MultiOmicsIntegrationStudy/raw/master/Method%20Results/Dataset%20%231%20Significant%20Datasets.rar)), 
Dataset #2 ([Noise Datasets](https://github.com/GaoLabXDU/MultiOmicsIntegrationStudy/raw/master/Method%20Results/Dataset%20%232%20Noise%20Datasets.rar)), 
Dataset #3 ([Gold Standard Datasets](https://github.com/GaoLabXDU/MultiOmicsIntegrationStudy/raw/master/Method%20Results/Dataset%20%233%20Gold%20Standard%20Datasets.rar), [Pan-cancer Datasets](https://github.com/GaoLabXDU/MultiOmicsIntegrationStudy/raw/master/Method%20Results/Dataset%20%233%20Pancancer%20Datasets.rar))

Calculation Results: Accuracy ([Dataset #1](https://github.com/GaoLabXDU/MultiOmicsIntegrationStudy/raw/master/Calculation%20Results/Accuracy_Dataset%20%231.xlsx), [Dataset #3](https://github.com/GaoLabXDU/MultiOmicsIntegrationStudy/raw/master/Calculation%20Results/Accuracy_Dataset%20%233.xlsx)), [Robustness](https://github.com/GaoLabXDU/MultiOmicsIntegrationStudy/raw/master/Calculation%20Results/Robustness.xlsx), [Computational Effeciency](https://github.com/GaoLabXDU/MultiOmicsIntegrationStudy/raw/master/Calculation%20Results/Computational%20Efficiency.xlsx).



### Contact us

If you are interested in this work and have any questions or suggestions, please send an email to us (duanran9013@126.com). We will reply to you as soon as possible. Thanks for your email.

