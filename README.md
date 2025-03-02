# FBjson

## About
FBjson is a JSON/BSON parsing library for the [FreeBASIC](https://www.freebasic.net) language. Also included is
a base64 encoder/decoder library as it is used by portions of the BSON support.

## Examples
Currently the best examples are the tests located in tests/json.bas. In the future there will be examples in the examples directory.

## History
This was originally a module of the FreeBASIC Extended Library but has been extracted to allow maximum usage without the extra features the Extended Library was attempting to support like generics.

## Building on Windows

1. Open a Command Prompt (if using powershell run "cmd" to get the proper support for batch file features used)
2. Define a variable for the FreeBASIC compiler to use: "SET FBC=fbc32" or "SET FBC=fbc64" for 32bit or 64bit support
3. Run winbuild.bat
4. Copy inc/*.bi to your FreeBASIC install's inc dir
5. Copy lib/*.a to your FreeBASIC install's lib dir

## Building on Other Platforms
Use the provided Makefile, it is untested at the moment.