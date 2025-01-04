### MPI and Threading Code Examples

This repository contains Python scripts demonstrating the usage of threading and MPI (Message Passing Interface) for various parallel programming tasks. Below is a brief overview of each script's functionality:

---

#### **1. Barrier.py**
- Simulates a race where runners must reach a barrier before continuing.
- Uses `threading.Barrier` to synchronize threads.

---

#### **2. Condition.py**
- Demonstrates producer-consumer synchronization with `threading.Condition`.
- Producers create items, and consumers consume them while maintaining proper thread communication.

---

#### **3. Event.py**
- Showcases producer-consumer synchronization using `threading.Event`.
- Producers signal consumers when data is available.

---

#### **4. IPC.py**
- Implements Inter-Process Communication using `multiprocessing.Queue`.
- A producer adds data to the queue, and a consumer retrieves it.

---

#### **5. MPI.py**
- Demonstrates MPI communication using `mpi4py`.
- Sends and receives data between processes.

---

#### **6. MyThreadClass.py**
- Creates and manages custom threads by subclassing `threading.Thread`.
- Each thread simulates a task with random durations.

---

#### **7. MyThreadClassLock.py**
- Similar to `MyThreadClass.py`, but uses `threading.Lock` for synchronization.
- Ensures safe access to shared resources.

---

#### **8. ProcessCreationAndManagement.py**
- Illustrates process creation and management using the `multiprocessing` module.
- Computes square and cube of a number in parallel.

---

#### **9. Rlock.py**
- Demonstrates the use of `threading.RLock` for reentrant locking.
- Simulates adding and removing items from a shared resource.

---

#### **10. Semaphore.py**
- Implements a producer-consumer model using `threading.Semaphore`.
- Controls access to a limited resource.

---

#### **11. SynchronizationPrimitive.py**
- Uses a semaphore to control access to a critical section.
- Multiple threads attempt to access a shared resource sequentially.

---

#### **12. Thread_definition.py**
- Illustrates basic thread creation and execution using `threading.Thread`.

---

#### **13. Thread_determine.py**
- Demonstrates thread behavior and execution flow by naming and managing threads.

---

#### **14. Thread_Name_and_Process.py**
- Identifies threads and their process IDs.

---

#### **15. threading_with_queue.py**
- Implements thread synchronization using `queue.Queue`.
- Demonstrates producer-consumer workflow with multiple consumers.

---

#### **16. broadcast.py**
- Shares a variable across processes using MPI's `bcast`.

---

#### **17. DeadlockProblems.py**
- Simulates a potential deadlock in MPI communication due to improper ordering of send and receive operations.

---

#### **18. gather.py**
- Gathers data from all processes in an MPI program and collects it at the root process.

---

#### **19. PointToPointCommunication.py**
- Demonstrates MPI point-to-point communication using `send` and `recv`.

---

#### **20. Scatter.py**
- Distributes elements of an array to multiple processes using MPI's `scatter`.
