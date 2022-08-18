# singularity-cellpose

Build:

`sudo singularity build --nv cellpose.sif cellpose.def`

Run:

`singularity run --nv -B /etc/machine-id -B /run/user/$UID/ cellpose.sif cellpose`
