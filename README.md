# MAIA project repository
This repository contains the data created under the [MAIA](https://aclanthology.org/2020.eamt-1.68.pdf) project.

The corpus is composed of entire, genuine and original bilingual conversations from four different clients of the Unbabel database. 
The conversations are from clients that gave written consented on using this data for research purposes as long as in accordance with the General Data Protection Regulation (GDPR).

In this corpus, the original segments of *customers* and *agents* are translated into their corresponding target languages via the MTPE process, done by the experienced translators of the Unbabel Community that have demonstrated consistently high quality within the respective language pair.
MT segments were produced with a mixed of online MT services and internal ones. 

## Anonymization process
To make the conversations publicly available and in accordance with the General Data Protection Regulation (GDPR), the data was anonymized first automatically by using the Unbabel proprietary anonymization tool and then was manually verified. 
This resulted in 12 different anonymization categories, each presented by a specific token that are presented in Table below. 
| Token | Description |
|:---|:---|
| \#NAME\# | Person’s names |
| \#PRS\_ORG\# | Products, Services, and Organizations |
| \#ADDRESS\#  | Address |
| \#EMAIL\#  | E-mail address |
| \#IP\# | IP Address |
| \#PASSWORD\# | Password |
| \#PHONENUMBER\# | Phone number |
| \#CREDITCARD\# | Credit card number |
| \#URL\# | URL Address |
| \#IBAN\# | IBAN Address |
| \#NUMBER\# | Any number (all digits) |
| \#ALPHANUMERIC\_ID\# | Any alphanumeric ID |

## Corpus statistics
The MAIA corpus contains more than 40k segments from more than 900 conversations in three language pairs (and a total of 6 language directions): English⇔German (en⇔de), English⇔French (en⇔fr) and English⇔Portuguese (Brazil) (en⇔pt-br). 
The breakdown of the corpus by language pair and direction are presented in Table below.
|     | en⇔de | en⇔fr | en⇔pt-br |
|:---|:---:|:---:|:---:|
| Number of conversations | 496 | 264 | 164 |
| Number of agent segments | 8,509 | 9,911 | 4,741 |
| Number of customer segments | 9,468 | 5,115 | 3,674 |
| Number of total (customer and agent) segments | 17,977 | 15,026 | 8,415 |

## License
MAIA corpus is released under the Creative Commons public license Attribution-NoDerivatives 4.0 International ([CC BY-ND 4.0](https://creativecommons.org/licenses/by-nc/4.0)) and can be freely used for research purposes only.
Please note that, as the license states, no commercial uses are permitted for this corpus.

## Citation
Please cite the following papers, if you use this corpus in your work.

```bibtex
@inproceedings{martins-etal-2020-project,
    title = "Project {MAIA}: Multilingual {AI} Agent Assistant",
    author = "Martins, Andr{\'e} F. T.  and
      Graca, Joao  and
      Dimas, Paulo  and
      Moniz, Helena  and
      Neubig, Graham",
    booktitle = "Proceedings of the 22nd Annual Conference of the European Association for Machine Translation",
    month = nov,
    year = "2020",
    address = "Lisboa, Portugal",
    publisher = "European Association for Machine Translation",
    url = "https://aclanthology.org/2020.eamt-1.68",
    pages = "495--496",
}
```
```bibtex
@inproceedings{farinha-etal-2022,
    title = "Findings of the {WMT} 2022 Shared Task on Chat Translation",
    author = "Farinha, Ana C. and
    Farajian, M. Amin and
    Buchicchio, Marianna and
    Fernandes, Patrick and
    de Souza, Jos{\'e} G. C. and
    Moniz, Helena  and
    Martins, Andr{\'e} F. T.",
    booktitle = "Proceedings of the Seventh Conference on Machine Translation (WMT22)",
    month = dec,
    year = "2022",
    address = "Abu Dhabi",
    publisher = "Association for Computational Linguistics",
}
```
