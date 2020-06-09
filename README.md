## Experimental evaluation and comparison of multi-omics data integration methods for cancer subtyping

Computational integrative analysis has become a significant approach in the data-driven exploration of biological problems. Many integration methods for cancer subtyping have been proposed, but evaluating these methods has become a complicated problem due to the lack of gold standards. **Moreover, questions of practical importance remain to be addressed regarding the impact of selecting appropriate data types and combinations on the performance of integrative studies.** Here, we constructed three classes of benchmarking datasets of five cancers in TCGA by considering all the eleven combinations of four multi-omics data types. Using these datasets, we conducted a comprehensive evaluation of five representative integration methods for cancer subtyping in terms of accuracy measured by combining both clustering accuracy and clinical significance, robustness, and computational efficiency. We subsequently investigated the influence of different omics data on cancer subtyping and the effectiveness of their combinations. **Refuting the widely held intuition that incorporating more types of omics data always produces better results, our analyses showed that there are situations where integrating more omics data negatively impacts the performance of integration methods. Our analyses also suggested several effective combinations for most cancers under our studies, which may be of particular interest to researchers in omics data analysis.**



### Key points

- Refuting the widely held intuition that incorporating more types of omics data always helps produce better results, our analyses showed that there are situations where integrating more types of omics data negatively impacts the performance of the integration methods.

- The influence of different omics data types varies in cancer subtyping.

- Our analyses suggested several effective combinations of omics data types for most cancers under our studies (e.g. mRNA + CNV and mRNA + miRNA) that can indeed improve the accuracy on cancer subtyping as measured by both clustering and clinical metrics. We believe that it will be of particular interest to researchers in the practice of integrative omics data analysis.



### Datasets description

The Cancer Genome Atlas Program (TCGA) has collected a large number of different types of omics data from more than 30 types of cancers. In this study, four types of omics data were chosen, including **copy number variation (CNV)** in genome level, **DNA methylation** and **miRNA expression** in epigenome level, and **mRNA expression** in transcriptome level. 

To decide the cancer types to be used in this studies, we focused on those cancers which had a sufficient number of samples of the four types of omics data in the TCGA collection and had been used in previous studies on cancer subtyping. As a result, five common cancers were chosen, including Breast Invasive Carcinoma (**BRCA**), Colon Adenocarcinoma (**COAD**), Kidney Renal Clear Cell Carcinoma (**KIRC**), Lung Adenocarcinoma (**LUAD**), and Lung Squamous Cell Carcinoma (**LUSC**). 

To make a comprehensive evaluation and comparison, we constructed three different classes of benchmarking datasets using the four types of omics data of the five cancers, including **Dataset #1: Five-cancer datasets**, **Dataset #2: Noise datasets**, and **Dataset #3: Gold standards datasets**.

Because of the inconsistency of the data combinations used in previous studies and the lack of a common guideline, we enumerated all the possible combinations of the four types of omics data. Therefore, there are six two-omic combinations (m+mi, m+me, m+cnv, mi+me, mi+cnv, me+cnv), four three-omic combinations (m+mi+me, m+mi+cnv, m+me+cnv, mi+me+cnv), and one four-omic combination (m+mi+me+cnv), giving a total of 11 possible combinations. We used each of these combinations to construct the three classes of benchmarking datasets illustrated above and these datasets were all used in our experiments.

For the details of the **Data pre-processing** and **Datasets construction**, please see our paper.



### Availability of datasets

As the size of the whole datasets is so huge and exceeds the file size limitation of GitHub, we are so sorry that we can not upload all the datasets to GitHub. We are now uploading the datasets to two cloud disk platforms and try our best to ensure that worldwide researchers can download them. We will push the download links on this page as soon as the upload process is done. Before this, please send an email to duanran9013@126.com, and we will send the datasets to you as soon as we receive the email.



### Results

Here, we provide all the clustering results of all tests in this work. The calculations of different metrics based on the clustering results are also provided. Please click the hyperlinks below for downloading.

[Download clustering results]()

[Download calculation results]()



### Contact us

If you are interested in this work and have any questions or suggestions, please send an email to us (duanran9013@126.com). We will reply to you as soon as possible. Thanks for your email.

