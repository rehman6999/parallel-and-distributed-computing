# Python Multiprocessing Examples

This repository demonstrates various multiprocessing techniques in Python, showcasing how to manage processes, inter-process communication, and synchronization effectively.

---

## Files and Descriptions

### 1. **communicatingwithpipe.py**
Demonstrates inter-process communication using `multiprocessing.Pipe`. The script includes two processes:
- **Producer**: Sends a sequence of numbers through a pipe.
- **Consumer**: Receives numbers and sends their squares through another pipe.

### 2. **communicatingwithqueue.py**
Illustrates producer-consumer implementation using `multiprocessing.Queue`.
- **Producer**: Generates random integers and adds them to a queue.
- **Consumer**: Retrieves items from the queue and processes them.

### 3. **KillingProcess.py**
Shows how to terminate a process prematurely.
- Creates a process that executes a function.
- Demonstrates starting, terminating, and joining the process.

### 4. **NamingProcess.py**
Highlights naming processes.
- A process can have a custom or default name.
- Displays process names during execution.

### 5. **runBackgroundprocesses.py**
Explains the difference between daemon and non-daemon processes.
- **Daemon Process**: Runs in the background and terminates when the main program exits.
- **Non-Daemon Process**: Completes execution even if the main program exits.

### 6. **Spawningprocess.py**
Demonstrates spawning multiple processes.
- Creates a list of processes to execute a function with different arguments.
- Starts and joins each process sequentially.

