# singularity-cellpose

A [singularity container](https://github.com/sylabs/singularity) build definition file to run [cellpose](https://github.com/MouseLand/cellpose). 

Build:

`sudo singularity build --nv cellpose.sif cellpose.def`

Run [GUI]:

`singularity run --nv -B /etc/machine-id -B /run/user/$UID/ cellpose.sif`

or

`singularity run --nv -B /etc/machine-id -B /run/user/$UID/ cellpose.sif -h`

