![Banner](https://github.com/LuisNagano/LuisNagano/blob/main/Banner_B.png)
# Hi there! I'm Luis Nagano

*<h3 align="center">Data Scientist and Bioinformatician</h3>*

<div align="center">
  
[![Static Badge](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&logoColor=white)](www.linkedin.com/in/luis-fernando-nagano-7585b82a8)
[![Static Badge](https://img.shields.io/badge/Medium-black?style=flat&logo=medium&logoColor=white)]()
[![Static Badge](https://img.shields.io/badge/Kaggle-%2320BEFF?style=flat&logo=kaggle&logoColor=white)]()
[![Static Badge](https://img.shields.io/badge/Gmail-red?style=flat&logo=gmail&logoColor=white)](nagano.luis@gmail.com)
[![Static Badge](https://img.shields.io/badge/Google_Scholar-blue?style=flat&logo=googlescholar&logoColor=white)]()
[![Static Badge](https://img.shields.io/badge/ORC_ID-green?style=flat&logo=orcid&logoColor=white)]()
[![Static Badge](https://img.shields.io/badge/Github_Page-black?style=flat&logo=github%20pages&logoColor=white)]()
[![Static Badge](https://img.shields.io/badge/Instagram-blueviolet?style=flat&logo=instagram&logoColor=white)]()
</div>

I am a passionate data scientist and bioinformatician with 8 years of experience, specializing in clinical, cancer, and developmental biology data analysis. My expertise in R, Python, Bash (Unix Shell), and Perl, combined with strong skills in machine learning, statistical analysis, and bioinformatics, allows me to derive impactful insights from complex datasets.

Throughout my career, I have contributed to several scientific projects aimed at discovering novel biomarkers and therapeutic targets, with a focus on improving the prognosis and treatment of pediatric cancers. My work is grounded in data science, leveraging advanced algorithms and statistical methods to translate raw data into actionable insights.

I have published multiple articles in international journals and have experience presenting research at scientific conferences, where I was recognized for my contributions to pediatric oncology.

I pride myself on my ability to communicate complex data in a clear, accessible way, making sure that insights are not only understood but also actionable. My critical thinking, problem-solving abilities, and deep curiosity about science and technology drive me to continuously improve and innovate.

## Skills

### Data Collection and Storage
- **Databases:** MySQL, PostgreSQL, TCGA, GTEx, GEO, Ensembl, NCBI, UCSC Genome Browser
- **Data Management and Versioning:** SQL, Git, GitHub, GitLab
- **Development Environments:** Jupyter Notebooks, RStudio, Visual Studio Code

### Data Processing and Analytics
- **Data Processing:** Pandas, NumPy, SciPy, BioPython, dplyr
- **Genomic Analysis:** STAR, HISAT2, BWA, Bowtie, DESeq2, EdgeR, limma, Seurat, Scanpy, CemiTools, Minfi, MACS2
- **Statistical Analysis:** Linear Regression, Logistic Regression, GLM, Cox Proportional Hazards, DESeq2, EdgeR, limma

### Machine Learning and Modeling
- **Algorithms:** Random Forest, SVM, Neural Networks, XGBoost, Deep Learning
- **Clustering:** K-means, Hierarchical Clustering, Consensus Clustering, WGCNA
- **Dimensionality Reduction:** PCA, t-SNE
- **Model Optimization:** Cross-validation, Hyperparameter Tuning

### Data Visualization
- **Visualization Tools:** Matplotlib, Seaborn, Plotly, ggplot2, Tableau, Shiny, Cytoscape, IGV (Integrative Genomics Viewer)
- **Visualization Types:** Heatmaps, Volcano Plots, PCA Plots, t-SNE, Interactive Dashboards
- **Network and Pathway Visualization:** STRING, Reactome, KEGG

### Machine Learning Deployment
- **Deployment Tools:** Flask, Docker, AWS

### Computational Resources
- **High-Performance Computing:** Running pipelines on distributed computing environments

## Bioinformatics Projects

- <h3><a href="https://github.com/LuisNagano/ConsensusClusterPlus" style="text-decoration: underline;">Unsupervised machine learning method establishes medulloblastoma molecular subgroup classification using lncRNA expression</a></h3>
  This project applies unsupervised machine learning techniques to classify molecular subgroups in medulloblastoma (MB) using lncRNA expression profiles from 167 MB samples. Using the ConsensusClusterPlus package in R, we identified four robust molecular subgroups corresponding to the known subtypes: Group 3, Group 4, SHH, and WNT. Validation with Cohen’s Kappa coefficient showed excellent agreement between the lncRNA-based classification and the original subgroups.

  <b>Technologies used:</b>
  <ul>
    <li><b>Language:</b> R</li>
    <li><b>Packages:</b> ConsensusClusterPlus, psych</li>
    <li><b>Data:</b> RNA-seq normalized expression from 167 samples</li>
  </ul>

- <h3><a href="https://github.com/LuisNagano/MetaFlux-Metabolism" style="text-decoration: underline;">Comparative Metabolic Flux Analysis: ACC-COC3 vs. BPCre Tumor Model</a></h3>
  This project presents a comparative metabolic flux analysis between human adrenocortical carcinoma (ACC) samples (subgroup ACC-COC3) and the mouse BPCre tumor model. The analysis utilizes RNA-seq data and calculates Metabolic Reaction Activity Scores (MRAS) to explore key metabolic pathways and validate metabolic similarities between both models. The study identified highly conserved pathways in amino acid and lipid metabolism, offering insights into potential therapeutic targets for ACC.

  <b>Technologies used:</b>
  <ul>
    <li><b>Language:</b> R</li>
    <li><b>Packages:</b> METAFlux, DESeq2, clusterProfiler</li>
    <li><b>Data:</b> TCGA RNA-seq (human ACC-COC3) and in-house RNA-seq (mouse BPCre)</li>
  </ul>

- <h3><a href="https://github.com/LuisNagano/Gene-Coexpression-network" style="text-decoration: underline;">Gene Co-expression Network Analysis in Adrenocortical Carcinoma (ACC)</a></h3>
  This project focuses on performing a comprehensive gene co-expression network analysis for adrenocortical carcinoma (ACC) samples from the TCGA database and normal adrenal gland tissues from the GTEx project. Using the CEMiTool package, we identified co-expressed gene modules, conducted pathway enrichment analysis, and explored their interactions within ACC subgroups (ACC-COC1, ACC-COC2, and ACC-COC3). The analysis highlights key pathways and hub genes that may serve as potential biomarkers and therapeutic targets in ACC.

  <b>Technologies used:</b>
  <ul>
    <li><b>Language:</b> R</li>
    <li><b>Packages:</b> CEMiTool, ggplot2</li>
    <li><b>Data:</b> TCGA-ACC samples and GTEx Normal Adrenal Gland tissue samples</li>
  </ul>

- <h3><a href="https://github.com/LuisNagano/Metabolism-PathwayScore" style="text-decoration: underline;">Metabolic Pathway Analysis in Lung Squamous Cell Carcinoma (LUSC)</a></h3>
  This project focuses on pathway scoring for Lung Squamous Cell Carcinoma (LUSC) using transcriptomic data. The analysis is based on the methodology from Rosario et al. (2018) to identify key metabolic pathways that are dysregulated in LUSC compared to normal tissue. We calculated pathway scores using a custom algorithm and identified significant dysregulation in multiple metabolic pathways, providing insights into potential therapeutic targets.

  <b>Technologies used:</b>
  <ul>
    <li><b>Language:</b> R</li>
    <li><b>Packages:</b> limma, edgeR, ggplot2</li>
    <li><b>Data:</b> TCGA-LUSC raw count data from GDAC Firehose</li>
  </ul>

- <h3><a href="https://github.com/LuisNagano/ComplexHeatmap-RNASeq" style="text-decoration: underline;">Data Visualization using ComplexHeatmap package</a></h3>
  This project focuses on the analysis and visualization of RNA-seq data from mouse samples using the ComplexHeatmap package. The analysis includes data normalization, selection of genes of interest from predefined lists, and the generation of heatmaps to visualize gene expression patterns across different experimental conditions (WT, BPCre, BCre, PCre, and ACC). The heatmaps are color-coded based on z-score values, providing insights into gene regulation.

  <b>Technologies used:</b>
  <ul>
    <li><b>Language:</b> R</li>
    <li><b>Packages:</b> ComplexHeatmap, RColorBrewer, circlize, colorRamps, biomaRt, edgeR</li>
    <li><b>Data:</b> RNA-seq gene expression data for mouse samples</li>
  </ul>


## Data Science Projects

- <h3><a href="https://github.com/LuisNagano/Breast-Cancer-Prediction" style="text-decoration: underline;">Breast Cancer Prediction Using Machine Learning</a></h3>
  This project focuses on building and evaluating various machine learning models to predict breast cancer using clinical and pathological data. The analysis includes data preprocessing, exploratory data analysis, model building, and evaluation. Multiple models such as Logistic Regression, SVM, Random Forest, and XGBoost are implemented and compared. The project also includes ROC curve analysis, feature importance assessment, and a profit calculation for a hypothetical breast cancer diagnosis company.
  
  <b>Technologies used:</b>
  <ul>
    <li><b>Language:</b> Python</li>
    <li><b>Libraries:</b> pandas, numpy, scikit-learn, xgboost, seaborn, matplotlib</li>
    <li><b>Data:</b> Breast cancer dataset with clinical and pathological features</li>
    <li><b>Algorithms:</b> Logistic Regression, KNN, SVM, Decision Trees, Random Forest, Gradient Boosting, XGBoost</li>
  </ul>

- <h3><a href="https://github.com/LuisNagano/Parkinson-Disease-Prediction" style="text-decoration: underline;">Parkinson's Disease Prediction Using Machine Learning</a></h3>
  This project focuses on predicting Parkinson's disease using biomedical voice measurements. The analysis includes data preprocessing, exploratory data analysis, model building using Support Vector Machine (SVM), and evaluation. The project demonstrates the entire machine learning pipeline from data loading to making predictions on new data. The SVM model achieves an accuracy of 87.18% on both training and testing sets, indicating good generalization without overfitting.
  
  <b>Technologies used:</b>
  <ul>
    <li><b>Language:</b> Python</li>
    <li><b>Libraries:</b> pandas, numpy, scikit-learn</li>
    <li><b>Data:</b> Parkinson's disease dataset with biomedical voice measurements</li>
    <li><b>Algorithm:</b> Support Vector Machine (SVM) with linear kernel</li>
    <li><b>Techniques:</b> Data standardization, train-test split, accuracy evaluation</li>
  </ul>

- <h3><a href="https://github.com/LuisNagano/cardiovascular_disease_prediction" style="text-decoration: underline;">Cardiovascular Disease Prediction Using Machine Learning</a></h3>
  This project aims to develop a tool to increase the accuracy of cardiovascular disease diagnosis for Cardio Catch Diseases company. The analysis includes feature engineering, exploratory data analysis, machine learning modeling, and evaluation of various algorithms such as Logistic Regression, KNN, Random Forest, and XGBoost. The final model (optimized XGBoost) achieves an accuracy of 71.4% on unseen data, representing a significant improvement over the current manual method (55-65% accuracy).
  
  <b>Technologies used:</b>
  <ul>
    <li><b>Language:</b> Python</li>
    <li><b>Libraries:</b> pandas, numpy, scikit-learn, xgboost, seaborn, matplotlib</li>
    <li><b>Data:</b> Dataset of biomedical measurements related to cardiovascular diseases</li>
    <li><b>Algorithms:</b> Logistic Regression, KNN, SVM, Random Forest, XGBoost</li>
    <li><b>Techniques:</b> Feature engineering, exploratory data analysis, hyperparameter optimization, cross-validation</li>
    <li><b>Deployment:</b> Flask API for serving model predictions</li>
  </ul>
  
## Artificial Intelligence Projects

- <h3><a href="https://github.com/LuisNagano/Chatbot-Music-Store" style="text-decoration: underline;">GuitarBot - Music Store Order Collection</a></h3>
  GuitarBot is an automated service designed to collect orders for a music store using OpenAI's GPT-3.5-turbo. This project showcases the integration of OpenAI's conversational AI with a graphical user interface (GUI) created using the Panel library. GuitarBot interacts with customers to take orders for guitars and related accessories, providing a seamless and interactive shopping experience.


## Blog Posts


## Languages and Tools

<div align="left" style="display: flex; flex-wrap: wrap; justify-content: space-between;">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge" height="25" alt="python logo" />
  <img src="https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white&style=for-the-badge" height="25" alt="r logo" />
  <img src="https://img.shields.io/badge/Perl-39457E?logo=perl&logoColor=white&style=for-the-badge" height="25" alt="perl logo" />
  <img src="https://img.shields.io/badge/GNU Bash-4EAA25?logo=gnubash&logoColor=white&style=for-the-badge" height="25" alt="bash logo" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white&style=for-the-badge" height="25" alt="mysql logo" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=black&style=for-the-badge" height="25" alt="jupyter logo" />
  <img src="https://img.shields.io/badge/RStudio-75AADB?logo=rstudio&logoColor=black&style=for-the-badge" height="25" alt="rstudio logo" />
  <img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black&style=for-the-badge" height="25" alt="linux logo" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge" height="25" alt="docker logo" />
  <img src="https://img.shields.io/badge/Sass-CC6699?logo=sass&logoColor=black&style=for-the-badge" height="25" alt="sass logo" />
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white&style=for-the-badge" height="25" alt="git logo" />
  <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=for-the-badge" height="25" alt="github logo" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=black&style=for-the-badge" height="25" alt="tensorflow logo" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white&style=for-the-badge" height="25" alt="pytorch logo" />
  <img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white&style=for-the-badge" height="25" alt="numpy logo" />
  <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white&style=for-the-badge" height="25" alt="pandas logo" />
</div>


###

## Stats
<div align="center">
<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=luisnagano&show_icons=true&locale=en&layout=compact" alt="luisnagano" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=luisnagano&show_icons=true&locale=en" alt="luisnagano" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=luisnagano&" alt="luisnagano" /></p>
</div>
