# Articles

List of articles either foundational or unlocking new SOTA applications. Given the fast pace of the field, articles are ranked by recency (newest at the top).

I'll soon™ add a better frontend to browse that list. 😏

arXiv articles are referenced by reference number. Other sources may vary.  
Author link, if any, points to a git profile (or any primary tech space, like HuggingFace) when existing. Otherwise a personal website, or finally a social profile.


## Machine Learning (ML)

| Source     | Submitted (UTC)     | Title | ELI15 | Abstract | Authors
|------------| ------------------- | ----- | ----- | -------- | -------
| [Answer.AI][24813.A1] | 2024.08.13 | **Small but Mighty: Introducing `answerai-colbert-small`** | Proof of concept for 33M ColBERT SOTA model | Say hello to `answerai-colbert-small-v1`, a tiny ColBERT model that punches well above its weight. | [Benjamin Clavié]
|[2406.11706]|2024.06.17-16\:25\:55| **Prompts as Auto-Optimized Training Hyperparameters: Training Best-in-Class IR Models from Scratch with 10 Gold Labels** | Generate (synthetic) training data with 10 or less human-annotated examples | We develop a method for training small-scale (under 100M parameter) neural information retrieval models with as few as 10 gold relevance labels. The method depends on generating synthetic queries for documents using a language model (LM), and the key step is that we automatically optimize the LM prompt that is used to generate these queries based on training quality. In experiments with the BIRCO benchmark, we find that models trained with our method outperform RankZephyr and are competitive with RankLLama, both of which are 7B parameter models trained on over 100K labels. These findings point to the power of automatic prompt optimization for synthetic dataset generation. | Jasper Xian, Saron Samuel, Faraz Khoubsirat, Ronak Pradeep, Md Arafat Sultan, Radu Florian, Salim Roukos, Avirup Sil, Christopher Potts, [Omar Khattab]
| …














<!-- Articles links -->

[2406.11706]: https://arxiv.org/abs/2406.11706
[24813.A1]: https://www.answer.ai/posts/2024-08-13-small-but-mighty-colbert.html


<!-- Authors -->

[Benjamin Clavié]: https://github.com/bclavie
[Omar Khattab]: https://github.com/okhat
