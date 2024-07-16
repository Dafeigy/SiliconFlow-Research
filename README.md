## What is this

This is a repo that using [SilliconFlow](https://siliconflow.cn/zh-cn/pricing#siliconcloud) free LLM api to do some ~~(maybe not but I hope it)~~ interesting research. Here are some demo:

- [x] RAG, using [BAAI/bge-large-zh-v1.5](https://docs.siliconflow.cn/reference/createembedding-1) Embedding model, which supports `512 tokens` and `32 batch_size`, for short articles RAG. See `embedding_vector_search.ipynb` for details.

- [x] Markdown translation, using free `Qwen/Qwen2-7B-Instruct` to convert `.md` from `source lang` to `target_lang`. See `translate_markdown.ipynb` for details. **NOTE: Not perfect for long text yet though**.

- [ ] Echarts Helper. I hope a demo can be made using QWen2, and deploy it on free Github Pages and Gitee Pages for zh-CN users. Prototype can be found in my previous [repo](https://github.com/ChartsGPT/ChartsGPT.github.io) and [here](https://github.com/Dafeigy/ChartsGPT). Maybe coming soon in my spare time.

## How to use

1. Register an account in [SilliconFlow](https://siliconflow.cn). 

2. Make a new file named `config.py` in this repo, and copy all content from `config_template.py` to this file.

3. Edit `OPENAI_KEY` value to your SilliconFlow API.

4. Enjoy it!