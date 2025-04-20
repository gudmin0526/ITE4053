| Layer     | Input → Output  | Activation | Dropout | Parameters  |
|-----------|------------------|------------|---------|-------------|
| Linear 1  | 16,384 → 512     | ReLU       | 0.3     | 8,388,608   |
| Linear 2  | 512 → 128        | ReLU       | 0.3     | 65,664      |
| Linear 3  | 128 → 1          | Sigmoid    | ✗       | 129         |
| **Total** | —                | —          | —       | **8,454,401** |

weight_decay: 1e-4 (DNN)

# epochs: 2
## LR
[LR][Epoch 1] Train Acc: 0.82, Train Loss: 0.48
[LR][Epoch 1] Val Acc: 0.91, Val Loss: 0.24
[LR][Epoch 2] Train Acc: 0.91, Train Loss: 0.23
[LR][Epoch 2] Val Acc: 0.93, Val Loss: 0.19

## DNN
[DNN][Epoch 1] Train Acc: 0.80, Train Loss: 0.47
[DNN][Epoch 1] Val Acc: 0.92, Val Loss: 0.21
[DNN][Epoch 2] Train Acc: 0.90, Train Loss: 0.25
[DNN][Epoch 2] Val Acc: 0.93, Val Loss: 0.17

## Test
[LR] Test Acc: 0.82
[DNN] Test Acc: 0.80

![alt text](flow.png)
![alt text](bar.png)

# epochs: 10


# epochs: 20
