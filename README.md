

# Soumiao Pinyin: Train your own Chinese Input Method with Seq2seq Model


Personalized Chinese Pinyin Input Method with Seq2seq model

Original code in https://github.com/Kyubyong/neural_chinese_transliterator for research purpose. This repository intends to experiment with different training data and interactive user inputs, and possibly develop towards a real data-personalized and model-localized Pinyin Input product.



## Requrements

* Python (>=3.5)

* TensorFlow (>=r1.2)

* xpinyin (for Chinese pinyin annotation)

* distance (for calculating the similarity score between two strings)

* tqdm


## Usage


### * Training:

* STEP 1. Download Leipzig Chinese Corpus or use your own Chinese Corpus. Extract it and copy zho_news_2007-2009_1M-sentences.txt to data/ folder.

* STEP 2. Run `build_corpus.py` to build a Pinyin-Chinese parallel corpus.

* STEP 3. Run `prepro.py` to make vocabulary and training data.

* STEP 4. Adjust hyperparameters in `hyperparams.py` if necessary.

* STEP 5. Run `train.py`. Pretrained files will be provided later.


### * Inference with command line input:

Run `eval.py` for command line input testing.


## Sample Results
