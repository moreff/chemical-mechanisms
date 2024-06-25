# chemical-mechanisms

Library of chemical kinetics mechanisms in orignial formats with converter to Cantera, OpenFOAM and pyJac ([DLBFoam](https://github.com/Aalto-CFD/DLBFoam)) formats.  
Each mechanism has a `retrieve` script, automatically downloading the original files of the mechanism if posibble.

### Mechanism conversion/compilation:  
For example, if you want to compile gri30 mechanism, use:  
```
cd chemical-mechanisms  
./convert gri30
```
Sometimes, mechanism cannot be automatically converted to Cantera format due to warnings and requres `--permissive` option to proceed.  
If so, please manually edit the `convert` script and add this option to `ck2cti` call

## License and rights
References for mechanisms are listed in the `retrieve` file for a corresponding mechanism. The author of the repository is not responsible for the correctness of its contents. Please check licenses for mechanisms from corresponding references if applicable
