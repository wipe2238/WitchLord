WitchLord
=========

Utility for checking issues with AngelScript.  
Similiar to ASCompiler, but aiming to be "clean" environment, without preprocessor or any FOnline-related stuff.

Features:
- loading multiple modules from source and/or bytecode
- if module is loaded from source, its bytecode can be saved for further tests
- executing specific functions after compilation

Notes:
- For program callstack, full program database (WitchLord.pdb) should be in same directory as application.
