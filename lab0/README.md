# A Kernel Seedling
This project is project 0 of CS111, the goal was to write a linux kernel in c to count the total number of processes running.

## Building
```shell
make
sudo insmod proc_count.ko //to activate the kernel
```

## Running
```shell
cat proc/count
returns numbers of processes running by running the code
```
Results: passes all 3 tests

## Cleaning Up
```shell
cmd for cleaning the built binary
make clean //deletes the compiled kernel code
sudo rmmod proc_count //eactivates the kernel

```

## Testing
```python
python -m unittest
//this runs the given test cases using python, the -m flag specifies a kernel module being run 
```


Report which kernel release version you tested your module on


```shell
Ran on 5.14.8-arch1-1 Linux #1 SMP PREEMPT 9/26/21
uname -r -s -v
```
