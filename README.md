# TOTEM-based-tool
The TOTEM-based tool is a visual code, made in Dynamo that allows to obtain an Excel file based on a Revit model able to be integrated into the online TOTEM tool to get full LCA results.

In this repository the documents related to the TOTEM-based tool are present. This repository obtains both the Dynamo file as well as the seperate scripts, written in Python language, present in the Dynamo file.

The TOTEM-based tool studies the possible integration of the TOTEM tool with the vendor specific BIM software, Revit. The online TOTEM tool allows the import of Excel files, with content according to a certain template, to obtain LCA results of the data included in the file. In the included Dynamo file the elements present in a Revit BIM model are exported to an Excel file that can be directly imported into a TOTEM project.

The TOTEM tool allows the assessment of building elements or buildings over their entire life cycle. It considers module A1-C4, as defined by EN 15978. When entire buildings are assessed with the TOTEM tool, also energy use during the use phase can be accounted for with this tool. However, this tool does not take those influences into account and will only study the influence of the building materials.
