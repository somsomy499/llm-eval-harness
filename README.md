# LLM Eval Harness 📏

Comprehensive LLM evaluation with standard benchmarks and custom test suites.

## Supported Benchmarks

- **MMLU**: 57 subjects, 14K questions
- **HumanEval**: 164 coding problems
- **GSM8K**: Grade school math
- **MT-Bench**: Multi-turn conversation quality
- **Custom**: Upload your own eval set

## Quick Start

```python
from llm_eval import EvalHarness

harness = EvalHarness(model="gpt-4o")
results = harness.run(["mmlu", "humaneval", "gsm8k"])
print(results.summary())
```

## License

MIT