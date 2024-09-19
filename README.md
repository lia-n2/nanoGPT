# nanoGPT

Based on https://github.com/karpathy/nanoGPT

Modified the model to include both extra register tokens and a small sliding window attention mechanism. Additionally, replaced the exp(.) operation in the Softmax function with abs(.) to reduce computational expense.
