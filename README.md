cannotator
==========

Developed artifacts and system components for CANnotator, a semi-automatic tool that automatically extracts signals from DBC files and computes candidate links to the ontology.

Materials for ESWC2021 submission
"Pay-as-you-go Population of an Automotive Signal Knowledge Graph"
Yulia Svetashova, Lars Heling, Stefan Schmid, and Maribel Acosta

### Abstract
Nowadays, cars are equipped with hundreds of sensors that support a variety of features ranging from basic functionalities to advanced driver assistance systems. The communication protocol of automotive signals is defined in DBC files, yet, these descriptions are typically ambiguous and vary across manufacturers. In this work, we address the problem of extracting the semantic data from DBC files, which is then managed in an Automotive Signal Knowledge Graph (ASKG). We developed a semi-automatic tool that automatically extracts signals from DBC files and computes candidate links to the ontology. These candidates can then be revised by experts who can also extend the ontology to accommodate new signal types in a pay-as-you-go manner. The knowledge provided by the experts is stored in the ASKG and exploited by the tool thereafter. We conducted an evaluation of the tool based on a targeted experiment with automotive experts and report on the first lessons learned from the usage of the tool in the context of the Bosch automotive data lake. The results show that our solution can correctly populate the ASKG and that the expert effort is reduced over time.

### Semantic artifacts
- OTTR templates
- TUI ontology
- Extended VSSo

### Experiment with users
- DBC files from the snapshot of the project opendbc: https://github.com/commaai/opendbc from Jul 27, 2020 [commit: 02be482f0f38fe1f992c5dd3d3c4a9e5f3db2bab]
- Signal list
- User performance data