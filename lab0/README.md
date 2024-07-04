# A Kernel Seedling
This project is project 0 of CS111, the goal was to write a linux kernel in c to count the total number of processes running.

## Building
```shell
make
sudo insmod proc_count.ko to activate the kernel
```

## Running
```shell
cat proc/count
returns numbers of processes running in 
```
Results: passes all 3 tests

## Cleaning Up
```shell
cmd for cleaning the built binary
make clean removes the code made

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
Ran on 5.14.8-arch1-1 Linux #1 SMP PREEMPT 9/26/21
uname -r -s -v
```
