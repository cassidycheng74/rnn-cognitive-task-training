# rnn-cognitive-task-training
PyTorch implementation of a continuous-time RNN trained on 15 cognitive tasks 
from Driscoll et al. 2024

## Status
- 10/15 tasks converged (<0.05 MSE): DelayPro, DelayAnti, MemoryPro, MemoryAnti, 
  ReactPro, ReactAnti, CtxDMPro, CtxDMAnti, MemoryPro
- DM amplitude comparison tasks still training
- Curriculum training approach implemented
- PCA hidden state analysis and ring attractor visualization included
- Task variance analysis; only top 20% of units (50/256) contributed to task-specific learning (heatmap)
- Confirm Yang's compositional representation finding on Pro/Anti pairs showing same units with flipped signs

## To run
Open `multitask_rnn.ipynb` in Google Colab (Runtime → T4 GPU recommended).
