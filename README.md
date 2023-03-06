# README

This is for out newly developed water model OPC3-B. The parameter files in the current directory should be moved to your Amber software installation path.

To be more precisely, the file `leaprc.water.opc3b` should be placed in the path of `$PATH_TO_AMBERHOME/dat/leap/cmd`, and the `frcmod.opc3b` should be placed in `$PATH_TO_AMBERHOME/dat/leap/parm`

Then you can use `source leaprc.water.opc3b` to load OPC3-B in your `tleap` commands.

And use the command of `OPC3BOX` to load the OPC3-B water box.
