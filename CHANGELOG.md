## [Unreleased]

## [1.0.0-beta1] - 2018-08-22
### Changed
- fixed upstream #1123 - Vue.use order for ExpansionPanel and Button breaks expansion panel toggle button
- added styling container for active tab indicator (aditional custom styles can be applied on container for better/styled look)
- fixed indicator left offset not calculated properly 

## [1.0.0-beta1] - 2018-08-12
### Changed
- removed top border from expanded expansion panel
- removed top and bottom margin from expanded expansion panel
- removed height changing for expanded expansion panel header 

## [1.0.0-beta1] - 2018-08-10
### Added
- custom nestedX CSS class for managing nested lists; class must be implemented outside library

### Changed
- removed nested level padding for list items, will use nestedX class instead
- removed some rarely used classes from grid system - some flex orders and flex offsets
- translated noDataText grid property 
