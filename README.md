# singularity-mega

A [singularity container](https://github.com/sylabs/singularity) definition file to run [Mega](https://www.megasoftware.net). 

Build:

`sudo singularity build mega.sif mega.def`

Run [GUI]:

`singularity run -B /etc/machine-id -B /run/user/$UID/ mega.sif`

