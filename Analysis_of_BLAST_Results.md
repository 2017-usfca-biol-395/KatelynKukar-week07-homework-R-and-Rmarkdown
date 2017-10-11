Analysis of BLAST Results
================
Katelyn B. Kukar
October 6, 2017

Introduction
============

Creating alternative ways of identification is highly important within the field of Forensics because this would allow for more specific analysis of potential suspects. By being able to compare blood, fingerprints, and other means of testing methods allows for a higher level of statistical significance for true suspect identification. Creating alternative methods is also important since some investigations of suspects of interest lack both DNA evidence and individual fingerprints allowing for ambiguity that could be resolved via other testing means. In Fierer et al., scientists explain that bacteria colonized on individual hands represent highly specific and diverse communities. They believe that "because skin bacterial communities are personalized, \[they\] could use the residual skin bacteria left on objects for forensic identification, matching the bacteria on the object to the skin-associated bacteria of the individual who touched the object," (Fierer et al.).

Within this study we analyze data collected from the Fierer Lab in Colorado through sequencing and computational techniques. The information gathered from the sequencing sets will be evaluated to further evidence towards the validity of utilizing such methods within forensic analysis. Specifically this analysis will utilize prior knowledge geared towards differences between the male and female sex. We hypothesize the female sex will have signficantlly different data than that of the male sex due to physiological and behavioral differences. Certain assumptions for this hypothesis include males having traditionally different hand shape and size, body hair, and fat percentage which constitue physiological differences. Assumptions of behavior for these differences are based on hygiene patterns experienced by males and females due to cultural biases towards the feminine construct.

Methods
=======

Sample origin, sequencing and computational techniques were utilized to analyze sequencing sets collected from human participants and coinciding mice which were touched by each participant in the study.

Sample origin and sequencing
----------------------------

Computational
-------------

In order to analyze the sequences received we used computational programs to evaluate species of interest. First, we analyzed the Fastq files which stored the biological sequences ran by evaluating the quality control number contained. We looked at the coressponding quality score in a chart to ensure the sequencing data was coherent and applicable to our study (no outliers due to contamination or fault sequencing techniques). Second, we took sequences gathered in Fastq files and ran them against a program to trim and align each length for optimal analysis. We then used a secondary program to

Results
=======

The results section was primarily used to extrapolate data in regards to female participants and the specific bacterial communities identified. This section outlines statistical analyses used to filter through the data set to identify the specific bacterial communties and where they arose against male counterpots.

    ## Warning: package 'dplyr' was built under R version 3.4.2

The data first needed to be subsetted by human genomic data which was done though the extrapolation of "Sebum," utilizing the percent identification for each sequence.

**Figure 1a.** Histogram of Percent Identity of Human Environmental Material within Whole Data

![](Analysis_of_BLAST_Results_files/figure-markdown_github-ascii_identifiers/histograms-1.png)

Once primarily human genomic data was extrapolated, only the female data was further filtered out utilizing the percent indentification for each sequence

**Figure 1b.** Histogram of Percent Identity of Human Environmental Material Analyzed for Females

![](Analysis_of_BLAST_Results_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-1-1.png)

The data next needed to be subsetted by human genomic data which was done though the extrapolation of "Sebum," utilizing the sequence length for each sequence as a secondary check against percent identity matches. These two characters were constantly used to analyze the data throughout the experiment.

**Figure 2a.** Histogram of Query Sequence Length of Human Environmental Material within Whole Data

![](Analysis_of_BLAST_Results_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-2-1.png)

Once primarily human genomic data was extrapolated, only the female data was further filtered out utilizing the sequence length for each sequence.

**Figure 2b.** Histgram of Query Sequence Length of Human Environmental Material Analyzed for Females

![](Analysis_of_BLAST_Results_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-3-1.png)

Once the data had been subsetted by both sequence length and percent identity match, to visualize potential skews and data indescrepancies, a further analyses was done to quantify the amount of specific bacterial colonies seen on female participant samples.

**Table 1** Most Common Bacterial Communities visualized within Female Participants

| Scientific Names       |  Count|
|:-----------------------|------:|
| Bartonella washoensis  |    678|
| Acidovorax sp.         |    173|
| unidentified bacterium |     85|
| Lupinus angustiflorus  |     76|
| Methylophilus quaylei  |     55|

**Figure 3** Bar Graph of Most Common Bacterial Communities visualized within Female Participants

![](Analysis_of_BLAST_Results_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-4-1.png)

After the most common bacteiral species was identified for the sex of interest analysis of the data was done through a histogram to visualize the frequency of this specific bacterial community, in regards to percent identity and base pair length within the sequences.

**Figure 4a.** Histogram for Percent Identity of Human Environmental Material Analyzed for Females for Most Common Bacterial Community Found

![](Analysis_of_BLAST_Results_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-5-1.png)

**Figure 4b.** Histogram for Query Sequence Length of Human Environmental Material Analyzed for Females for Most Common Community Found

![](Analysis_of_BLAST_Results_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-6-1.png)

After female analyses were run it was concluded that a potential difference could be present between the sexes due to behavioral and physiological traits. To further investigate these differences within sex analyses were continued on male participant data using the most common bacterial species.

**Table 2** Most Common Bacterial Communities visualized within Male Participants

| Scientific Names                   |  Count|
|:-----------------------------------|------:|
| Solemya pervernicosa gill symbiont |   1549|
| Aquitalea sp. KJ011                |    500|
| Acidovorax sp.                     |    170|
| Pinus oocarpa                      |    127|
| Acinetobacter junii                |    117|

**Figure 5.** Bar Graph of Most Common Bacterial Communities visualized within Male Participants

![](Analysis_of_BLAST_Results_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-8-1.png)

After the most common bacteiral species was identified for the sex of interest analysis of the data was done through a histogram to visualize the frequency of this specific bacterial community, in regards to percent identity and base pair length within the sequences. This was done specifically for the male population due to the visualization of differing bacterial communities from the female specific analyses done prior.

**Figure 6a.** Histogram of Percent Identity of Human Environmental Material Analyzed for Males for Most Common Community Found

![](Analysis_of_BLAST_Results_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-9-1.png)

**Figure 6b.** Histogram of Query Sequence Length of Human Environmental Material Analyzed for Males for Most Common Community Found

![](Analysis_of_BLAST_Results_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-10-1.png)

After both male and female data sets were individually analyzed comparitive measures were taken to showcase differences in percent identity and seqeunce lengths overall. In this way sex specific interpretations could be made towards bacterial communities visualized based on original sequence data received.

**Figure 7a.** Percent Match for Male Verus Female Participants

![](Analysis_of_BLAST_Results_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-11-1.png)

**Figure 7b.** Length of Sequences for Male versus Female Participants

![](Analysis_of_BLAST_Results_files/figure-markdown_github-ascii_identifiers/gplot2-1.png)

Discussion
==========

Add 2-3 paragraphs here interpreting your results and considering future directions one might take in analyzing these data.
