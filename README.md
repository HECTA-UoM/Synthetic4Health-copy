# Synthetic4Health
A system to generate annotated, synthetic, de-identified clinical letters while protecting entities and document structure. 

This work presents a system for generating synthetic, de-identified clinical letters that are distinguishable from the originals, while preserving entities and document structures. We employed a hybrid approach, combining rule-based methods and named entity recognition (NER), to safeguard necessary information while exploring different models. We investigated various masking ratios and strategies based on token types (e.g., POS tags, stopwords) to balance diversity and similarity in synthetic letters. Our results demonstrate that this system produces high-quality synthetic clinical letters and is effective in protecting key information using encoder-only models, based on NER, POS tags, and stopword status.



# cite us:
@misc{ren2024synthetic4healthgeneratingannotatedsynthetic,
      title={Synthetic4Health: Generating Annotated Synthetic Clinical Letters}, 
      author={Libo Ren and Samuel Belkadi and Lifeng Han and Warren Del-Pinto and Goran Nenadic},
      year={2024},
      eprint={2409.09501},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={ https://arxiv.org/abs/2409.09501 }, 
}

# new hosting repository: please visit
https://github.com/Libo-Ren/HECTA-UoM-Synthetic4Health
