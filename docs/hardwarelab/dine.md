# Accessing DINE

DINE is accessible through Cosma.

To request a Bluefield-2 DPU node, use the `bluefield1` partition with the appropriate account, for example:

```sh
#!/bin/bash -l

#SBATCH -p bluefield1
#SBATCH -A durham
#SBATCH -t 00:00:10

echo Hello from $(hostname) # Hello from b117.pri.cosma.local
```

The Bluefield nodes are powered down when not in use, so when you submit your job you may see the status as `CF` (configuring) while your allocated nodes are booting.

To see the status of the Bluefield-2 nodes, run `sinfo -p bluefield1`.
