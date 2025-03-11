## Setup tau-bench
https://github.com/sierra-research/tau-bench
```
mkdir tau-bench
cd tau-bench
git clone https://github.com/sierra-research/tau-bench
pip install -e .
```

## Download agent-leaderboard dataset from Huggingface 
https://huggingface.co/datasets/galileo-ai/agent-leaderboard/tree/main
```
mkdir data/datasets
cd data/datasets
huggingface-cli download galileo-ai/agent-leaderboard --repo-type dataset --local-dir ./
```

## Run Jupyter notebook
jupyter notebook --no-browser --port=8888

