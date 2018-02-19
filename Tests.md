Tests for Calculator example

| ID | Description  | Expected | Actual | Pass/Fail |
| --- | --- | --- | --- | --- |
| 1 | Check for no input | Err | | |
| 2 | Check for 1 input | Err | | |
| 3 | Check for 2 inputs: 1, 2 | 3 | | |
| 4 | Check for 3 inputs: 1, 2, 3 | 6 | | |
| 5 | Check for 5 inputs: 1, 2, 3, 4, 5 | 15 | | |
| 6 | Check for 9 inputs: 1, 2, 3, 4, 5, 6, 7, 8, 9 | 45 | | |
| 7 | Check for 10 inputs: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 | 55 | | |
| 8 | Check for 11 inputs: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11 | Err | | |
| 9 | Check input containing a + | Err | | |
| 10 | Check input containing a ; | Err | | |
| 11 | Check input containing XYZ | Err | | |