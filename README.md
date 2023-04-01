# PyTorch Tutorial for MIL Prerinko 2023

## Usage
PyTorch、logging、argparseのチュートリアル。

Tutoral for PyTorch, logging, and argpase.

## Examples
- 実行前に下記のフォーマットに沿って`.env`を作成
```
CIFAR_ROOT=[PATH_FOR_CIFAR_DATASET]
MODEL_OUTPUT=[PATH_FOR_MODEL_OUTPUT]
```

- 訓練 / Training
```
python ~/prerinko/train.py --gpu 0 --num_epochs 3 --batch_size 16
```

- 評価 / Evaluation (Only after training)
```
python ~/prerinko/train.py --do_eval_only --gpu 0 --num_epochs 3 --batch_size 16
```