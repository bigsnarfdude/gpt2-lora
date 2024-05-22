# gpt2-lora

```

python gpt2_lora.py

...    )
      (norm1): LayerNorm()
      (norm2): LayerNorm()
      (drop_resid): Dropout(p=0.0, inplace=False)
    )
  )
  (final_norm): LayerNorm()
  (out_head): LinearWithLoRA(
    (linear): Linear(in_features=768, out_features=2, bias=True)
    (lora): LoRALayer()
  )
)
Training accuracy: 46.25%
Validation accuracy: 45.00%
Test accuracy: 48.75%
Ep 1 (Step 000000): Train loss 2.849, Val loss 2.565
Ep 1 (Step 000050): Train loss 0.515, Val loss 0.465
Ep 1 (Step 000100): Train loss 0.191, Val loss 0.423
Training accuracy: 97.50% | Validation accuracy: 97.50%
Ep 2 (Step 000150): Train loss 0.170, Val loss 0.072
Ep 2 (Step 000200): Train loss 0.013, Val loss 0.091
Ep 2 (Step 000250): Train loss 0.028, Val loss 0.191
Training accuracy: 100.00% | Validation accuracy: 92.50%
Ep 3 (Step 000300): Train loss 0.017, Val loss 0.323
Ep 3 (Step 000350): Train loss 0.008, Val loss 0.181
Training accuracy: 100.00% | Validation accuracy: 97.50%
Ep 4 (Step 000400): Train loss 0.018, Val loss 0.128
Ep 4 (Step 000450): Train loss 0.020, Val loss 0.123
Ep 4 (Step 000500): Train loss 0.141, Val loss 0.019
Training accuracy: 100.00% | Validation accuracy: 100.00%
Ep 5 (Step 000550): Train loss 0.003, Val loss 0.051
Ep 5 (Step 000600): Train loss 0.003, Val loss 0.140
Training accuracy: 100.00% | Validation accuracy: 97.50%
Ep 6 (Step 000650): Train loss 0.011, Val loss 0.065
Ep 6 (Step 000700): Train loss 0.001, Val loss 0.216
Ep 6 (Step 000750): Train loss 0.000, Val loss 0.194
Training accuracy: 100.00% | Validation accuracy: 97.50%
Training completed in 0.47 minutes.
Training accuracy: 99.90%
Validation accuracy: 98.66%
Test accuracy: 97.33%

```
