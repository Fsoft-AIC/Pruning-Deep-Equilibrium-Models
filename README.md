# [SNN workshop - ICML 2022] Pruning at Initialization for Monotone DEQ


## Requirements
Compatible with python 3.5+ and known to work with pytorch 1.4, torchvision 0.5, and numpy 1.18. 

`
pip install -r requirements.txt
`

## Run
`
python run_exps.py --is_pruning --pruner rand --sparsity 0.9 --dataset mnist --model SingleFcNet --sp PR
`


## Reference 
*MonDEQ codebase is from [the paper](https://arxiv.org/abs/2006.08591) by Ezra Winston and [Zico Kolter](http://zicokolter.com).*

*Pruning codebase is from [the paper](https://arxiv.org/abs/2006.05467) by Tanaka*