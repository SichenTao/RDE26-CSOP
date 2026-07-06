# RDE26-CSOP

RDE26-CSOP is the Rank 1 entry for Competition 2-CSOPs in the IEEE WCCI 2026 / IEEE CEC 2026 Competition on Numerical Optimization Considering Accuracy and Speed.

## Competition

| Item | Description |
| --- | --- |
| Track | Competition 2-CSOPs |
| Problem class | Constrained single-objective optimization |
| Benchmark | 28 CEC 2017 constrained real-parameter optimization problems |
| Runs | 25 independent runs per problem |
| Budget | 20000 x D function evaluations |
| Official rank | Rank 1 |
| Official source | [P-N-Suganthan/2026-CEC](https://github.com/P-N-Suganthan/2026-CEC) |

## Authors

Sichen Tao, Hanyu Hu, Ruihan Zhao, Qingke Zhang, Yifei Yang, Jian Wang, Masatoshi Kawai, and Hiroyuki Takizawa.

## Contents

| Path | Description |
| --- | --- |
| `benchmark/` | Public benchmark materials |
| `code/rde26-csop/main.py` | Track-specific run entry |
| `code/rde26-csop/RDEx.cpp` | Final algorithm source |
| `code/rde26-csop/cec17_test_COP.cpp` | Benchmark evaluator |
| `code/rde26-csop/inputData/` | Required benchmark input data |

## Requirements

- Python 3
- C++ compiler with C++11 support

## Run

```bash
python3 code/rde26-csop/main.py
```

Generated outputs are written under `code/rde26-csop/outputs/`.

## Reference

K. Qiao, X. Ban, P. Chen, K. V. Price, P. N. Suganthan, J. Liang, C. Yue, and G. Wu, "Performance comparison of CEC 2026 competition entries on numerical optimization considering accuracy and speed," IEEE WCCI/CEC 2026 competition slides.
