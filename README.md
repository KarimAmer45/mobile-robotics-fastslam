# FastSLAM

FastSLAM for range-bearing landmark observations. Each particle tracks a robot pose, a trajectory, an importance weight, and an independent landmark EKF map. The implementation includes prediction, landmark initialization, EKF correction, likelihood weighting, low-variance resampling, and selective resampling.

## Run

```bash
python ex7.py
```

Runtime parameters are stored in `params.txt`.
