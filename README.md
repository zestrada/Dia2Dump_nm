# Dia2Dump_nm
Fork of Dia2Dump with an added '-nm' switch to dump functions and addresses from .pdb files in an nm style format

Originally created to provide a System.map style for windows kernels using the PDB files obtained from microsoft

Example Usage: 
```
 C:\>Dia2Dump.exe -nm C:\Symbols\...\ntkrnlmp.pdb > System.map
 ... 
 003B00C0 T _TriagepGetPageSize@4
 003B0140 T _TriagepVerifyDump@4
 003B0200 T _TriageGetDriverCount@8
 003B0240 T _TriageGetBugcheckData@24
```

Note that this (currently) only outputs addresses for functions

Not sure what license this should be under since it's a forked sample...
