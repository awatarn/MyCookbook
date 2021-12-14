# netCDF operation using `nco`
Reference: http://nco.sourceforge.net/nco.html#ncatted-netCDF-Attribute-Editor

## Delete some variables from netCDF file
`ncks -x -v var1,var2,var3 original.nc modify.nc`

## Read some attributes using `ncks`
`ncks -m -M original.nc`

## Delete the global attributes from netCDF file
`ncatted -a ,global,d,, out.nc` 
