# PT-LegislativeElections2022
Keyword Extraction from Political Party Programmes. The Portuguese Legislative Elections - 30th January, 2022

Tutorial available on [medium](https://medium.com/@ricardo.campos/keyword-extraction-from-political-party-programmes-dd7fdcd671c9). 

<p align="center">
  <img src="https://github.com/rncampos/PT-LegislativeElections2022/blob/main/MAP_Readme.png">
</p>

In this tutorial, we will be applying [YAKE!](http://yake.inesctec.pt) keyword extraction [Python package](https://github.com/LIAAD/yake) to extract relevant keyphrases from 16 political party programmes candidates to the Portuguese legislative elections held in January 30th, 2022. We refer to nine political parties with parliamentary representation in the last legislature (2019–2021):
- [PS](https://ps.pt/): Partido Socialista
- [PSD](https://www.psd.pt/): Partido Social Democrata
- [BE](https://bloco.org/): Bloco de Esquerda
- [CDU](https://www.cdu.pt/2022/): Coligação Democrática Unitária PCP-PEV
- [CDS-PP](https://cds.pt/): Partido do Centro Democrático e Social
- [PAN](https://pan.com.pt/): Partido Pessoas-Animais-Natureza
- [Chega](http://partidochega.pt)
- [IL](https://iniciativaliberal.pt/): Iniciativa Liberal
- [Livre](https://partidolivre.pt/)

and to seven political parties which did not have a representation in the parliament. We refer to:
- [ADN](http://adn.com.pt/): Alternativa Democrática Nacional
- [Ergue-te](http://www.partidoergue-te.pt/)
- [MAS](http://mas.org.pt/): Movimento Alternativo Socialista
- [MPT](https://mpt.pt/): Partido da Terra
- [Nós Cidadãos](https://noscidadaos.pt/)
- [RIR](http://partido-rir.pt/): Reagir Incluir Reciclar
- [Volt Portugal](http://voltportugal.pt/)

Four other political parties (PTP; PCTP/MRPP; JPP; Aliança) are running in the elections but did no make their programme available online.

YAKE! is an unsupervised keyword extraction algorithm which rests on text statistical features to extract relevant keyphrases from single documents. Its plug-and-play nature and adaptability to different domains and languages, plus a good compromise between effectiveness and efficience, makes it a good solution for this use-case scenario.

## References
Please cite the following works when using YAKE:

**In-depth journal paper at Information Sciences Journal**

- Campos, R., Mangaravite, V., Pasquali, A., Jatowt, A., Jorge, A., Nunes, C. and Jatowt, A. (2020). YAKE! Keyword Extraction from Single Documents using Multiple Local Features. In Information Sciences Journal. Elsevier, Vol 509, pp 257-289. [pdf](https://doi.org/10.1016/j.ins.2019.09.013)

**ECIR'18 Best Short Paper**

- Campos R., Mangaravite V., Pasquali A., Jorge A.M., Nunes C., and Jatowt A. (2018). A Text Feature Based Automatic Keyword Extraction Method for Single Documents. In: Pasi G., Piwowarski B., Azzopardi L., Hanbury A. (eds). Advances in Information Retrieval. ECIR 2018 (Grenoble, France. March 26 – 29). Lecture Notes in Computer Science, vol 10772, pp. 684 - 691. [pdf](https://link.springer.com/chapter/10.1007/978-3-319-76941-7_63)

- Campos R., Mangaravite V., Pasquali A., Jorge A.M., Nunes C., and Jatowt A. (2018). YAKE! Collection-independent Automatic Keyword Extractor. In: Pasi G., Piwowarski B., Azzopardi L., Hanbury A. (eds). Advances in Information Retrieval. ECIR 2018 (Grenoble, France. March 26 – 29). Lecture Notes in Computer Science, vol 10772, pp. 806 - 810. [pdf](https://link.springer.com/chapter/10.1007/978-3-319-76941-7_80)
