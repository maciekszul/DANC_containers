# Recipes for various DANC lab containers

### DANCmriproc MRI processing container recipe currently includes:
- ANTs 2.3.1
- Freesurfer-6.0.0-min
- FSL 6.0.3
- dcm2niix 1.0.20201102
- Python 3.6
- Nipype

### Dependencies:
- Singularity
- Docker

### Build
`singularity build DANCmriproc.simg DANCmriproc`

### Issues
- build requires sudo access
- building directly on cluster fails because of permissions
- building container with Freesurfer requires a path to a local license file
