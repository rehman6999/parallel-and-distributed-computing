# Threading, Synchronization, and Inter-Process Communication Examples

This repository contains Python code examples demonstrating various threading, synchronization, and inter-process communication (IPC) techniques. These examples highlight the usage of threading, multiprocessing, and synchronization primitives for concurrency and parallelism in Python.

## File Descriptions

### `Barrier.py`
- Implements a race simulation using the `threading.Barrier` synchronization primitive.
- Multiple threads (runners) wait at a barrier until all participants arrive.

### `Condition.py`
- Demonstrates the use of `threading.Condition` for producer-consumer synchronization.
- Producers add items to a shared list, and consumers consume items with proper thread signaling.

### `Event.py`
- Utilizes `threading.Event` for signaling between producer and consumer threads.
- The producer appends items to a list, and the consumer processes them after receiving a signal.

### `IPC.py`
- Showcases inter-process communication (IPC) using `multiprocessing.Queue`.
- A producer process generates data, while a consumer process retrieves and processes it.

### `MPI.py`
- Illustrates message passing with the `mpi4py` library.
- Two processes communicate by sending and receiving data using `MPI`.

### `MyThreadClass.py`
- A custom thread class demonstrating the creation and execution of multiple threads with random sleep durations.

### `MyThreadClassLock.py`
- Similar to `MyThreadClass.py`, but includes a `threading.Lock` to ensure mutual exclusion.

### `ProcessCreationandManagement.py`
- Demonstrates process creation and management using the `multiprocessing` module.
- Two processes compute the square and cube of a number, respectively.

### `Rlock.py`
- Uses `threading.RLock` to synchronize access to a shared resource (a box for adding/removing items).

### `Semaphore.py`
- Demonstrates producer-consumer synchronization using a `threading.Semaphore`.
- A producer generates an item, and a consumer waits until the item is available.

### `Synchronization Primitive.py`
- Illustrates the use of `threading.Semaphore` for controlling access to a resource by multiple threads.

### `Thread_definition.py`
- A basic example of creating and running threads in Python.

### `Thread_determine.py`
- Demonstrates thread naming and basic thread execution flow.

### `Thread_Name_and_Process.py`
- Prints process and thread information for each thread.

### `threading_with_queue.py`
- Implements producer-consumer synchronization using `queue.Queue` for thread-safe data sharing.
