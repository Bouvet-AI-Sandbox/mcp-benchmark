## Install code dependencies
```
pip install -r requirements.txt
```

## Setup tau-bench code
https://github.com/sierra-research/tau-bench
```
git clone https://github.com/sierra-research/tau-bench
cd tau-bench
pip install -e .
```



## Download agent-leaderboard dataset from Huggingface 
https://huggingface.co/datasets/galileo-ai/agent-leaderboard/tree/main
```
mkdir -p data/datasets
cd data/datasets
huggingface-cli download galileo-ai/agent-leaderboard --repo-type dataset --local-dir ./
```

## Setup tau-bench data through Jupyter notebook
Start Jupyter notebook from project root directory
```
jupyter notebook --no-browser --port=8888
```

Run all cells in tau.ipynb. This creates `data/datasets/tau_long_context.parquet`.
