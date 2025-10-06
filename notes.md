# Project Change Log

## Added Functions
- `plot_top_tokens` - plots the top 10 tokens and its probabilities as a bar chart

## Modified Functions
- `generate` - now returns the idx, and the probabilities

## Notes
- run command line `python sample.py --init_from=gpt2 --start="Hi, I am" --max_new_tokens=1 --num_samples=3 --show_probs=True --device=cpu temperature=1.0` for development
- `python sample.py --init_from=gpt2 --start="Hi, I am " --num_samples=1 --show_probs=True --device=cpu --fixed_response="the best"`
- `python eval.py --init_from=gpt2 --num_samples=1 --device=cpu`
