# rnn-cognitive-task-training
PyTorch implementation of a continuous-time RNN trained on 15 cognitive tasks 
from Driscoll et al. 2024

## Status
- 9/15 tasks converged (<0.05 MSE): DelayPro, DelayAnti, MemoryPro, MemoryAnti, 
  ReactPro, ReactAnti, CtxDMPro, CtxDMAnti, MemoryPro
- DM amplitude comparison tasks still training
- Curriculum training approach implemented
- PCA hidden state analysis and ring attractor visualization included

## To run
Open `multitask_rnn.ipynb` in Google Colab (Runtime → T4 GPU recommended).
