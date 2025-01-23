# llm-reasoning-wth-templates
Improving llm reasoning on GSM and other datasets with structured templates 

## Goal:
To improve the performance of large language models (LLMs) on the GSM8K dataset by designing and integrating a template-based reasoning framework that structures problem-solving into fixed reasoning steps and dynamic content mapping, ensuring accuracy, generalization, and scalability.

## Idea:
1. Analyze the GSM8K dataset to identify recurring reasoning patterns and problem structures.
2. Develop a library of unique templates, each representing a distinct reasoning pattern, with fixed steps and placeholders for dynamic content (e.g., numbers, variables).
3. Preprocess the GSM8K questions to extract question-specific content and map it into template placeholders.
4. Fine-tune the LLM with input-output pairs where GSM8K questions map to their corresponding instantiated templates, enabling structured reasoning.
5. Explore advanced optimization techniques such as Direct Preference Optimization (DPO), Monte Carlo Tree Search (MCTS) or Process rewards to refine template selection and reasoning accuracy during training.
6. Validate the answers against GSM8K ground truth, analyze errors, and refine templates or the LLM’s behavior based on insights.
7. Also evaluate on GSM Symbolic.
8. [Optional] Apply Program of thought technique as well.
