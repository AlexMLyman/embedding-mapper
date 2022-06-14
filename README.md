# embedding-mapper
Demo code for the Semantic Map of the Bible https://alexlyman.org/bible_semantic_map/


The process is simple, use the MPNet encoder to turn sentences into embeddings, then perform dimensionality reduction on the embeddings with UMAP.
A T-SNE implementation is also included.



Resources:
- [MPNet on HuggingFace](https://huggingface.co/docs/transformers/model_doc/mpnet)
- [MPNet arxiv paper](https://arxiv.org/abs/2004.09297)
- [UMAP repository](https://github.com/lmcinnes/umap)
- [UMAP arxiv paper](https://arxiv.org/abs/1802.03426)


