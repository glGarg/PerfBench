# PerfBench: Performance Issue Benchmark for Software Engineering Agents

PerfBench is a benchmark dataset for evaluating software engineering agents on C# performance optimization tasks. This repository contains 82 real-world performance issues extracted from GitHub, along with evaluation tools and Docker environments for testing.

## Dataset Overview

The benchmark consists of 81 instances from real GitHub repositories, each containing:
- A specific performance issue described in the problem statement
- The repository state before the performance fix
- Reference solution (the actual commit that fixed the performance issue)

### Example Structure

Each instance id follows the pattern: `{owner}_{repo}__{issue_id}__{dotnet_version}`

E.g.:
- `aarnott_nerdbank.messagepack__155__9.0` - Async serialization optimization
- `angusjohnson_clipper2__35__6.0` - Replacing foreach with for loops
- etc.

## Citation

If you use PerfBench in your research, please cite:

```bibtex
@article{garg2025perfbenchagentsresolverealworld,
      title={PerfBench: Can Agents Resolve Real-World Performance Bugs?}, 
      author={Spandan Garg and Roshanak Zilouchian Moghaddam and Neel Sundaresan},
      year={2025},
      primaryClass={cs.SE},
      url={https://arxiv.org/abs/2509.24091}, 
}
```
