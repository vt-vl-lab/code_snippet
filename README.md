# code_snippet
Some code snippets.

## MISC:
- google_drive.py: Download files from Google Drive using terminal

## TensorBoard
Sometimes when you try to use tensorboard to visualize something, you don't have the write access. You can try
```bash
export TMPDIR=/tmp/$USER; mkdir -p $TMPDIR; tensorboard --logdir $LOGDIR
```
