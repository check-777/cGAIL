# cGAIL
This repository contains code and data for the paper of conditional generative adversarial imitation learning (cGAIL) accepted by ICDM2019.

## Dataset
The data are stored under the directory 

## Runing
```
python main.py --use-gae --log-interval 1 --num-steps 120 --num-processes 8 --lr 3e-4 --entropy-coef 0 --value-loss-coef 0.5 --ppo-epoch 10 --num-mini-batch 32 --gamma 0.99 --gae-lambda 0.95 --use-linear-lr-decay --cgail --gail-batch-size 40 --save-dir ./trained_models/cgail
```