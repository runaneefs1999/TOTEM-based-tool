# TOTEM-based-tool
The TOTEM-based tool is a visual code, made in Dynamo that allows to obtain an Excel file based on a Revit model able to be integrated into the online TOTEM tool to get full LCA results.

In this repository the Dynamo script used for the TOTEM-based tool is present.

The TOTEM-based tool studies the possible integration of the TOTEM tool with the vendor specific BIM software, Revit. The online TOTEM tool allows the import of Excel files, with content according to a certain template, to obtain LCA results of the data included in the file. In the included Dynamo file the elements present in a Revit BIM model are exported to an Excel file that can be directly imported into a TOTEM project. The TOTEM project that can be used to import the Excel file into can be accessed via the following URL: https://www.totem-building.be/pages/user/library.xhtml?l=PROJECT&s=Unf2VV6b5ekI0dG0JlQ9YByYGi8lbCZC

The TOTEM tool allows the assessment of building elements or buildings over their entire life cycle. It considers module A1-C4, as defined by EN 15978. When entire buildings are assessed with the TOTEM tool, also energy use during the use phase can be accounted for with this tool. However, this tool does not take those influences into account and will only study the influence of the building materials.
