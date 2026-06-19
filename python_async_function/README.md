# Python - Async

This project covers the basics of asynchronous programming in Python using `asyncio`.

## Learning Objectives

- `async` and `await` syntax
- How to execute an async program with `asyncio`
- How to run concurrent coroutines
- How to create `asyncio` tasks
- How to use the `random` module

## Tasks

### 0. The basics of async

**File:** `0-basic_async_syntax.py`

Write an asynchronous coroutine `wait_random` that takes an integer argument `max_delay` (default: `10`) and waits for a random float delay between `0` and `max_delay` seconds before returning it.

```python
async def wait_random(max_delay: int = 10) -> float:
```

## Requirements

- Python 3.9+
- `pycodestyle` 2.5.x compliant
- All files must be executable
- All functions must be type-annotated

## Author

panaki-gillot
