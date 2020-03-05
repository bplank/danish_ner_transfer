# transfer_ner
Repository accompanying NER (Named Entity Recognition) transfer paper (NoDaLiDa 2019)

## Data overview

<div id="ref:stats">

|             |                                    |                                     |                                     |                                      |
| :---------- | ---------------------------------: | ----------------------------------: | ----------------------------------: | -----------------------------------: |
|             |                                    |                                     |                                     |                                      |
|             | <span class="smallcaps">Dev</span> | <span class="smallcaps">Test</span> | <span class="smallcaps">Train Tiny (5k)</span> | <span class="smallcaps">Train Small (10k)</span> |
| Sentences   |                                564 |                                 565 |                                 272 |                                  604 |
| Tokens      |                             10,332 |                              10,023 |                               4,669 |                               10,069 |
| Types       |                              3,640 |                               3,424 |                               1,918 |                                3,525 |
| TTR         |                               0.35 |                                0.34 |                                0.41 |                                 0.35 |
| Sent.w/ NE  |                                220 |                                 226 |                                  96 |                                  206 |
| Sent.w/ NE% |                                39% |                                 34% |                                 35% |                                  34% |
| Entities    |                                347 |                                 393 |                                 153 |                                  341 |

Overview of the annotated Danish NER data. Around 35%-39% of the
sentences contain NEs. TTR: type-token ratio. Table reported from Plank (2019).

</div>

## References 
If you use this resource, please cite the paper and the references to the Danish UD data:

* Plank, Barbara. Neural Cross-Lingual Transfer and Limited Annotated Data for Named Entity Recognition in Danish. NoDaLiDa, 2019.

* Johannsen, Anders, Martínez Alonso, Héctor and Plank, Barbara.
  "Universal Dependencies for Danish". TLT14, 2015.

* Buch-Kromann, Matthias T., Line Mikkelsen, and Stine Kern Lynge.
  "Danish dependency treebank.". TLT, 2003.

* Keson, Britt (1998). Documentation of The Danish Morpho-syntactically Tagged PAROLE Corpus.
Technical report, DSL
