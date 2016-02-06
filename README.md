# desisim-testdata

This repo includes a lightweight set of input data for testing desisim by
replicating pieces of the $DESI_ROOT directory tree with trimmed down files.
To set $DESI_ROOT and $DESI_BASIS_TEMPLATES:

    source setup-testdata.sh
    
The scripts to trim the basis templates and the cosmics files are in

    bin/trim_basis_templates
    bin/trim_cosmics_templates
    
These assume require access to a non-trimmed version of the files, e.g.
from NERSC:/project/projectdirs/desi/

Stephen Bailey, LBL
2016-02-05
    
