# Record Linkage

## Strategy

R functions for record linkage with big data

- Use R-package `datatable`

- Use R-package matrix and the function `sparse` for triangular matrixes 

- Editing is important 

- Use a sequential strategy

- See through the data as rarely as possible.

- Use R-package parallel for parallelization

## R packages

### fastLink package

- [geht posterior Probst](https://www.rdocumentation.org/packages/fastLink/versions/0.6.0/topics/getPosterior)


- [Github page for the fastLink package](https://github.com/kosukeimai/fastLink)

- [How to go parallel](https://www.r-bloggers.com/2015/02/how-to-go-parallel-in-r-basics-tips/)


- [ludic package](https://www.nature.com/articles/sdata2018298)


- [diyar package](https://olisansonwu.github.io/diyar/index.html)


- [Matching methods](https://cran.r-project.org/web/packages/MatchIt/vignettes/matching-methods.html)

- [Matching Package](https://www.r-project.org/conferences/useR-2007/program/presentations/sekhon.pdf)

### Matching probability

- [p.gamma.k.m: The posterior of the matching probability for a specific matching field.](https://www.opensourceagenda.com/projects/fastlink)


- [stack_fastLink_matches.R](https://github.com/brad-cannell/cerebro/blob/master/stack_fastLink_matches.R)

- [match_probabilities_code.R](https://github.com/tnecamp/match_probabilities/blob/master/match_probabilities_code.R)

- [Keypoint filtering based on matching probability](https://github.com/AlexandraPapadaki/Match-or-no-match-Keypoint-filtering-based-on-matching-probability/blob/main/README.md) - [function](https://github.com/AlexandraPapadaki/Match-or-no-match-Keypoint-filtering-based-on-matching-probability)

- [emlinkRS](https://www.rdocumentation.org/packages/fastLink/versions/0.6.0/topics/emlinkRS)

### R Literature


- [Using a Probabilistic Model to Assist Merging
of Large-scale Administrative Records](https://oar.princeton.edu/jspui/bitstream/88435/pr1r180/1/%5BAPSR%5Dlinkage.pdf)

- [Fast String Matching by Using Probabilities:
On an Optimal Mismatch Variant of Horspool’s Algorithm](http://wwwagak.informatik.uni-kl.de/downloads/papers/Fast_String_Matching_by_Using_Probabilities_On_an_Optimal_Mismatch_Variant_of_Horspools_Algorithm.pdf)


- [Data Engineering, Record Linking and Deduplication](https://open-canada.github.io/r4gc/data-engineering-record-linking-and-deduplication.html)


- [MatchIt: Nonparametric Preprocessing for
Parametric Causal Inference](https://r.iq.harvard.edu/docs/matchit/2.4-20/matchit.pdf)

### Data Import

- [How to import only some lines of a csv?](https://stackoverflow.com/questions/23197243/how-to-read-only-lines-that-fulfil-a-condition-from-a-csv-into-r)
- [Check file size before import](https://stackoverflow.com/questions/30580798/how-to-check-file-size-before-opening)
- [Introduction to dbplyr](https://cran.r-project.org/web/packages/dbplyr/vignettes/dbplyr.html)

### Data Processing

- [Use EACHI in data.table](https://stackoverflow.com/questions/27004002/eachi-in-data-table/27004566#27004566)

### Spark

- [sparklyr](https://cran.r-project.org/web/packages/sparklyr/index.html)
- [SparkR](http://spark.apache.org/docs/latest/sparkr.html)
- [Book on mastering Spark in R](https://therinspark.com/)

- Record Linkage - [Fuzzy Matching and Deduplicating Hundreds of Millions of Records using Apache Spark](

## Theory on the EM Algorithm

- [Peter Pfaffelhuber - Der E(xpectation-)M(aximization)-Algorithmus](https://www.stochastik.uni-freiburg.de/lehre/WS-2015/mathstat/emskript)


## Key words

- Multibit-Trees, [Bloom-Filter](https://en.wikipedia.org/wiki/Bloom_filter)

# Record Linkage with Python

https://recordlinkage.readthedocs.io/en/latest/notebooks/link_two_dataframes.html#Make-record-pairs

https://recordlinkage.readthedocs.io/en/latest/notebooks/classifiers.html

# Research Papers and Literature

- Ted Enamorado et al. -  [Using a Probabilistic Model to Assist Merging of Large-Scale
Administrative Records](https://imai.fas.harvard.edu/research/files/linkage.pdf)
- [Online Supplementary Information for “Using a
Probabilistic Model to Assist Merging of
Large-scale Administrative Records.”](https://static.cambridge.org/content/id/urn:cambridge.org:id:article:S0003055418000783/resource/name/S0003055418000783sup001.pdf)

- [Research paper of the European Comission on Data Linkage](https://ec.europa.eu/eurostat/cros/system/files/s-dwh-m_4.2_methodology_data_linkage_v2.pdf)

- [Privacy-Preserving Record Linkage for Big Data: Current Approaches and Research Challenges](https://link.springer.com/chapter/10.1007/978-3-319-49340-4_25)

- Gilbert - [GUILD: GUidance for Information about Linking Data sets](https://harveygoldsteinweb.files.wordpress.com/2018/11/guidelines-for-information-about-record-linkage.pdf)

- [Privacy Preserving Record Linkage](https://www.scads.de/de/2-uncategorised/316-privacy-preserving-record-linkage)

## Youtube Videos

[Building a Scalable Record Linkage System with Apache Spark, Python 3, and Machine Learning](https://www.youtube.com/watch?v=iQiaZKU3n0Y&ab_channel=Databricks)

[R Data Analysis Projects: Demonstrating the Use of RecordLinkage Package](https://www.youtube.com/watch?v=Msl1Q5Yv8Ow&ab_channel=PacktVideo)

[Probabilistic Record Linkage of Hospital Patients - Chris Oakman](https://www.youtube.com/watch?v=rGKEOMUtJfE&t=570s&ab_channel=ClojureTV)


