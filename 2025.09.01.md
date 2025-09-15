
[frontend]

## Bug Fixes 🛠
* [STERDEV-1446] adjust take off component - Create a new molecule sideAssigmentContainer - Delete hardcoded minHeigh on datagrid so component resize properly - Remove unnecessary spread - Fix lint errors (#1494)
  
* [STERDEV-1441] fix page height (#1492)
  
* [STERDEV-1439] adjust page height and refactor resources - fix page height on const items and resouce manager - refactor GridWithBuildupTemplate - update components that use same GridWithBuildupTemplate - add spacing to detailPanel component - fix lint errors - adjust the resouces resize issue in cost Items page (#1489)
  
* [STERDEV-1434] fix scroll issue (#1481)
  
* [STERDEV-1430] unify dropdown button logic with icon button actions - Replace menuItems mapping with direct integration data from `useGetIntegrations('File')` - Each integration now generates a DropdownOption with proper label, action and disabled state - Ensures the "Add Revision" dropdown button behaves the same as the icon button - Fix lint errors (#1478)
  
* [STERDEV-1391] Remove reverse perimter calculation from area (#1480)
  
* [STERDEV-1431] remove unnecessary scroll (#1479)
  
* [STERDEV-1429] Fix "Add Revision" icon button behaviour (#1477)
  
* [STERDEV-1392]  Fixed forecasting cost item quantity splitting issue (#1463)
  
* [STERDEV-1426] fix non scrolling in lifecycle - Add new lincense key - Remove deprecated autoHeight prop to enable scrolling - Fix lint errors (#1474)
  
* [STERDEV-1428] - Adjust isResizableGrid logic - Remove white space - Adjust Height on Complex resouces Data - Remove unnecessary scroll in pages - Fix lint errors (#1473)
  
* [STERDEV-1417] refactor takeoff2D to use flexbox this adjust measurements (#1462)
  
* [STERDEV-1425] object parameters fill the box when 3D floating - Adjust 3d measurements and paramenters - Fix lint errors - Fix Test error - Rename variable to isResizableGrid (#1467)
  
* [STERDEV-1417]Refactor TakeOffService3D/takeoff page - Refactor TakeOffService data component to align with modern best practices, leveraging Flexbox for layout consistency. - Replace the existing parameter button with an icon-based button for improved usability and visual coherence. - Update the Parameters component design to maintain consistency with the application's current design system. - Implement smooth open/close transitions for the parameters panel to enhance user experience. - Adjust spacing across TakeOff page components to reflect the latest design specifications. - Fix responsiveness (#1462)


[frontend-api]

## Bug Fixes 🛠
* [STERDEV-1392] Fixed forecast program creation issue (#124)

