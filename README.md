# LitLLM
LitLLM: A Toolkit for Scientific Literature Review

This repo contains code for the paper [LitLLM: A Toolkit for Scientific Literature Review](https://arxiv.org/abs/2402.01788).

HF Demo available at https://huggingface.co/spaces/shubhamagarwal92/LitLLM


## Setup
Install conda/miniconda then create an environment

```
conda create -n litllm python=3.11 -y
pip install -r requirements.txt
```

Please make sure you have the `OPENAI_API_KEY` set in your environment. We also used Semantic Scholar API to retrieve relevant papers. Follow the instructions on the official [website](https://www.semanticscholar.org/product/api#api-key) to get the API key. Please make sure you have the `S2_API_KEY` set in your environment. 

```
# For linux you can save your key in bashrc or zshrc.
echo "export OPENAI_API_KEY='yourkey'" >> ~/.bashhrc
echo "export S2_API_KEY='yourkey'" >> ~/.bashhrc
```


Run `python app.py`

## Citations

If you found this work useful, please cite:

```bibtex
@article{agarwal2024llms,
  title={LitLLMs, LLMs for Literature Review: Are we there yet?},
  author={Agarwal*, Shubham and Sahu*, Gaurav and Puri*, Abhay and Laradji, Issam H and Dvijotham, Krishnamurthy DJ and Stanley, Jason and Charlin, Laurent and Pal, Christopher},
  journal={arXiv preprint arXiv:2412.15249},
  year={2024}
}

@article{agarwal2024litllm,
  title={Litllm: A toolkit for scientific literature review},
  author={Agarwal*, Shubham and Sahu*, Gaurav and Puri*, Abhay and Laradji, Issam H and Dvijotham, Krishnamurthy DJ and Stanley, Jason and Charlin, Laurent and Pal, Christopher},
  journal={arXiv preprint arXiv:2402.01788},
  year={2024}
}
```
