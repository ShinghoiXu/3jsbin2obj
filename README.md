# 3jsbin2obj
Convert three.js binary models to wavefront .obj format

The binary file specified on the command line will be read and the processed output will go to standard out. This can be redirected to a file if needed.

Processing data and statistics will be output to standard error.

## Syntax :

`3jsbin <filename.bin>`

## Where :

 * `<filename.bin>` The three.js binary file

## Notes :
 * All values are assumed to be little-endian
 * The .obj file will be output to the same directory
 * A default materials file (tex.mtl) will be added to the .obj
 * Material indexes are not processed and are instead allocated a number with prefix "Texture_"
