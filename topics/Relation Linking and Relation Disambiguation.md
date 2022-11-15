## Linking and Disambiguation of Relational Phrases

__Relation Linking__
1. Matching natural language relations to knowledge graph properties for question answering (ReMatch, SEMANTICS 2017)
2. Capturing knowledge in semantically-typed relational patterns to enhance relation linking (SIBKB, K-CAP 2017)

__Joint Entity and Relation Linking__
1. Old is Gold: Linguistic Driven Approach for Entity and Relation Linking of Short Text (FALCON, NAACL-HLT 2019)[[Paper](https://www.aclweb.org/anthology/N19-1243.pdf)][[Code](https://github.com/AhmadSakor/falcon)][[Demo](https://labs.tib.eu/falcon/)][[Notes](https://github.com/BrambleXu/knowledge-graph-learning/issues/211)] (DBpedia)
2. Falcon 2.0: An Entity and Relation Linking Tool over Wikidata (Falcon 2.0, CIKM 2020) [[Paper](https://arxiv.org/pdf/1912.11270.pdf)][[Code and Datasets](https://github.com/SDM-TIB/falcon2.0)] (Wikidata)
3. EARL: Joint Entity and Relation Linking for Question Answering (EARL, ISWC 2018) [[Paper](https://arxiv.org/abs/1801.03825)][[Code](https://github.com/AskNowQA/EARL)] (DBpedia)
4. KBPearl: A Knowledge Base Population System Supported by Joint Entity and Relation Linking (VLDB 2020) 🌟 [[Paper](http://www.vldb.org/pvldb/vol13/p1035-lin.pdf)]
5. Joint Entity Linking and Relation Extraction with Neural Networks for Knowledge Base Population (IJCNN 2020) [[Paper](https://ieeexplore.ieee.org/abstract/document/9207021)]
> * Relations are pre-defined based on the target knowledge base.
> * Neural networks are applied to automatically encode sentence semantics, which is a powerful way to model large-scale noisy text.
6. J-REED: Joint Relation Extraction and Entity Disambiguation (CIKM 2017 short paper) [[Paper](https://dl.acm.org/doi/pdf/10.1145/3132847.3133090)]
> * J-REED is based on probabilistic graphical models that captures the interdependencies between entities and relations.
> * J-REED consides which lexical types of entities are compatible with the type signature of which relation (but the experiments are only conducted on the PERSON-type entities).
7. Better Call the Plumber: Orchestrating Dynamic Information Extraction Pipelines (ICWE 2021) [[Paper](https://arxiv.org/pdf/2102.10966.pdf)]
8. TENET: Joint Entity and Relation Linking with Coherence Relaxation (SIGMOD 2021) 🌟
