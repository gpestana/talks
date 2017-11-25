# Golang Pipelines

We're discussing about what are pipelines in go, different patterns of piping
data between goroutines and how to get confused and deadlocked in the process.

### Content

- 1. What are goroutine pipelines
- 2. Examples when go pipelines make sense ...
- 3) ... and when they don't make sense at all
- 4) Different piping patterns for different use cases
- 5) You Got Deadlock'ed!
- 6) Complexity, debugging and profiling
- 7) From code to infra: the different levels of abstraction and piping

### Audience

Basic knowledge of Go recommended but not required.

### Meetups and conferences presented

*talk not ready yet*

## Notes

A Go pipeline is a concurrency pattern which can be used to optimize CPU and
i/o when streaming data between go routines.



© MIT by goncalo pestana
