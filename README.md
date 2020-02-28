# code_snippet
Some code snippets.

## MISC:
- google_drive.py: Download files from Google Drive using terminal
- [merge.ipynb](https://colab.research.google.com/drive/1EvRMO-NerFBlZtCTnPNPSDYWlElJg-cA): Merge two images into one (one on the left and the other one on the right, visually similar to `A\B`)

## TensorBoard
Sometimes when you try to use tensorboard to visualize something, you don't have the write access. You can try
```bash
export TMPDIR=/tmp/$USER; mkdir -p $TMPDIR; tensorboard --logdir $LOGDIR
```
