# Epic_Novels_LLM

Epic literature is one of the most challenging forms of creative writing for generative models
to replicate due to its unique combination of elevated language, extensive narrative structure,
archaic vocabulary, and sustained thematic depth. Unlike short-form narratives or
conversational text, epic writing demands long-term coherence across characters, settings, and
plot progression. It also follows a formal and often poetic tone, dense descriptive passages, and
culturally rich symbolism. General-purpose language models like GPT-2, although capable of
generating coherent sentences, often fail to maintain these characteristics consistently. They
tend to revert to modern, neutral, or instructional language styles, thereby losing the grandeur,
rhythm, and dramatic tone that define epic storytelling. This limitation highlights a significant
gap in current language modeling systems: while they can generate contextually meaningful
text, they are not inherently capable of adopting complex literary styles unless explicitly
adapted. Therefore, there is a need for an efficient approach to specialize LLMs in reproducing
the stylistic and narrative structures of epic literature without requiring computationally
expensive full-model training. 

This project aims to bridge the gap between general-purpose language modeling and genrespecific literary generation by adapting the GPT-2 model to emulate the stylistic conventions
of epic literature using parameter-efficient finetuning. The primary objective is to demonstrate
that techniques such as Low-Rank Adaptation (LoRA) can successfully modify a foundational
model to produce text that aligns more closely with classical epic style while keeping
computational costs manageable. To achieve this, the study focuses on three main goals. First,
to build a high-quality and reproducible dataset consisting of classical epics and literary texts
from public domain sources such as Project Gutenberg, ensuring the data reflects the linguistic
richness and narrative depth required for training. Second, to apply LoRA-based finetuning on
GPT-2 to enable it to learn genre-specific language patterns, including archaic vocabulary,
formal tone, structured narration, and descriptive intensity. Third, to evaluate the performance
of the specialized model through both quantitative measures, such as Perplexity and ROUGE
scores, and qualitative analysis, assessing improvements in stylistic authenticity, narrative
coherence, and vocabulary richness when compared to the base GPT-2 model. Through these
objectives, the project aims to validate that literary style adaptation using LoRA is not only
effective but also computationally practical. 
