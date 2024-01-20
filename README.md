# A Kernel Seedling
Create a /proc/cout file that shows the current number of running processes running

## Building
```shell
Use "make" to build the module as well as "make clean" to remove the previous build information if needed.
Use "sudo insmod proc_count.ko" to insert the module into the kernel
```

## Running
```shell
Use the "cat /proc/count" command to run the program
```
Result: 141

## Cleaning Up
```shell
Use "sudo rmmod proc_count" to clean up the built binary and remove the module from the kernel
```

## Testing
```python
python -m unittest
```
Ran 3 tests in 12.883s OK

Report which kernel release version you tested your module on
(hint: use `uname`, check for options with `man uname`).
It should match release numbers as seen on https://www.kernel.org/.

```shell
uname -r -s -v
```
Kernel Ver: 5.14.8