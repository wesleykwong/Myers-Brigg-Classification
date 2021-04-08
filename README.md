# Myers-Brigg Personality Classification with Twitter Feed

This is the repo for Wesley Kwong's 5th Year MIDS W266 Natural Language Processing with Deep Learning final project.

The aim of this project was to analyze how various monolingual and multilingual BERT models performed on classifying the Myers-Brigg Personality Test (MBTI) classes based on Twitter tweets. The dataset used for this project was the TwiSty dataset. The four languages examined are German (DE), Spanish (ES), Italian (IT), and Dutch (NL).

**Dataset:** https://www.uantwerpen.be/en/research-groups/clips/research/datasets/
 - Verhoeven, B., Daelemans, W., & Plank, B. (2016) TwiSty: a multilingual Twitter Stylometry corpus for gender and personality profiling. In: Proceedings of the 10th International Conference on Language Resources and Evaluation (LREC 2016). Portorož, Slovenia.

**fastText's Aligned Word Vectors:** https://fasttext.cc/docs/en/aligned-vectors.html
 - A. Joulin, P. Bojanowski, T. Mikolov, H. Jegou, E. Grave, Loss in Translation: Learning Bilingual Word Mapping with a Retrieval Criterion
 - P. Bojanowski*, E. Grave*, A. Joulin, T. Mikolov, Enriching Word Vectors with Subword Information

**BERT Models:**
 - Multilingual (bert-base-multilingual-cased): https://huggingface.co/bert-base-multilingual-cased
 - German (bert-base-german-cased): https://huggingface.co/bert-base-german-cased
 - Spanish (dccuchile/bert-base-spanish-wwm-cased): https://huggingface.co/dccuchile/bert-base-spanish-wwm-cased
 - Italian (dbmdz/bert-base-italian-cased): https://huggingface.co/dbmdz/bert-base-italian-cased
 - Dutch (GroNLP/bert-base-dutch-cased): https://huggingface.co/GroNLP/bert-base-dutch-cased
