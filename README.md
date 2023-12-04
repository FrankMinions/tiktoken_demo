# tiktoken_demo
Based on tiktoken which is a fast BPE tokenizer, I gave an example of encoding and decoding on cl100k_base. 

Moreover, you can use examples such as `train_my_tiktoken.ipynb` to train your own tokenizer based on tiktoken.

In addition, I referred to the code examples provided by the community and compiled a script that can convert the tokenizer in tiktoken into a general format. Based on this, you can use the tokenizer directly through the corresponding method of transformers without installing tiktoken.

But I would like to know how to use sentencepiece to expand the vocabulary and then merge it with the tokenizer.

You need to install the following libraries first:
```bash
pip install tiktoken
pip install transformers
```
