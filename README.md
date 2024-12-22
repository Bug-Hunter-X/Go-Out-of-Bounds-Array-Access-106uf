# Go Out-of-Bounds Array Access Bug

This repository demonstrates a common error in Go: accessing an array element outside its valid index range.  The `bug.go` file contains the buggy code, while `bugSolution.go` provides the corrected version.

**Bug Description:**
The original code attempts to access an array element beyond the defined bounds, leading to a runtime panic.

**Solution:**
The solution corrects the loop condition to prevent accessing the out-of-bounds index.  Always ensure your loop counters and array indices remain within the valid range to avoid this error.
