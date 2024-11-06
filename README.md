# circle02_testers
Current planned tests:
* so_long
* push_swap
* pipex

## push_swap
ps_gen is a **benchmarking** bash script for push_swap. It is not designed to break the program; it is only designed to test its performance.

It is designed to enter inputs as if they were individual arguments. This means that, for example, a sequence of "5 3 4 2 1" will be passed in as:
```./push_swap 5 3 4 2 1```

instead of

```>./push_swap "5 3 4 2 1"```

The latter requiring the program to automatically detect the numbers separately. Note: this is sometimes done by students as zsh does not automatically expand variables like in bash.
