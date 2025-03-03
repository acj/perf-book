## Questions and Exercises {.unlisted .unnumbered}

\markright{Questions and Exercises}

1. What is the difference between the CPU core clock and the reference clock?
2. What is the difference between retired and executed instructions?
3. When you increase the frequency, does IPC go up, down, or stay the same?
4. Take a look at the `DRAM BW Use` formula in Table {@tbl:perf_metrics}. Why do you think there is a constant `64`?
5. Measure the bandwidth and latency of the cache hierarchy and memory on the machine you use for development/benchmarking using Intel MLC, Stream, or other tools.
6. Run the application that you're working with on a daily basis. Collect performance metrics. Does anything surprise you?

**Capacity Planning Exercise**: Imagine you are the owner of four applications we benchmarked in the case study. The management of your company has asked you to build a small computing farm for each of those applications with the primary goal being maximum performance (throughput). The spending budget you were given is tight but enough to buy 1 mid-level server system (Mac Studio, Supermicro/Dell/HPE server rack, etc.) or 1 high-end desktop (with overclocked CPU, liquid cooling, top GPU, fast DRAM) to run each workload, so 4 machines in total. Those could be all four different systems. Also, you can use the money to buy 3-4 low-end systems; the choice is yours. The management wants to keep it under $10,000 per application, but they are flexible (10--20%) if you can justify the expense. Assume that Stockfish remains single-threaded. Look at the performance characteristics for the four applications once again and write down which computer parts (CPU, memory, discrete GPU if needed) you would buy for each of those workloads. Which parameters you will prioritize? Where will you go with the most expensive part? Where you can save money? Try to describe it in as much detail as possible, and search the web for exact components and their prices. Account for all the components of the system: motherboard, disk drive, cooling solution, power delivery unit, rack/case/tower, etc. What additional performance experiments would you run to guide your decision?
