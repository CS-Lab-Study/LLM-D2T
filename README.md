# A Comparative Analysis of Conversational Large Language Models in Knowledge-Based Text Generation
This GitHub repository hosts the code and data resources accompanying the paper titled "A Comparative Analysis of Conversational Large Language Models in Knowledge-Based Text Generation".

## Setup
1. Download the [WebNLG dataset](https://gitlab.com/shimorina/webnlg-dataset/-/tree/master/)
2. Download the WebNLG [Corpus XML Reader](https://gitlab.com/webnlg/corpus-reader)
3. Use the _WebNLG\_Preparation.ipynb_ notebook to translate the xml files of WebNLG to json
4. Setup the [LLaMA](https://github.com/facebookresearch/llama) Large Language Model (LLM)
5. Setup the Vicuna LLM using [FastChat](https://github.com/lm-sys/FastChat)
6. If you want to use OpenAI (e.g., GPT-3.5-Turbo), rename the _.env.dist_ file to _.env_ and add your OpenAI API key there
7. Use the _WebNLG\_DataToText_Prediction.ipynb_ notebook to translate rdf triples into text, using different LLMs and prompts
8. For evaluation, the _WebNLG\_DataToText\_Evaluation.ipynb_ notebook can be used
