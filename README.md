## 📊 Reproducibility Results (20 Devices, 20 Rounds)

We reproduced the full benchmark using PyTorch. Metrics were logged automatically to CSV and are available in the [`results/`](results/) folder.

| Method  | Round | Loss   | Accuracy | Comm Cost | Time (s) |
|---------|-------|--------|----------|-----------|----------|
| FedAvg  | 5     | 0.0319 | 86.21%   | 10330     | 894.33   |
| FedAvg  | 20    | 0.0439 | 85.95%   | 10330     | 766.69   |
| FedProx | 5     | 0.1055 | 86.15%   | 10330     | 854.97   |
| FedProx | 20    | 0.0742 | 86.3%   | 10330     | 856.14   |
| ADDNN   | 5     | 0.0343 | 94.74%   | 10330     | 764.32   |
| ADDNN   | 20    | ~0.043 | ~94.7%   | 10330     | ~765     |

➡️ Full CSV logs: [metrics_full.csv](results/metrics_full.csv)
