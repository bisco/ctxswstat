# ctxswstat(A context Switch statistics tool)

## What is this?

ctxswstat can collect statistics data of context switches of Linux.

## Dependencies

- python-bcc


## Usage

You can use this tool with `sudo` or root account.

```
$ sudo ./ctxswstat
```

## Output Sample

You can get the number of context switches in 1sec(cnt),
total time of context switches in 1sec(tot, nsec),
average time of context switch in 1sec(avg, nsec),
and ratio of the time of context switch in 1sec(%).
Maybe you will see compiler warning, but it is no problem.

```
time of context switch [unit:nsec]
count      cpu1       cpu2
2     cnt: 0          4
2     tot: 0          26166
2     avg: 0.00       6541.50
2       %: 0.00       0.00
3     cnt: 0          2
3     tot: 0          111305
3     avg: 0.00       55652.50
3       %: 0.00       0.01
4     cnt: 0          1
4     tot: 0          246338
4     avg: 0.00       246338.00
4       %: 0.00       0.02
5     cnt: 8          1
5     tot: 75519      6131
5     avg: 9439.88    6131.00
5       %: 0.00       0.00
```

## Lisense

Apache 2.0 Lisence
