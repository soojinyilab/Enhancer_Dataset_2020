# Enhancer_Dataset_2020

#Overview of files associated with "A study of the enhancer-gene interaction architecture: linking enhancer pleiotropy to gene expression breadth in the human genome" (Singh and Yi 2020)

#-------------------------------
1.enhancer_dataset_state15.bed

 - BED format file containing all merged and processed genomic coordinates (Hg19) for enhancers identified by chromatin state
    state 6 (genic enhancers) and state 7 (enhancers)
 - Fields (tab-separated):
    [1]chromosome [2]start [3]stop [4]enhancer index [5]length (bp) [6]enhancer pleiotrophy category [7]number of tissues [8]list of tissues
 - Unprocessed files were obtained from the NIH Roadmap Epigenomics Mapping Consortium  (http://www.roadmapepigenomics.org/)
     List of Epigenomes with Roadmap EID
     E008_ESC        ESC
     E015_ESC        ESC
     E034_BLOOD      Blood
     E050_BLOOD      Blood
     E059_SKIN       Skin
     E063_FAT        Fat
     E066_LIVER      Liver
     E071_BRAIN      Brain
     E073_BRAIN      Brain
     E075_GI_COLON   Colon
     E076_GI_COLON   Colon
     E078_GI_DUODENUM        Duodenum
     E079_GI_ESOPHAGUS       Esophagus
     E080_ADRENAL    Adrenal
     E081_BRAIN      Brain
     E082_BRAIN      Brain
     E083_HEART      Heart
     E084_GI_INTESTINE       Intestine
     E085_GI_INTESTINE       Intestine
     E086_KIDNEY     Kidney
     E087_PANCREAS   Pancreas
     E088_LUNG       Lung
     E089_MUSCLE     Muscle
     E090_MUSCLE     Muscle
     E091_PLACENTA   Placenta
     E092_GI_STOMACH Stomach
     E093_THYMUS     Thymus
     E094_GI_STOMACH Stomach
     E095_HEART      Heart
     E096_LUNG       Lung
     E097_OVARY      Ovary
     E098_PANCREAS   Pancreas
     E099_PLACENTA   Placenta
     E101_GI_RECTUM  Rectum
     E103_GI_RECTUM  Rectum
     E108_MUSCLE     Muscle
     E109_GI_INTESTINE       Intestine
     E111_GI_STOMACH Stomach
     E112_THYMUS     Thymus
     E113_SPLEEN     Spleen
     E126_SKIN       Skin
     E128_LUNG       Lung
     E129_BONE       Bone

 - Enhancer merging protocol:
        The union of all enhancers across all samples was taken and outlier regions with the top 5% length (length > 3,500 bp) were removed.
        Any enhancer regions which overlapped more than 50% were merged.

#-------------------------------------
