# CMPS 2200 Reciation 5
## Answers

**Name:**_________________________


Place all written answers from `recitation-05.md` here for easier grading.







- **1b.**
the upper bound for quick sort(both fix p and random p) is O(nlogn), and the upper bound for selection sort is O(n^2)
for different size:
|   n |   qsort-fixed-pivot |   qsort-random-pivot |   tim_sort |
|-----|---------------------|----------------------|------------|
|  10 |               0.036 |                0.140 |      0.447 |
|  20 |               0.405 |                0.345 |      0.432 |
|  50 |               0.659 |                0.669 |      1.067 |
|  80 |               0.688 |                1.577 |      3.385 |
| 100 |               0.662 |                1.455 |      1.370 |
| 130 |               0.674 |                1.945 |      3.170 |
| 170 |               2.699 |                7.200 |      2.700 |
| 200 |              55.338 |                6.133 |      9.129 |
| 250 |               2.327 |                5.946 |      5.058 |
| 300 |               2.805 |               62.391 |     14.860 |
from the result we can find the run time for selection sort are much slower than quick sort.



- **1c.**
for time sort
|      n |   qsort-fixed-pivot |   qsort-random-pivot |   tim_sort |
|--------|---------------------|----------------------|------------|
|    100 |               0.875 |                2.869 |      0.027 |
|    200 |               1.890 |               50.077 |      0.032 |
|    500 |               2.904 |               10.740 |      0.057 |
|   1000 |               7.698 |               24.602 |      0.160 |
|   2000 |              16.966 |              110.607 |      0.264 |
|   5000 |              87.221 |              418.832 |      0.947 |
|  10000 |             261.176 |              893.056 |      1.763 |
|  20000 |             414.238 |             1870.851 |      3.982 |
|  50000 |            1477.149 |             4187.367 |     14.105 |
| 100000 |            2961.484 |             9761.318 |     44.861 
the graph shows that thr run time for tim-sort is much faster than both two quick sort