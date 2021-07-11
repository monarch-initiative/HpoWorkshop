.. _rstexomiser:

########
Exomiser
########

Exomiser is an application that prioritizes genes and variants in next-generation sequencing (NGS) projects for novel disease-gene discovery or differential diagnostics of Mendelian disease. 


* Robinson PN, et al (2014) Improved exome prioritization of disease genes through cross-species phenotype comparison. Genome Res;24(2):340-8. [`PMID:24162188 <https://pubmed.ncbi.nlm.nih.gov/24162188/>`_]
* Smedley D (2015) Next-generation diagnostics and disease-gene discovery with the Exomiser. Nat Protoc;10(12):2004-15. [`PMID:26562621 <https://pubmed.ncbi.nlm.nih.gov/26562621/>`_]



Exomiser was among the first bioinformatics tools of its kind, published in 2014 as a freely available Java program. 
It requires as input (i) a variant call format (VCF) file with the called variants of a rare disease patient (or optionally a multi-sample VCF and pedigree (PED) file if family members have also been sequenced) and (ii) a set of HPO terms to describe the corresponding patient’s phenotype. 


A demo version of Exomiser is available on the `Monarch Initiative website <https://exomiser.monarchinitiative.org/exomiser/>`_. 


To try out Exomiser, download the example file with a causative FGFR2 variant for the autosomal dominant Pfeiffer syndrome 
added to exome of a healthy individual. Add HPO terms representing the Phenotype of Pfeiffer syndrome as you have done with the Phenomizer.
You may want to consult the HPO page for `Pfeiffer syndrome <https://hpo.jax.org/app/browse/disease/OMIM:101600>`_ to find appropriate HPO terms.

You can run Exomiser with the default settings or  adjust them (in the latter case, you may want to consult the consult the above cited papers to learn about the meaning of the parameters).


Exercise 1
^^^^^^^^^^

Examine the output of Exomiser. Examine the top 5 candidates and explore the phenotypic and genetic evidence for or against their candidacy.
