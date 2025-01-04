# Python Asynchronous Programming and Concurrency Examples

This repository contains various Python scripts demonstrating asynchronous programming and concurrency techniques using `asyncio`, threading, multiprocessing, and concurrent futures. Each script highlights a specific use case or pattern for managing tasks efficiently.

---

## Contents

1. **`asyncioandFuture.py`**
   - Demonstrates the use of `asyncio.Future` and coroutines to compute:
     - Sum of the first `N` integers.
     - Factorial of a number.
   - The results are handled using callback functions.

   **Usage:**
   ```bash
   python asyncioandFuture.py <num1> <num2>
   ```

2. **`asyncioCoroutine.py`**
   - Simulates a finite state machine (FSM) using `asyncio.coroutine`.
   - Each state transitions to another based on random inputs, showcasing coroutine chaining.

   **Run:**
   ```bash
   python asyncioCoroutine.py
   ```

3. **`asyncioeventloop.py`**
   - Illustrates the `asyncio` event loop with task scheduling.
   - Tasks (`task_A`, `task_B`, `task_C`) are scheduled to run repeatedly until the loop ends.

   **Run:**
   ```bash
   python asyncioeventloop.py
   ```

4. **`asyncioTaskManipulation.py`**
   - Demonstrates task creation and manipulation using `asyncio.Task`.
   - Computes:
     - Factorial.
     - Fibonacci sequence.
     - Binomial coefficient.

   **Run:**
   ```bash
   python asyncioTaskManipulation.py
   ```

5. **`concurrent_futures_pooling.py`**
   - Compares different execution models:
     - Sequential execution.
     - Thread pool execution.
     - Process pool execution.
   - Computes a dummy function (`count`) on a list of numbers.

   **Run:**
   ```bash
   python concurrent_futures_pooling.py
   ```

6. **`Barrier.py` to `Synchronization_Primitive.py`**
   - Demonstrates various threading and synchronization primitives such as `Barrier`, `Lock`, `Semaphore`, and `Condition`.

