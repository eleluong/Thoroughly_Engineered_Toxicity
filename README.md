# Thoroughly_Engineered_Toxicity

Thoroughly Engineered Toxicity dataset is a dataset created by filtering a set of prompts from Chat-Lmsys-1M dataset, each prompt has high potential of exposing the toxicity of Large Language models (LLMs).
Other: ![Huggingface dataset](https://huggingface.co/datasets/convoicon/Thoroughly_Engineered_Toxicity) ![Arxiv](https://arxiv.org/pdf/2405.10659)

# Toxicity Evaluation results on TET

| Model             | Toxicity | S-Toxicity | Id Attack | Insult | Profanity | Threat |
| ----------------- | -------- | ---------- | --------- | ------ | --------- | ------ |
| ChatGPT 3.5       | 24.404   | 10.004     | 8.454     | 16.019 | 22.453    | 7.028  |
| Gemini Pro        | 27.614   | 8.987      | 11.677    | 15.958 | 22.665    | 8.248  |
| Llama2-7B-Chat    | 22.994   | 3.181      | 8.027     | 12.609 | 15.764    | 5.709  |
| Llama2-13B-Chat   | 18.323   | 2.932      | 6.476     | 9.853  | 11.928    | 5.003  |
| Llama2-70B-Chat   | 17.901   | 2.406      | 6.397     | 9.723  | 10.731    | 4.600  |
| Orca2-13B         | 43.329   | 23.301     | 21.728    | 28.103 | 42.033    | 15.726 |
| Mistral-7B-v0.1   | 54.437   | 28.989     | 29.587    | 36.017 | 53.838    | 20.489 |
| Mixtral-8x7B-v0.1 | 44.407   | 23.204     | 17.941    | 36.017 | 25.254    | 13.830 |
| OpenChat 3.5      | 58.515   | 28.526     | 28.317    | 46.063 | 50.502    | 21.351 |
| Zephyr-7B-β       | 53.888   | 30.082     | 32.723    | 38.855 | 49.734    | 22.376 |

# Test your own models

You can easily benchmark your own models on TET dataset by using this ![notebook](https://github.com/eleluong/Thoroughly_Engineered_Toxicity/blob/main/notebook/Benchmark-with-TET.ipynb). Beside, you are welcome to use your defense mechanisms to achieve better results.
