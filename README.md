# AmbiguityQuantifiersTests
Understanding Quantifier Scope in Negated Sentences:
Humans vs. Large Language Models
Tova Avidan & Nurit Melnik

Introduction 
Large Language Models (LLMs) are advanced machine learning systems specifically trained for Natural Language Processing. As they evolve, their language comprehension improves, making them increasingly prevalent. However, despite their impressive performance in generating coherent responses and completing complex language tasks, do LLMs truly "understand" language like humans do? 
This study focuses on one particular phenomenon: the scope of quantifiers in negated sentences. For example, consider this ambiguous sentence (Kamath 2024):
(1)	Sita doesn't like a classmate of hers. 
This sentence has two interpretations:
1.	Non-isomorphic reading: "There is a specific classmate that Sita does not like."
2.	Isomorphic reading: "There is no classmate that Sita likes."
Recent studies have addressed these questions. Gupta (2023) argues that as LLMs grow, they improve in language comprehension tasks, yet they struggle with language tests that involve negation and quantifiers. His findings suggest that these models fail to consistently interpret a significant percentage of sentences. Conversely, Kamath et al. (2024) claim that advanced models, particularly GPT-4, can select the human-preferred reading with 98% accuracy. 
Building on results from psycholinguistic research on the acquisition of quantifier scope (Lidz & Musolino 2002; Gualmini 2004; Crain, 2009), this study replicates Lidz & Musolino's (2002) experiments and examines how GPT-3.5 and GPT-4.0 interpret ambiguous sentences. It evaluates whether the models recognize different readings, whether they favor one interpretation over the other and if so, whether it aligns with the interpretation preferred by adults or children. 
 
The Study 
Four trials were conducted using Python API requests; for brevity, we present only two here. 
In Trial 1, the models were presented with stories followed by ambiguous statements and were asked to determine their truthfulness. For example, a story about Cookie Monster and four giant pizza slices, where he eats the first slice and barely finishes the second, is followed by:
Cookie Monster didn’t eat two slices of pizza, am I right? 
 
Trial 1
Results indicate that both models struggle with understanding ambiguous sentences. GPT-4.0 performs better, though still below adult level. 

Trial 2
The models were presented with stories followed by ambiguous statements and were asked to identify both interpretations, select the appropriate one and explain their reasoning.
 
The findings are surprising, both in comparison between model versions and across conditions, especially for GPT-3.5, whose results contrast with Trial 1. Moreover, the explanations provided by the models were inconsistent. Interestingly, GPT-3.5's behavior resembled that of young children, as both consistently preferred the isomorphic reading.
Conclusions 
The models' judgments fall significantly short of human adult performance. The models were inconsistent across  identical stories judgment (especially GPT-3.5) and in judgment of different stories with the same type of ambiguity, though the more advanced model demonstrated higher accuracy.
 
Bibliography
Crain, S. (2009). "Sentence scope", In Edith L. Bavin (Ed.), The Cambridge Handbook of Child Language (Cambridge, UK: Cambridge University Press. pp. 301-320
Gualmini, A. (2004). "Some knowledge children don't lack", Linguistics, 42(5), pp. 957-982
Gupta, A. (2023). "Probing Quantifier Comprehension in Large Language Models: Another Example of Inverse Scaling", Proceedings of the 6th BlackboxNLP Workshop: Analyzing and Interpreting Neural Networks for NLP, pp. 56–64
Kamath, G., Schuster, S., Vajjala, S. and Reddy, S.  (2024). "Scope Ambiguities in Large Language Models", McGill University, Transactions of the Association for Computational Linguistics, vol. 12, pp. 738–754
Lidz, J. and Musolino, J. (2002). "Children's command of quantification", Cognition 84, pp. 113-154.


