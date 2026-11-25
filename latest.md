
[core]

## New Features 🎉

* [STERDEV-2135] Core: Implement DHTMLX client, background jobs and SignalR hub for Gantt streaming (#633)

* [STERDEV-2129] Assemblies grouping (#630)

* [STERDEV-2044] Feature - Assemblies entities, models and endpoints (#622)

* [STERDEV-2116] "Subcontractor" role to have access to all projects in their portfolio (#619)

## Bug Fixes 🛠

* [STERDEV-1244] Populate paths in library imports (#666)

* [STERDEV-2238] Saving CI Libraries; fix tag family name mapping (#653)

* Stop revisions from silently ignoring deleted activities (#634)

* [STERDEV-2109] handle System.NullReferenceException: Object reference… (#615)

[frontend]

## New Features 🎉

* [STERDEV-2226] Added menu option to 'Swap Portfolio' (#2241)

* [STERDEV-2185] Update MUI components to v9 (#2206)

* [STERDEV-2160] Update takeoff-viewer to version 0.0.88 and implement measurement label formatting improvements (#2200)

* [STERDEV-2161] feat(frontend): unit-conversion marker in Rule Manager and feature flag for the Classify button (#2195)

* [STERDEV-2135] Implement high-capacity Gantt streaming and background processing (#2190)

* [STERDEV-1977] feat(take-off): Rule-Driven ToQ and Model Object Classifier workspace (#2185)

* [STERDEV-2129] Assemblies groups (#2181)

* [STERDEV-1976] feat(frontend): Object Grid Classification status/Derived Parameters columns (#2164)

* [STERDEV-2044] Assembly UI changes (#2155)

* [STERDEV-2075] Rule Lifecycle Actions (#2156)

* [STERDEV-2117] Revisioning - Cost & Carbon summary tab - Quantity roll-ups not required (#2150)

## Bug Fixes 🛠

* [STERDEV-2160] Bump @sterling/takeoff-viewer to version 0.0.89 (#2213)

* [STERDEV-2176] Scope node cost-item data to the programme and stop the BOQ erasing assignments (#2211)

* [STERDEV-2044] Assemblies feature flag fix (#2204)

* [STERDEV-2177] Fix collapsed Left Hand nav not working in Safari (#2202)

* [STERDEV-2174] Restore the deletion warning on the streaming revision comparison (#2197)

* [STERDEV-2151] unassign ci from activity (#2196)

* [STERDEV-1950] Lifecycle workbook manual items persistence fix (#2193)

* [STERDEV-2147] Show all portfolio projects to non subcontractor user (#2165)

* [STERDEV-2044] React query in CI library, const cache keys and better ux (#2157)

* [STERDEV-1767] hide and disable editing interface if not editable (#2154)

* [STERDEV-2099] handle missing end dates to fix No Rows display (#2149)

* [STERDEV-2109] handle System.NullReferenceException: Object reference… (#2134)

* [STERDEV-2096] Setting the row before we start editing them (#2144)

* [STERDEV-2103] Cost Plan - Add Resources button not visible until scrolled to right (#2141)
  

[frontend-api]

## New Features 🎉

* [STERDEV-2135] Frontend-API: Implement internal bulk import and increase payload limits (#184)

## Bug Fixes 🛠

* Unassign cost items for activities removed by a revision (#185)

* [STERDEV-2151] Resolve node ids tolerantly and stop move() losing siblings (#186)

* [STERDEV-1767] reject programme updates if not editable (#181)
  

[identity]

## New Features 🎉

* [STERDEV-2226] Roles fallback (#185)

* [STERDEV-2217] Sorted portfolio names asc (#184)

* [STERDEV-2102] Users can be created without password (SSO only); No reset or registration for such users (#169)

## Bug Fixes 🛠

* [STERDEV-2150] Setting explicit role for subcontractors (#175)

* [STERDEV-2116] "subcontractor" role assigned to new subcontractors (#171)
  

[mailing]

## New Features 🎉

* [STERDEV-1690] Email template handling changes (#68)

* [STERDEV-1525] GETendpoints for default email templates (Unblocks FE) (#50)

## Bug Fixes 🛠

* [STERDEV-1690] Fixing issues (#75)

* [STERDEV-1690] fix .net version (#73)

* [STERDEV-1236] Remove unnecessary content from user invitation mail (#69)

* [STERDEV-1530] fic mailing env vars (#53)
  

[proxy]

## New Features 🎉

* [STERDEV-2226]  New 'reauth' endpoint so refresh proxy cached token (#44)

## Bug Fixes 🛠

* [STERDEV-2226] Added '/reauth' endpoint for portfolio swap; build fixes with .NET6 (#48)

* [STERDEV-2226] Proxy revert #1 (#46)

[takeoff]

## New Features 🎉

* [STERDEV-2264] Set file name after .DWG conversion (#306)
