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
If you use this resource, please cite:

```
@inproceedings{plank-2019-neural,
    title = "Neural Cross-Lingual Transfer and Limited Annotated Data for Named Entity Recognition in {D}anish",
    author = "Plank, Barbara",
    booktitle = "Proceedings of the 22nd Nordic Conference on Computational Linguistics",
    month = "30 " # sep # " {--} 2 " # oct,
    year = "2019",
    address = "Turku, Finland",
    publisher = {Link{\"o}ping University Electronic Press},
    url = "https://www.aclweb.org/anthology/W19-6143",
    pages = "370--375",
    abstract = "Named Entity Recognition (NER) has greatly advanced by the introduction of deep neural architectures. However, the success of these methods depends on large amounts of training data. The scarcity of publicly-available human-labeled datasets has resulted in limited evaluation of existing NER systems, as is the case for Danish. This paper studies the effectiveness of cross-lingual transfer for Danish, evaluates its complementarity to limited gold data, and sheds light on performance of Danish NER.",
}
```
