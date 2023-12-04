# tiktoken_demo
Based on tiktoken which is a fast BPE tokenizer, I gave an example of encoding and decoding on cl100k_base. 

In addition, I referred to the code examples provided by the community and compiled a script that can convert the tokenizer in tiktoken into a general format. Based on this, you can use the tokenizer directly through the corresponding method of transformers without installing tiktoken.

You need to install the following libraries first:
```bash
pip install tiktoken
pip install transformers
```

Moreover, you can use examples to train your own tokenizer based on tiktoken:

Step1. Use `train_my_tiktoken.ipynb` to train your own tiktoken tokenizer based on your corpus. 

Step2. Use `generate_extra_vocab_freq.ipynb` to generate a txt file which contains tokens to be merged and their frequencies.

Step3. Finally use `merge_extra_vocab.ipynb` to merge the file generated in step2 with the basic tiktoken file. For the code of this step, referring to [Qwen](https://github.com/QwenLM/Qwen).
