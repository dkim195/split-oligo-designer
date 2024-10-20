## Building Singularity image

```
sudo singularity build split-oligo-designer.sif split-oligo-designer.def
```

## Launching Singularity container

```
singularity run --bind `pwd`:/workdir split-oligo-designer.sif
```

This command will launch Jupyter Lab on localhost:8888.
Open your browser, and copy and paste the URL printed by the above command.
