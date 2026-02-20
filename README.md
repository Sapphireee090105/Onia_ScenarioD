# Onia_ScenarioD

Scenario D: The "Clean-Water" Treatment Plant
- Base Class: WaterFilter (Properties: FilterID, UsageCount).
- Sub-Classes: CarbonFilter and ChemicalFilter.
- Logic: An abstract method ProcessWater(). The ChemicalFilter must track chemical levels, while the Carbon tracks physical debris.
- Exception: Handle a DivideByZeroException when calculating the "Filtration Efficiency" if no water has passed through yet.
 
