# Perform-the-following-sorting-methods-
14. Perform the following sorting methods 
  np.sort(arr), np.argsort(arr), np.unique(arr)
import numpy as np
a=[1,9,5,2,7,3]
print(np.sort(a))
print(np.argsort(a))
print(np.unique(a))
Output:
[1 2 3 5 7 9]
[0 3 5 2 4 1]
[1 2 3 5 7 9]

import numpy as np
a=[1,9,5,5,2,7,3]
print(np.unique(a))

Output:
[1 2 3 5 7 9]
