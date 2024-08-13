# Articles

List of articles either foundational (🔴) or unlocking new SOTA applications. Given the fast pace of the field, articles are ranked by recency (newest at the top).

I'll soon™ add a better frontend to browse that list. 😏

arXiv articles are referenced by reference number. Other sources may vary.  
Author link, if any, points to a git profile (or any primary tech space, like HuggingFace) when existing. Otherwise a personal website, or finally a social profile.


## Machine Learning (ML)

| Source     | Submitted (UTC)     | Title | ELI15 | Abstract | Authors
|------------| ------------------- | ----- | ----- | -------- | -------
| [Answer.AI][24813.A1] | 2024.08.13 | **Small but Mighty: Introducing `answerai-colbert-small`** | Proof of concept for 33M ColBERT SOTA model | Say hello to `answerai-colbert-small-v1`, a tiny ColBERT model that punches well above its weight. | [Benjamin Clavié]
|[2406.11706]|2024.06.17-16\:25\:55| **Prompts as Auto-Optimized Training Hyperparameters: Training Best-in-Class IR Models from Scratch with 10 Gold Labels** | Generate (synthetic) training data with 10 or less human-annotated examples | We develop a method for training small-scale (under 100M parameter) neural information retrieval models with as few as 10 gold relevance labels. The method depends on generating synthetic queries for documents using a language model (LM), and the key step is that we automatically optimize the LM prompt that is used to generate these queries based on training quality. In experiments with the BIRCO benchmark, we find that models trained with our method outperform RankZephyr and are competitive with RankLLama, both of which are 7B parameter models trained on over 100K labels. These findings point to the power of automatic prompt optimization for synthetic dataset generation. | Jasper Xian, <br>Saron Samuel, <br>Faraz Khoubsirat, <br>Ronak Pradeep, <br>Md Arafat Sultan, <br>Radu Florian, <br>Salim Roukos, <br>Avirup Sil, <br>Christopher Potts, <br>[Omar Khattab]
| …
| [2004.12832] | 2020.06.04-05\:28\:21 (v2) | 🔴 **ColBERT: Efficient and Effective Passage Search via Contextualized Late Interaction over BERT** | late-interaction Information Retrieval (IR) | Recent progress in Natural Language Understanding (NLU) is driving fast-paced advances in Information Retrieval (IR), largely owed to fine-tuning deep language models (LMs) for document ranking. While remarkably effective, the ranking models based on these LMs increase computational cost by orders of magnitude over prior approaches, particularly as they must feed each query-document pair through a massive neural network to compute a single relevance score. To tackle this, we present ColBERT, a novel ranking model that adapts deep LMs (in particular, BERT) for efficient retrieval. ColBERT introduces a late interaction architecture that independently encodes the query and the document using BERT and then employs a cheap yet powerful interaction step that models their fine-grained similarity. By delaying and yet retaining this fine-granular interaction, ColBERT can leverage the expressiveness of deep LMs while simultaneously gaining the ability to pre-compute document representations offline, considerably speeding up query processing. Beyond reducing the cost of re-ranking the documents retrieved by a traditional model, ColBERT's pruning-friendly interaction mechanism enables leveraging vector-similarity indexes for end-to-end retrieval directly from a large document collection. We extensively evaluate ColBERT using two recent passage search datasets. Results show that ColBERT's effectiveness is competitive with existing BERT-based models (and outperforms every non-BERT baseline), while executing two orders-of-magnitude faster and requiring four orders-of-magnitude fewer FLOPs per query. | [Omar Khattab], <br>[Matei Zaharia]
|













<!-- Articles links -->

[2406.11706]: https://arxiv.org/abs/2406.11706
[24813.A1]: https://www.answer.ai/posts/2024-08-13-small-but-mighty-colbert.html
[2004.12832]: https://arxiv.org/abs/2004.12832


<!-- Authors -->

[Benjamin Clavié]: https://github.com/bclavie
[Omar Khattab]: https://github.com/okhat
[Matei Zaharia]: https://github.com/mateiz
