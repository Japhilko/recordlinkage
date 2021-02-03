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

- [Github page for the fastLink package](https://github.com/kosukeimai/fastLink)

- [How to go parallel](https://www.r-bloggers.com/2015/02/how-to-go-parallel-in-r-basics-tips/)


### Data Import

- [How to import only some lines of a csv?](https://stackoverflow.com/questions/23197243/how-to-read-only-lines-that-fulfil-a-condition-from-a-csv-into-r)
- [Check file size before import](https://stackoverflow.com/questions/30580798/how-to-check-file-size-before-opening)

### Spark

- [sparklyr](https://cran.r-project.org/web/packages/sparklyr/index.html)
- [SparkR](http://spark.apache.org/docs/latest/sparkr.html)

- Record Linkage - [Fuzzy Matching and Deduplicating Hundreds of Millions of Records using Apache Spark](

## Key words

- Multibit-Trees, [Bloom-Filter](https://en.wikipedia.org/wiki/Bloom_filter)

# Research Papers and Literature

- TED ENAMORADO et al. -  [Using a Probabilistic Model to Assist Merging of Large-Scale
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


