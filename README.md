# Multi-lingual-Sentence-Detection

Developed an advanced language detection model capable of identifying languages within multi-lingual sentences. Multi-lingual sentences contain words or phrases from multiple languages in a single sentence. The goal was to build a model that can accurately detect which languages appear within these complex mixed-language sentences.

Leveraged state-of-the-art techniques such as mBERT (multilingual BERT), N-gram, and Word2Vec to train the model. Specifically, multilingual BERT (mBERT) embeddings were used as input representations for the model. mBERT is a variant of BERT that has been pre-trained on 104 languages, making it well-suited for multi-lingual tasks. N-gram features extracting word sequences and Word2Vec for generating semantic word vectors were also utilized. Through meticulous fine-tuning of mBERT embeddings using diverse language datasets, optimized these contextual embeddings to be more discriminative for the language detection task. The fine-tuning aligned the embedding space to capture nuances between languages effectively.

Achieved highly accurate results with the developed model, reaching a 93% accuracy rate in detecting languages at a sentence level. The rigorous training process involving fine-tuned mBERT and other techniques led to a model capable of identifying mixed-language sentences with a high degree of precision.
