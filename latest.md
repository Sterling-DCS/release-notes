
[core]

  #### New Features 🎉
* [STERDEV-1614] Filtering data sent over signalr to be just the updated/inserted costitems (#504)
* [STERDEV-1653] Refactor BillOfQuantityCalculationService for parallel processing (#502)
* [STERDEV-1613] Compute structure path on the fly (#499)
* [STERDEV-1283] RMv2 add group by family type (#494)
* [STERDEV-1584] bottom line totals fix structures recalc (#490)
* [STERDEV-1584] RMv2 bottom line totals (#482)
* [STERDEV-1581] Removed conversion to tons for co2 fields (#485)
* [STERDEV-1172] bulk update resources for RMv2 (#474)
* [STERDEV-1370]-Adding lifecycle to copying project (#475)
* [STERDEV-1523] filter toggle zero priced bid items (#467)
* [STERDEV-1515] the filter logic for RMv2 (#454)

#### Bug Fixes 🛠
* [STERDEV-1699] Quote complex resources components endpoint (#541)
* [STERDEV-1738] Added subcontractor portfolio Id (#537)
* [STERDEV-1686] Fixed function definition to work with spaces in structure name (#531)
* [STERDEV-1686] Filtered Sub-contractor structures (#526)
* [STERDEV-1686] Fixed core migration isuses, GetProjectTagsByFamilies for quotes (#523)
* [STERDEV-1685] Set CreateProjectTakeoffsProposal job priority to critical and reports to low (#521)
* [STERDEV-1685] Return all cost items if its a proposal (#519)
* [STERDEV-1687] Fixed CI delete workflow (#518)
* [STERDEV-1673] Resetting costitem quantity if all takeoff items (actuals & placeholders) are deleted (#515)
* [STERDEV-1673] If measurement is default use TakeoffItemQuantity (#510)
* [STERDEV-1621] map CI title to RMv2 endpoints (#507)
* [STERDEV-1613] Move unitData population logic to postgre function (#500)
* [STERDEV-1524] Should_Display_All_Unwrapped_CR_Components_With_Unassigned_Filter (#491)
* [STERDEV-1581] Always override EPD data, no default integration type (#480)
* [STERDEV-1524] unassigned bucket (synthetic Unassigned Node) (#491)
* [STERDEV-1354] Making sure latest model id is available in project entity Takeoffs (#465)
* [STERDEV-1354]  Set ModelId when Updating a TakeoffItem (#460)
* [STERDEV-602]  Synchronised CI library complex resources (#459)

[frontend]

#### New Features 🎉
* [STERDEV-1450] Cost Plan Cost Carbon Both view settings (#1757)

#### Bug Fixes 🛠
* [STERDEV-1557] 2d measurements grid category column not saving data (#1753)
* [STERDEV-1748] Finalisation side grid sizing fixes (#1763)
* [STERDEV-1543] Fix forecasting search box and missing plus icon  (#1758)
* [STERDEV-1733] Fixed revision upload issue (#1754)
* [STERDEV-1543] Toolbar Search component fixes Takeoff tile view Forecasting Programme (#1748)
* [STERDEV-1744] fixes on BP add from library modal (#1747)
* [STERDEV-1745] Fix package library grid columns (#1745)
* [STERDEV-1731] Fixed 3d viewer undocked view (#1742)
* [STERDEV-1736] Fix for BP grid expand/collaps issue (#1741)

[identity]

#### New Features 🎉
* [STERDEV-1664] Corrected EULA flow; Added support user to be part of multiple portfolio (#128)
* [STERDEV-30] Bulk User Import (#119)
* [STERDEV-1546] User transfer between portfolios (#118)

#### Bug Fixes 🛠
* [STERDEV-1738] Added subcontractor portfolioId to fix creation issue (#139)
* [STERDEV-1664] Skipping portfolio selection for the SYSTEM user; rolling back data in case we decide to revert the feature. (#137)
* [STERDEV-1691] Fix broken workflow refs (#133)
* [STERDEV-1548] Change phoneNumber type to google.protobuf.StringValue (#124)


[model-converter]

#### New Features 🎉
* [STERDEV-1611] Upgrade Dockerfile to use TechSoft 3D version 2026.1.0 for Revit 2026 support

[takeoff]

#### Bug Fixes 🛠
* [STERDEV-1557] 2D Measurements Grid Category Column not saving data (#210)
