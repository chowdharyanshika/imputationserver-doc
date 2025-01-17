# Helmholtz Munich Imputation Server (HMIS)

[Helmholtz Munich Imputation Server](https://imputationserver.helmholtz-muenchen.de) provides a free genotype imputation service using [Minimac4](http://genome.sph.umich.edu/wiki/Minimac4). You can upload phased or unphased GWAS genotypes and receive phased and imputed genomes in return. Currently, our server offers imputation from 1000 Genomes and the HapMap 2 reference panel and more reference panels will be added in the future. For all uploaded datasets an extensive QC is performed.

![](images/munich_imputation_server.png)

Please cite this paper if you use Munich Imputation Server in your publication:

> Das S, Forer L, Schönherr S, Sidore C, Locke AE, Kwong A, Vrieze S, Chew EY, Levy S, McGue M, Schlessinger D, Stambolian D, Loh PR, Iacono WG, Swaroop A, Scott LJ, Cucca F, Kronenberg F, Boehnke M, Abecasis GR, Fuchsberger C. [Next-generation genotype imputation service and methods](https://www.ncbi.nlm.nih.gov/pubmed/27571263). Nature Genetics 48, 1284–1287 (2016).


The complete source code is hosted on [GitHub](https://github.com/genepi/imputationserver/) using Travis CI for continuous integration.
