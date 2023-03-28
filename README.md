# Uterine-Cervix-and-Corpus-cancers-characterization-through-gene-expression-analysis-using-Knowseq

This repository collects the code used for the work "Uterine Cervix and Corpus Cancers Characterization through Gene Expression Analysis Using the Knowseq Tool".

Department of Computer Engineering, Automatics and Robotics,University of Granada. C.I.T.I.C., Periodista Rafael Gómez Montero, 2, 18014. Granada, Spain.

luciaalmorox@correo.ugr.es

- ***Healthy_CervixTumor_CorpusTumor*** folder: contains files related to the characterization of healthy, cervical cancer and uterine corpus cancer samples. *Preprocesamiento_CERVIX_CORPUS_HEALTHY.Rmd* document produces all the R objects that the *Clasificación_CERVIX_CORPUS_HEALTHY.Rmd* document takes as input.
  - ***Preprocesamiento_CERVIX_CORPUS_HEALTHY.Rmd***: document developed for preprocessing gene expression quantification data related to cervical cancer or uterine corpus cancer patients, considering the classes "HEALTHY", "CERVIX_TUMOR" and "CORPUS_TUMOR". The data was obtained from TCGA (through the GDC portal). 
  - ***Clasificación_CERVIX_CORPUS_HEALTHY.Rmd***: document developed for gene expression analysis in the classes of interest. It includes the identification of DEGs, the analysis of the three KnowSeq feature selection methods, the implementation of cross-validations using kNN with different numbers of genes, the determination and evaluation of a gene signature, its biological enrichment (gene ontology, diseases and pathways), and the generation of graphical information.

- ***CervicalAdenocarcinoma_CervicalSquamousCellCarcinoma*** folder: contains files related to the characterization of cervical adenocarcinoma and cervical squamous cell carcinoma samples. Additionally, it includes the classification experiment of a mixed sample (adenosquamous) into one of these two histological types. Both the objects produced by the *Preprocesamiento_ADENO_SQUAMOUS_ADENOSQUAMOUS.Rmd* document and by the *Preprocesamiento_cervix_ADENO_SQUAMOUS.Rmd* document are taken as input by the *Clasificación_cervix_ADENO_SQUAMOUS.Rmd* document.
  - ***Preprocesamiento_ADENO_SQUAMOUS_ADENOSQUAMOUS.Rmd***: document developed for preprocessing gene expression quantification data related to cervical cancer patients, considering the classes "ADENO" and "SQUAMOUS". The data was obtained from TCGA (through the GDC portal).
  - ***Preprocesamiento_cervix_ADENO_SQUAMOUS.Rmd***: document developed for preprocessing gene expression quantification data related to cervical cancer patients, considering the classes "ADENO", "SQUAMOUS" and "ADENOSQUAMOUS". The data was obtained from TCGA (through the GDC portal).
  - ***Clasificación_cervix_ADENO_SQUAMOUS.Rmd***: document developed for gene expression analysis in the classes of interest. It includes the identification of DEGs, the implementation of cross-validation using kNN with different numbers of genes, and the generation of graphical information.
