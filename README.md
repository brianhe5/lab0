# A Kernel Seedling
Create a /proc/cout file that shows the current number of running processes running

## Building
```shell
Use "make" to build the module as well as "make clean" to remove the previous build information if needed
```

## Running
```shell
Use the cat /proc/count command to run the program
```
TODO: results?

## Cleaning Up
```shell
Use sudo rmmod proc_count to clean up the built binary
```

## Testing
```python
python -m unittest
```
TODO: results?

Report which kernel release version you tested your module on
(hint: use `uname`, check for options with `man uname`).
It should match release numbers as seen on https://www.kernel.org/.

```shell
uname -r -s -v
```
TODO: kernel ver?