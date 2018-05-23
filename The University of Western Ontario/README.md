# datamicroarray

The dataset of the University of Western Ontario.

## Data Sets

Each data set is listed below by the first author on the original paper. The data sets are organized them by category; note that most of the data sets are cancer-related. Click a data set to see its description, a link to the original paper, and additional information.

* Breast Cancer
  * [Alon (1999)]()
  * [BRAC1]()
  * [BRAC2]()
  * [Gaussian])()
  * [Golub (1999)]()
  * [Iizuka ()]()
  * [Mixture ()]()
  * [Nutt ()]()
  * [Singh ()]()
  * [Spira ()]()
  * [Sporadic ()]()
  * [Veer ()] ()

## Usage

Once you have installed and loaded the `datamicroarray` package, you can load a data set with the `data` command. For example, to load the well-known [Alon et al. (1999) Colon Cancer data set](https://github.com/ramey/datamicroarray/wiki/Alon-%281999%29), type the following at the R console:

```r
library(datamicroarray)
data('alon', package = 'datamicroarray')
```

After loading the data set, the resulting object is a named `list` with two elements:

1. `x` - the data matrix. The rows are the `n` observations, and the columns are the `p` features.
2. `y` - a factor vector of length `n` with the corresponding class labels.

Here is a summary for the [Alon et al. (1999) Colon Cancer data set](https://github.com/ramey/datamicroarray/wiki/Alon-%281999%29).

## Alon et al. (1999)
* Description

Response is y=1 or y=-1 according as tissue is normal or tumor There are 2000 gene expressions.
 
* Detail

Colon adenocarcinoma tissues were collected from patients and from some of these patients, paired normal colon tissue also was obtained. Gene expression in 40 tumor and 22 normal colon tissue samples was analyzed with an Affymetrix oligonucleotide array complementary to more than 6500 human genes. The data set contains the expression of the 2000 genes with highest minimal intensity across the 62 tissues. Each gene intensity has been derived from the about 20 feature pairs that correspond to the gene on the chip by using a filtering process. The data is otherwise unprocessed, i.e. no normalization has been performed yet. The training set consists of 40 colon tissues of which 14 are normal and 26 tumor samples. The test set consists of 22 tissues of which 8 are normal and 14 tumor samples. The number of gene expression levels is 2000. The goal here is to classify the tissues as being cancerous or noncancerous.

* References

Alon,A., Barkai,N., Notterman,D.A., Gish,K., Ybarra,S., Mack,D., and Levine,A.J. (1999) Broad Patterns of Gene Expression Revealed by Clustering Analysis of Tumor and Normal Colon Tissues Probed by Oligonucleotide Arrays, Proc. Natl. Acad. Sci. USA, 96,6745-6750.

## Alon et al. (1999)
* Description
 
* Detail

* References

## BRAC1 Hendenfalk et al. (2004)
* Description

Response is y=1 or y=-1 according as have BRAC1 mutation or not. There are 3226 gene expressions.
 
* Detail

Breast cancer data set (Hedenfalk et al., 2001). RNA from samples of primary breast tumors from 7 carriers of the BRCA1 mutation, 8 carriers of the BRCA2 mutation, and 7 patients with sporadic cases of breast cancer have been hybridized to a cDNA microarray containing 6512 complementary DNA clones of 5361 genes. The goal here is to classify the different mutations, so three combinations are possible in this case. First, tissues with BRCA1 mutations are separated from the tissues with BRCA2 or sporadic mutations. The training set consists of 14 breast cancer tissues of which 4 have a BRCA1 mutation and 10 have not. The test set consists of 8 tissues of which 3 have a BRCA1 mutation and 5 have not. The number of gene expression levels is 3226. Second, tissues with BRCA2 mutations are separated from the tissues with BRCA1 or sporadic mutations. The training set consists of 14 breast cancer tissues of which 5 have a BRCA1 mutation and 9 have not. The test set consists of 8 tissues of which 3 have a BRCA1 mutation and 5 have not. The number of gene expression levels is 3226. Third, tissues with sporadic mutations are separated from the tissues with BRCA1 or BRCA2 mutations. The training set consists of 14 breast cancer tissues of which 4 have a BRCA1 mutation and 10 have not. The test set consists of 8 tissues of which 3 have a BRCA1 mutation and 5 have not. The number of gene expression levels is 3226.

* References

Hedenfalk,I., Duggan,D., Chen,Y., Radmacher,M., Bittner, M., Simon,R., Meltzer,P., Gusterson,B., Esteller,M., Raffeld,M., Yakhini,Z., Ben-Dor,A., Dougherty,E., Kononen,J., Bubendorf,L., Fehrle,W., Pittaluga,S., Gruvberger,S., Loman,N., Johannsson,O., Olsson,H., Wilfond,B., Sauter,G., Kallioniemi,O.-P., Borg,A. and Trent,J. (2001) Gene-Expression Profiles in Hereditary Breast Cancer,

## BRAC2 Hendenfalk et al. (2004)
* Description

Response is y=1 or y=-1 according as have BRAC2 mutation or not. There are 3226 gene expressions.
 
* Detail

Breast cancer data set (Hedenfalk et al., 2001). RNA from samples of primary breast tumors from 7 carriers of the BRCA1 mutation, 8 carriers of the BRCA2 mutation, and 7 patients with sporadic cases of breast cancer have been hybridized to a cDNA microarray containing 6512 complementary DNA clones of 5361 genes. The goal here is to classify the different mutations, so three combinations are possible in this case. First, tissues with BRCA1 mutations are separated from the tissues with BRCA2 or sporadic mutations. The training set consists of 14 breast cancer tissues of which 4 have a BRCA1 mutation and 10 have not. The test set consists of 8 tissues of which 3 have a BRCA1 mutation and 5 have not. The number of gene expression levels is 3226. Second, tissues with BRCA2 mutations are separated from the tissues with BRCA1 or sporadic mutations. The training set consists of 14 breast cancer tissues of which 5 have a BRCA1 mutation and 9 have not. The test set consists of 8 tissues of which 3 have a BRCA1 mutation and 5 have not. The number of gene expression levels is 3226. Third, tissues with sporadic mutations are separated from the tissues with BRCA1 or BRCA2 mutations. The training set consists of 14 breast cancer tissues of which 4 have a BRCA1 mutation and 10 have not. The test set consists of 8 tissues of which 3 have a BRCA1 mutation and 5 have not. The number of gene expression levels is 3226.

* References

Hedenfalk,I., Duggan,D., Chen,Y., Radmacher,M., Bittner, M., Simon,R., Meltzer,P., Gusterson,B., Esteller,M., Raffeld,M., Yakhini,Z., Ben-Dor,A., Dougherty,E., Kononen,J., Bubendorf,L., Fehrle,W., Pittaluga,S., Gruvberger,S., Loman,N., Johannsson,O., Olsson,H., Wilfond,B., Sauter,G., Kallioniemi,O.-P., Borg,A. and Trent,J. (2001) Gene-Expression Profiles in Hereditary Breast Cancer,

## Gaussian with two classes
* Description

Two predictor variables generated from a bivariate normal distribution. The covariance matrix is different for each class. In the training sample, there is a separating hyperplane.
 
* Detail

None.

* References

None.

## Golub et al. (1999)
* Description
 
* Detail

* References

## Mixture
* Description

HTF example. Data generated for each class by a mixture of 10 different normal distribution. The training sample is as given by HTF but the test sample was generated independently.
The Bayes error rate for this model is about 21
 
* Detail

None.

* References

None.

## Iizuka et al. (1999)
* Description

Iizuka carcinoma data set.
Response is y=1 or y=-1 according as early intrahepatic recurrence or not There are 7129 gene expressions.
 
* Detail

Hepatocellular carcinoma data set (Iizuka et al., 2003). mRNA expression profiles in tissue specimens from a training set comprising 33 patients with hepatocellular carcinoma have been hybridized with high-density oligonucleotide microarrays representing about 6000 genes. The same has been done for a blinded set of samples from 27 newly enrolled patients. Since hepatocellular carcinoma has a poor prognosis because of the high intrahepatic recurrence rate, the goal here is to predict early intrahepatic recurrence or non-recurrence. The training set consists of 33 hepatocellular carcinoma tissues of which 12 suffer from early intrahepatic recurrence and 21 not. The test set consists of 27 hepatocellular carcinoma tissues of which 8 suffer from early intrahepatic recurrence and 19 not. The number of gene expression levels is 7129.

* References

Iizuka,N., Oka,M., Yamada-Okabe,H., Nishida,M., Maeda,Y., Mori,N., Takao,T., Tamesa,T., Tangoku,A., Tabuchi,H., Hamada,K., Nakayama,H., Ishitsuka,H., Miyamoto,T., Hirabayashi,A., Uchimura,S. and Hamamoto,Y. (2003) Oligonucleotide microarray for prediction of early intrahepatic recurrence of hepatocellular carcinoma after curative resection, The Lancet, 361,923-929.

## High-grade glioma dataset Nutt et al. (2003)
* Description
 
 Response is y=1 or y=-1 according as glioblastomas or anaplastic oligodendrogliomas. There are 12625 gene expressions.
 
* Detail

50 high-grade glioma samples were carefully selected, 28 glioblastomas and 22 anaplastic oligodendrogliomas, all were primary tumors sampled before therapy. The classic subset of tumors were cases diagnosed similarly by all examining pathologists, and each case resembled typical depictions in standard textbooks. A total of 21 classic tumors was selected, and the remaining 29 samples were considered nonclassic tumors, lesions for which diagnosis might be controversial. Affymetrix arrays are used to determine the expression of about 12000 genes. The goal here is to separate the glioblastomas from the anaplastic oligodendrogliomas, which allows appropriate therapeutic decisions and prognostic estimation. The training set consists of 21 gliomas with classic histology of which 14 are glioblastomas and 7 anaplastic oligodendrogliomas. The test set consists of 29 gliomas with non-classic histology of which 14 are glioblastomas and 15 are anaplastic oligodendrogliomas. The number of gene expression levels is 12625.

* References

Nutt,C.L., Mani,D.R., Betensky,R.A., Tamayo,P., Cairncross, J.G., Ladd,C., Pohl,U., Hartmann,C., McLaughlin, M.E., Batchelor,T.T., Black,P.M., von Deimling,A., Pomeroy,S.L., Golub,T.R. and Louis,D.N. (2003) Gene expression-based classification of malignant gliomas correlates better with survival than histological classification, Cancer Research, 63(7),1602-1607.

## Smoker dataset Spira et al. (2004)
* Description

Number of genes: 9968. Other covariates including age and gender are available in the original data. The training set consists of 38 subjects and the test data 37.The response y=1 corresonds to a smoker or previous smoker while y=-1 corresponds to an individual who never smoked.
The original data was not divided into training and test. There are 27 males in the training and test datasets. There are 10 females in the training dataset and 9 in the test.
 
* Detail

None.

* References

Avrum Spira, Jennifer Beanea, Vishal Shah, Gang Liu, Frank Schembri, Xuemei Yang, John Palma, and Jerome S. Brody (2004). Effects of cigarette smoke on the human airway epithelial cell transcriptome. PNAS July 6, 2004 vol. 101 no. 27

## Breast cancer Sporadic et al. (2004)
* Description

Response is y=1 or y=-1 according as have BRAC2 mutation or not. There are 3226 gene expressions.
 
* Detail

Breast cancer data set (Hedenfalk et al., 2001). RNA from samples of primary breast tumors from 7 carriers of the BRCA1 mutation, 8 carriers of the BRCA2 mutation, and 7 patients with sporadic cases of breast cancer have been hybridized to a cDNA microarray containing 6512 complementary DNA clones of 5361 genes. The goal here is to classify the different mutations, so three combinations are possible in this case. First, tissues with BRCA1 mutations are separated from the tissues with BRCA2 or sporadic mutations. The training set consists of 14 breast cancer tissues of which 4 have a BRCA1 mutation and 10 have not. The test set consists of 8 tissues of which 3 have a BRCA1 mutation and 5 have not. The number of gene expression levels is 3226. Second, tissues with BRCA2 mutations are separated from the tissues with BRCA1 or sporadic mutations. The training set consists of 14 breast cancer tissues of which 5 have a BRCA1 mutation and 9 have not. The test set consists of 8 tissues of which 3 have a BRCA1 mutation and 5 have not. The number of gene expression levels is 3226. Third, tissues with sporadic mutations are separated from the tissues with BRCA1 or BRCA2 mutations. The training set consists of 14 breast cancer tissues of which 4 have a BRCA1 mutation and 10 have not. The test set consists of 8 tissues of which 3 have a BRCA1 mutation and 5 have not. The number of gene expression levels is 3226.

* References

Hedenfalk,I., Duggan,D., Chen,Y., Radmacher,M., Bittner, M., Simon,R., Meltzer,P., Gusterson,B., Esteller,M., Raffeld,M., Yakhini,Z., Ben-Dor,A., Dougherty,E., Kononen,J., Bubendorf,L., Fehrle,W., Pittaluga,S., Gruvberger,S., Loman,N., Johannsson,O., Olsson,H., Wilfond,B., Sauter,G., Kallioniemi,O.-P., Borg,A. and Trent,J. (2001) Gene-Expression Profiles in Hereditary Breast Cancer,

## Prostate cancer Singh et al. (2002)
* Description
 
 Response is y=1 or y=-1 according as tissue is normal/tumor. There are 12600 gene expressions.
 
* Detail

High-quality expression profiles were successfully derived from 52 prostate tumors and 50 nontumor prostate samples from patients undergoing surgery. Oligonucleotide microarrays containing probes for approximately 12600 genes and ESTs. Since prostate tumors are among the most heterogeneous of cancers, both histologically and clinically, the goal here is to classify tumor and nontumour samples. The training set consists of 102 prostate tissues of which 50 are normal and 52 tumor samples. The test set consists of 34 tissues of which 9 are normal and 25 tumor samples. The number of gene expression levels is 12600.

* References

Singh,D., Febbo,P.G., Ross,K., Jackson,D.G., Manola,J., Ladd,C., Tamayo,P., Renshaw,A.A., D'Amico,A.V., Richie,J.P., Lander,E.S., Loda,M., Kantoff,P.W., Golub,T.R. and Sellers,W.R. (2002) Gene expression correlates of clinical prostate cancer behavior, Cancer Cell, 1(2),203-209.

## Breast cancer Van't Veer et al. (2002)
* Description

Response is y=1 or y=-1 according as develop metastases or disease free. There are 24188 gene expressions.
 
* Detail

78 primary breast cancers (34 from patients who developed distant metastases within 5 years and 44 from patients who continue to be disease-free after a period of at least 5 years) have been selected from patients who were lymph node negative and under 55 years of age at diagnosis. Two hybridizations were carried out for each tumour using a fluorescent dye reversal technique on microarrays containing approximately 25000 human genes synthesized by an inkjet oligonucleotide technology. The goal here is to predict the presence of subclinical metastases in order to provide a strategy to select patients who would benefit from adjuvant therapy. The training set consists of 78 breast cancer patients of which 34 develop metastases within 5 years and 44 remain disease-free within 5 years. The test set consists of 19 patients of which 12 develop metastases within 5 years and 7 remain disease-free within 5 years. The number of gene expression levels is 24188. This data set contained some missing values. Gene expression levels lacking for all patients are left out. The rest of the missing values is estimated based on the correlations between the gene expressions.

* References

Van't Veer,L.J., Dai,H., Van De Vijver,M.J., He,Y.D., Hart,A.A.M., Mao,M., Peterse,H.L., Van Der Kooy,K., Marton, M.J., Witteveen,A.T., Schreiber,G.J., Kerkhoven,R.M., Roberts,C., Linsley,P.S., Bernards,R. and Friend,S.H. (2002) Gene Expression Profiling Predicts Clinical Outcome of Breast Cancer, Nature, 415,530-536.

##

You can see all of the data sets available along with a brief summary of each with the `describe_data` helper function. Here it is in action:

        author year   n     p K              Disease
1         alon 1999  62  2000 2         Colon Cancer
2    borovecki 2005  31 22283 2 Huntington's Disease
3   burczynski 2006 127 22283 3      Crohn's Disease
4    chiaretti 2004 111 12625 2             Leukemia
5         chin 2006 118 22215 2        Breast Cancer
6     chowdary 2006 104 22283 2        Breast Cancer
7  christensen 2009 217  1413 3                  N/A
8        golub 1999  72  7129 3             Leukemia
9       gordon 2002 181 12533 2          Lung Cancer
10     gravier 2010 168  2905 2        Breast Cancer
11        khan 2001  63  2308 4                SRBCT
12     pomeroy 2002  60  7128 2            CNS Tumor
13       shipp 2002  58  6817 2             Lymphoma
14       singh 2002 102 12600 2      Prostate Cancer
15      sorlie 2001  85   456 5        Breast Cancer
16          su 2002 102  5565 4                  N/A
17 subramanian 2005  50 10100 2                  N/A
18        tian 2003 173 12625 2              Myeloma
19        west 2001  49  7129 2        Breast Cancer
20        yeoh 2002 248 12625 6             Leukemia
```
