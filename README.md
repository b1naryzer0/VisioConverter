# VisioConverter
A helper tool to bulk convert all .vsd files in a folder to the new format .vsdx

it needs:
- Visio (a working installation must be present on the machine)
- Powershell v5.0+
- vsd files to convert

Your old vsd files won't be deleted, the tool will create and add a new vsdx file 
with the same name in the same folder for every vsd file it finds.
Visio is used in the background for the conversion. If Visio should stop during 
the conversion, just close it and the tool will continue with the next vsd file.
