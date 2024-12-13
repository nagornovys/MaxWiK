# MaxWiK: Maxima Weighted Isolation Kernel Mapping Method

[![License](https://img.shields.io/badge/License-GPL.3-green.svg)](https://github.com/tugHall/MaxWiK/blob/main/LICENSE.md)

**MaxWiK** *(**Max**ima **W**eighted-**i**solation **K**ernel mapping method)* is a machine learning method of meta-sampling based on Isolation Kernel and Kernel mean embedding. For more details of the method, please, be kind to read the papers:

[Iurii Nagornov, Sampling vs. Metasampling Based on Straightforward Hilbert Representation of Isolation Kernel, In: Arai, K. (eds) Intelligent Systems and Applications. IntelliSys 2024. Lecture Notes in Networks and Systems, vol 1067, pp. 243-258. Springer, Cham, 2024](https://link.springer.com/chapter/10.1007/978-3-031-66431-1_16)

[Iurii Nagornov, Overfitting Problem in the Approximate Bayesian Computation Method Based on Maxima Weighted Isolation Kernel, In: Takama, Y., Yada, K., Satoh, K., Arai, S. (eds) New Frontiers in Artificial Intelligence. JSAI-isAI 2022. Lecture Notes in Computer Science, vol 13859, pp. 267–282, Springer, 2023.](https://link.springer.com/chapter/10.1007/978-3-031-29168-5_18)

[Iurii S. Nagornov, Approximate Bayesian Computation Based on Maxima Weighted Isolation Kernel Mapping, arXiv.2201.12745, 2022](https://doi.org/10.48550/arXiv.2201.12745)

### Authors and contributor list:

**Iurii (Yuri) Nagornov** (Maintainer, Author)

All questions and requests can be sent to [nagornov.yuri\@gmail.com](mailto:nagornov.yuri@gmail.com){.email}

### Short description of the package:

**Motivation:** A branching processes model yields an unevenly stochastically distributed dataset that consists of sparse and dense regions. This work addresses the problem of precisely evaluating parameters for such a model. Applying a branching processes model to an area such as cancer cell evolution faces a number of obstacles, including high dimensionality and the rare appearance of a result of interest. We take on the ambitious task of obtaining the coefficients of a model that reflects the relationship of driver gene mutations and cancer hallmarks on the basis of personal data regarding variant allele frequencies.

**Method:** An approximate Bayesian computation method based on Isolation Kernel is developed. The method involves the transformation of row data to a Hilbert space (mapping) and the measurement of the similarity between simulated points and maxima weighted Isolation Kernel mapping related to the observation point. We also design a meta-sampling algorithm for parameter estimation that requires no gradient calculation and is dimension independent. The advantages of the proposed machine learning method are more clearly can be illustrated using multidimensional data as well as a specific branching processes model like cancer cell evolution.

**Package:** This software is a package named **MaxWiK** contains Approximate Bayesian Computation methods to choose a single parameter for a single observation point.

To install from CRAN:

```         
utils::install.packages("MaxWiK")
```

To install from the archive file 'MaxWiK_1.XX.XX.tar.gz' (1.XX.XX is a release number):

```         
utils::install.packages("./MaxWiK_1.XX.XX.tar.gz", repos = NULL, type = "source")
```

To see how it works, please, be kind use the templates and read vignettes. To get templates, please, use command:

```         
MaxWiK_templates( dir = './' )   # dir can be any working folder where template will be copied
```

### Cite package MaxWiK

For publication, please, be kind to use next references related to MaxWiK software:

-   [Iurii Nagornov, Sampling vs. Metasampling Based on Straightforward Hilbert Representation of Isolation Kernel, In: Arai, K. (eds) Intelligent Systems and Applications. IntelliSys 2024. Lecture Notes in Networks and Systems, vol 1067, pp. 243-258. Springer, Cham, 2024](https://link.springer.com/chapter/10.1007/978-3-031-66431-1_16)

-   [Iurii Nagornov, Overfitting Problem in the Approximate Bayesian Computation Method Based on Maxima Weighted Isolation Kernel, In: Takama, Y., Yada, K., Satoh, K., Arai, S. (eds) New Frontiers in Artificial Intelligence. JSAI-isAI 2022. Lecture Notes in Computer Science, vol 13859, pp. 267–282, Springer, 2023.](https://link.springer.com/chapter/10.1007/978-3-031-29168-5_18)

-   [Iurii S. Nagornov, Overfitting Problem in the Approximate Bayesian Computation Method Based on Maxima Weighted Isolation Kernel, The 36th Annual Conference of the Japanese Society for Artificial Intelligence, 2S5-IS-2c-05, 2022](https://confit.atlas.jp/guide/event/jsai2022/subject/2S5-IS-2c-05/tables?cryptoId=)

-   [Package MaxWiK: https://github.com/tugHall/MaxWiK](https://github.com/tugHall/MaxWiK)
