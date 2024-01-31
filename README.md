# Sriradh_1002173929
2. Argue selection sort correctness:
   
Selection sort works by repeatedly finding the minimum unsorted element and moving it to the sorted subset. It maintains a sorted and unsorted subarray that are updated each iteration.

The algorithm is provably correct because:

1.The sorted section remains ordered.

2.It terminates when fully sorted.

3.It correctly identifies the minimum unsorted element to move.

4.It stably preserves order of equal elements.

5.It sorts in-place without extra memory.

The O(n^2) time complexity is higher than better algorithms. However, selection sort adapts well to small n or where simplicity is preferred. Its straightforwardness can offset less efficiency for certain use cases.

In summary, selection sort is a simple, beginner-friendly, in-place sorting technique with quadratic runtimes. It works for smaller datasets where interpretability matters more than performance. The step-by-step iterative logic serves as an elegant introduction to more advanced algorithms.

3. Benchmark the runtime of each algorithm:
   
System information: 

   CPU: AMD RYZEN 3
   
   RAM: 8Gb
   
   OS: Windows 11
   
   Python version: Python 2.7
