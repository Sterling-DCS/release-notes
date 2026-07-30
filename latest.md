
[core]

* [STERDEV-1244] CI Library Add CI, Assign Structures and removed unused caching references (#582)

* [STERDEV-1803] on demand totals calculations (#561)

* [STERDEV-1244] Populating new tables with imports and keep them in sync (#571)

* [STERDEV-1244] Renamed tables to fix migrations; filter out inactive rows; deleted commented out columns (#570)

* [STERDEV-1244] New tables, caching and CI library GET endpoints (#567)

* [STERDEV-1815] MCP- Server integration (#568)



## Bug Fixes 🛠

* [STERDEV-1786]  Ignore invalid model ids & no rollback (#580)

* [STERDEV-1879]  Fixed takeoff references (#576)

[frontend]

* [STERDEV-1947] Align 2D formula suggestions with headers (#1972)

* [STERDEV-1591] Update dependencies and fix arc detection logic in TakeOffService (#1923)

* [STERDEV-1244] Add CI item fixes and action column title (#1919)

* [STERDEV-1244] Add CI, assign structure to CI library (#1904)

* [STERDEV-1244] Add CI item fixes and action column title (#1919)

* [STERDEV-1244] Add CI, assign structure to CI library (#1904)

* [STERDEV-1824] Add structure dropdown and hierarchy shading to revision variance grids (#1872)

* [STERDEV-1868] feat: Add relational highlighting and undock/redock to TO 3D Revisions (#1883)

* [STERDEV-1789] uploading a new programme now supports CSV (as a performance workaround) (#1888)

* [STERDEV-1760] WBS code support (#1894)

* [STERDEV-1763] basic keynav enabled, no shortcuts (#1884)

* [STERDEV-1803] on demand totals calculations (#1814)

* [STERDEV-1789] Unassign CI from deleted Tasks on revision upload (#1857)

* [STERDEV-1854] Update @sterling/takeoff-viewer to version 0.0.76 (#1861)



## Bug Fixes 🛠

* [STERDEV-1942] Set finalisation SliderRange and no cache (#1979)

* [STERDEV-1876] Persist undocked viewer window size (#1958)

* [STERDEV-1755] fix bare resolve of "react-dom/client" (#1968)

* [STERDEV-1937] Add 'public/**' to ESLint ignore patterns (#1962)

* [STERDEV-1893] 3DTO - Model tree - Undocked viewer - Panel loses formatting on first time opening (#1959)

* [STERDEV-1932] Update @sterling/takeoff-viewer to version 0.0.82 in package.json and pnpm-lock.yaml (#1950)

* [STERDEV-1891]: restore range cell-select & paste-fill on measurements/objects grids (#1937)

* [STERDEV-1922] 2D Take-off Revisioning 'Adjust' - sync selection between viewer and Measurements grid (#1930)

* [STERDEV-1345] fix(frontend): hide null values on grouped parent rows in take-off documents grid (#1926)

* [STERDEV-1307] fix(takeoff): preserve Sterling measurement names in TOI grid (#1921)

* [STERDEV-1623] Implement TOI converter, fix scrollbar clipping, and add unit tests (#1902)

* [STERDEV-1726] 2D Take-off Revisioning 'Adjust' - Derived Perimeter not being calculated (#1915)

* [STERDEV-1911] TO - Moving TOI within the TO Structure (#1906)

* [STERDEV-1360] update @sterling/takeoff-viewer to version 0.0.78 (#1899)

* [STERDEV-1911] TO - Moving TOI within the TO Structure (#1906)

* [STERDEV-1360] update @sterling/takeoff-viewer to version 0.0.78 (#1899)

* [STERDEV-1854][v2] - Update @sterling/takeoff-viewer dependency to version 0.0.77 (#1890)

* [STERDEV-1813][v2] Implement grouping for empty values as "Value not defined" and refactor value getters for improved consistency (#1874)

* [STERDEV-1734] fix split modal regression (#1863)

[frontend-api]

* [STERDEV-1789] properly unassign by programmeId & batch unassign on update (#144)

* [STERDEV-1716] Migrate to postgredb (#141)



## Bug Fixes 🛠

* [STERDEV-1942] Lifecycle assessment period fix (#154)


[takeoff]

* [STERDEV-1868] feat: add ElementIds to Takeoff models and implement SubClaimTransformation (#253)

* [STERDEV-1882] Define & set hangfire job priorities (#245)

* [STERDEV-1813]  implement batch loading for model settings and add Gzip compression for /bim-elements endpoint (#239)



## Bug Fixes 🛠

* [STERDEV-1911] TO - Moving TOI within the TO Structure (#261)

* test(STERDEV-1883): fix 47 inherited failing tests + 19 CI infra failures (#252)

* [STERDEV-1623] Fix metadata resolution, add SignalR payload, event handler, and unit tests (#259)

* [STERDEV-1726] 2D Take-off Revisioning 'Adjust' - Derived Perimeter not being calculated (#263)

* [STERDEV-1911] TO - Moving TOI within the TO Structure (#261)

* test(STERDEV-1883): fix 47 inherited failing tests + 19 CI infra failures (#252)

* [STERDEV-1786]  Ignore invalid model ids & no rollback (#247)

* [STERDEV-1879]  Fixed takeoff references (#243)

* [STERDEV-1786] Corrected projectId assignment in ProcessModelEntities (#238)
