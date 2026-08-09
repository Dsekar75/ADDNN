## 📊 Reproducibility Results (20 Devices, 20 Rounds)

We reproduced the full benchmark using PyTorch. Metrics were logged automatically to CSV and are available in the [`results/`](results/) folder.

| Method  | Round | Loss   | Accuracy | Comm Cost | Time (s) |
|---------|-------|--------|----------|-----------|----------|
| FedAvg  | 5     | 0.0319 | 98.91%   | 10330     | 894.33   |
| FedAvg  | 20    | 0.0439 | 98.35%   | 10330     | 766.69   |
| FedProx | 5     | 0.1055 | 98.35%   | 10330     | 854.97   |
| FedProx | 20    | 0.0742 | 98.53%   | 10330     | 856.14   |
| ADDNN   | 5     | 0.0343 | 98.74%   | 10330     | 764.32   |
| ADDNN   | 20    | ~0.043 | ~98.7%   | 10330     | ~765     |

➡️ Full CSV logs: [metrics_full.csv](results/metrics_full.csv)
