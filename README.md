# Matryoshka Representation Learning (MRL) and Binary Quantization (BQ)

MRL is a scaling solution to reduce the dimensionality of the embeddings by truncation. The solution introduces embeddings of various sizes keeping the most important features in earlier dimensions compared to later dimensions. This results in maintaining  the most important features while maintaining high quality and cheaper embeddings as used by 
[OpenAI](https://openai.com/blog/new-embedding-models-and-api-updates).

Models
- [paraphrase-multilingual-MiniLM-L12-v2-sts-2d-matryoshka](https://huggingface.co/ciCic/paraphrase-multilingual-MiniLM-L12-v2-sts-2d-matryoshka)


```commandline
pip install torch --index-url https://download.pytorch.org/whl/cu121
```

```commandline
pip install -r requirements.txt
```