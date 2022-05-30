Name: William Sayre
Project Type: Brute Force Password Cracker Using Work-Stealing Thread Scheduler
Known Issues: None


How to run (MAKE SURE YOU ARE SITTING AT TOP OF proj3 DIR):

Benchmark tests
=> python3 benchmark/benchmark.py
    - Small flag runs tests using only small dataset, omitting this flag runs full benchmark tests

Run Manually

"Usage: go run driver.go testSize outputPath searchStyle (numThreads)\n" +
	" testSize =  small, medium, or large \n" +
	" outputPath =  Relative write path from data/out/ \n" +
	" searchStyle =  p (Production: randomly shuffle search space to avoid pathologically bad inputs) | b (Benchmark: Standardize search space to reduce randomness for benchmarking)\n" +
	" numThreads =  if empty, run sequentially. Otherwise this is # of threads"


Works Cited:
Marked with inline comments wherever applicable

Performance Analysis:
Please see attached Performance Analysis dir (included plain text version without graphs and PDf version with graphs. Wanted to be extra safe since I had issue with PDF getting corrupted on earlier project)
