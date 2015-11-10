# a2lupdater
Python Script that updates addresses in A2L-Files out of the DWARF-Info of an elf-file  - Automotive - XCP

example: a2lUpdater.py elf-file.elf input.a2l output.a2l

**the nice thing:**
Supports strucure elements (this is why DWARF-Info is used)

* currently this script needs gnu objdump.exe - therefore objdump.exe ist in git repo
* currently this script only runs under windows (easy to adopt)
* currently only *MEASUREMENT* and *CALIBRATION* labels are supportet
* currently NO SUPPORT for "*SYMBOL_LINK*"
* currently NO SUPPORT for "*LINK_MAP*"

any comments are welcome

Eduard
