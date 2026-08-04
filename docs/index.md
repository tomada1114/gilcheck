# gilcheck

Zero-config AST linter for code that was only accidentally thread-safe under the GIL

## Installation

=== "pip"

    ```bash
    pip install gilcheck
    ```

=== "uv"

    ```bash
    uv add gilcheck
    ```

## Quick Example

```python
from gilcheck import add

result = add(1, 2)
print(result)  # 3
```

## Next Steps

- [Getting Started](getting-started.md) — setup and first steps
- [API Reference](reference.md) — full API documentation
- [Contributing](contributing.md) — how to contribute
