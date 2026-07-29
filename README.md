# Threads Proof of Concept

This repository demonstrates Java concurrency concepts with simple examples.

## Project Structure

- `Counter.java` - A shared counter example used to illustrate thread-safe and non-thread-safe behavior.
- `ExecuterServiceDemo.java` - Demonstrates using `ExecutorService` to run tasks concurrently.
- `ScheduledExecutorServiceDemo.java` - Demonstrates scheduling tasks with `ScheduledExecutorService`.
- `RaceCondition.java` - Shows a race condition example and how it can occur with shared mutable state.
- `Main.java` - Contains the main entry point for running selected demos.

## How to Run

1. Open the project in your Java IDE or use a terminal.
2. Compile the sources:

   ```bash
   javac src/*.java
   ```

3. Run the main class:

   ```bash
   java -cp src Main
   ```

## Notes

- Use this repository to explore thread behavior, race conditions, and executor services.
- Each demo is designed for educational purposes and can be extended with more concurrency patterns.
