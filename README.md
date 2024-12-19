This repository demonstrates a common ActionScript error: attempting to access an array element beyond its bounds.  The `bug.as` file contains the erroneous code, while `bugSolution.as` provides the corrected version.  The error occurs because ActionScript arrays are zero-indexed; the last element's index is length - 1, not length.