# rv-models

Static embedding models for [rv](https://github.com/altrao/rv)'s opt-in document search. rv downloads them itself and checks each file's SHA-256; nothing here needs installing by hand. The files are in the [releases](https://github.com/altrao/rv-models/releases).

| Model | Languages |
|---|---|
| `rv-en-fr` | English + French |
| `rv-en-de` | English + German |

## Licences and attribution
- Distilled from [sentence-transformers/distiluse-base-multilingual-cased-v2](https://huggingface.co/sentence-transformers/distiluse-base-multilingual-cased-v2) (Apache-2.0) with [Model2Vec](https://github.com/MinishLab/model2vec) (MIT). The models are distributed under the Apache License 2.0.
- Vocabulary from the Leipzig Corpora Collection, news 2023 (CC BY 4.0): D. Goldhahn, T. Eckart, U. Quasthoff, *Building Large Monolingual Dictionaries at the Leipzig Corpora Collection: From 100 to 200 Languages*, LREC 2012.
