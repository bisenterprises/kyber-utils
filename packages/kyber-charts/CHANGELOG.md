# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [10.0.5](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.4&sourceBranch=refs%2Ftags%2Fv10.0.5) (2020-08-11)

**Note:** Version bump only for package @bisenterprises/kyber-charts






## [10.0.4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.3&sourceBranch=refs%2Ftags%2Fv10.0.4) (2020-07-29)

**Note:** Version bump only for package @bisenterprises/kyber-charts






## [10.0.3](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.0-alpha.7&sourceBranch=refs%2Ftags%2Fv10.0.3) (2020-07-22)

**Note:** Version bump only for package @bisenterprises/kyber-charts






## [10.0.2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.0-alpha.7&sourceBranch=refs%2Ftags%2Fv10.0.2) (2020-06-08)

**Note:** Version bump only for package @bisenterprises/kyber-charts






## [10.0.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.0-alpha.7&sourceBranch=refs%2Ftags%2Fv10.0.1) (2020-06-03)

**Note:** Version bump only for package @bisenterprises/kyber-charts






# [10.0.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.0-alpha.7&sourceBranch=refs%2Ftags%2Fv10.0.0) (2020-05-20)

### Bug Fixes

* fix chart loading styles so they are responsive and match chart size CE2-4783 ([4b2a445](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4b2a445))


### chore

* remove core-js polyfills ([2e511be](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/2e511be))


### Code Refactoring

* stop modularizing className props CE2-4788 ([bbe3d37](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/bbe3d37))
* upgrade highcharts and fix BarChart animation bug CE2-4434 ([d583d44](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/d583d44))
* drop support for React 15 CE2-4527 ([b65273f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b65273f))


### BREAKING CHANGES

* DonutChart and MeteredDonutChart's "chartLineWidth" prop and SkeletonCircle's "lineWidth" prop now used as a percentage relative to the chart's radius. See Migration Guide for details.
* upgrade highcharts to 8.0.4
* className props will no longer be mangled if they match one of the component's classNames. See migration guide for details.
* React 15 is no longer supported - please upgrade to 16.8.6. See migration guide for details.
* core-js polyfills are no longer included. See migration guide for details.






## [9.8.6](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.5&sourceBranch=refs%2Ftags%2Fv9.8.6) (2020-05-12)

**Note:** Version bump only for package kyber-charts






## [9.8.5](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.4&sourceBranch=refs%2Ftags%2Fv9.8.5) (2020-05-05)

**Note:** Version bump only for package kyber-charts






## [9.8.4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.2&sourceBranch=refs%2Ftags%2Fv9.8.4) (2020-04-29)

**Note:** Version bump only for package kyber-charts






## [9.8.3](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.2&sourceBranch=refs%2Ftags%2Fv9.8.3) (2020-04-27)

**Note:** Version bump only for package kyber-charts






## [9.8.2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.1&sourceBranch=refs%2Ftags%2Fv9.8.2) (2020-04-22)

**Note:** Version bump only for package kyber-charts






## [9.8.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.0&sourceBranch=refs%2Ftags%2Fv9.8.1) (2020-02-25)

**Note:** Version bump only for package kyber-charts






# [9.8.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.7.0&sourceBranch=refs%2Ftags%2Fv9.8.0) (2020-02-07)


### Bug Fixes

* close popover when clicking on a chart CE2-4374 ([781c231](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/781c231))
* disable hovering for multi series charts when interactionEnabled is false - CE2-4349 ([94f61aa](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/94f61aa))


### Features

* static analysis with sonarjs CE2-3744 ([01853af](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/01853af))
* **SmartField:** add validationLabel prop CE2-3727 ([706c148](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/706c148))






# [9.7.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.6.2&sourceBranch=refs%2Ftags%2Fv9.7.0) (2019-10-29)


### Bug Fixes

* aria usage issues for DonutChart, ComboBox, and MenuButton CE2-3838 ([4ed43b7](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4ed43b7))
* rename components and chart packages so they can be externalized - CE2-4334 ([f34eabe](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f34eabe))


### Features

* upgrade highcharts to 7.1.2 - CE2-3809 ([2c02d2a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/2c02d2a))






## [9.6.2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.6.1&sourceBranch=refs%2Ftags%2Fv9.6.2) (2019-10-21)

**Note:** Version bump only for package kyber-charts






## [9.6.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.6.0&sourceBranch=refs%2Ftags%2Fv9.6.1) (2019-09-30)

**Note:** Version bump only for package kyber-charts






# [9.6.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.5.1&sourceBranch=refs%2Ftags%2Fv9.6.0) (2019-09-24)


### Bug Fixes

* remove no data subtitle when switching from no data to data chart ([4388a27](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4388a27))


### Features

* use rollup to output modules with docgen ([d4fd83f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/d4fd83f))






## [9.5.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.5.0&sourceBranch=refs%2Ftags%2Fv9.5.1) (2019-08-07)

**Note:** Version bump only for package kyber-charts






# [9.5.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.4.2&sourceBranch=refs%2Ftags%2Fv9.5.0) (2019-08-06)


### Bug Fixes

* fix BarChart multi point tooltip formatting - CE2-3584 ([ffa4880](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/ffa4880))


### Features

* **kyber-storybook:** upgrade to Storybook 5 ([11e1483](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/11e1483))






## [9.4.2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.4.1&sourceBranch=refs%2Ftags%2Fv9.4.2) (2019-07-22)

**Note:** Version bump only for package kyber-charts






## [9.4.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.4.0&sourceBranch=refs%2Ftags%2Fv9.4.1) (2019-07-17)

**Note:** Version bump only for package kyber-charts






# [9.4.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.3.0&sourceBranch=refs%2Ftags%2Fv9.4.0) (2019-07-10)


### Bug Fixes

* fix the highcharts bundle url for charts manifest ([0d5fc8e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/0d5fc8e))
* interactionEnabled works when set to false on BarChart CE2-3588 ([491c51a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/491c51a))


### Features

* generate a css file instead of embedding styles CE2-3716 ([3f6465c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3f6465c))






## [9.3.2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.3.1&sourceBranch=refs%2Ftags%2Fv9.3.2) (2019-07-09)

**Note:** Version bump only for package kyber-charts






## [9.3.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.3.0&sourceBranch=refs%2Ftags%2Fv9.3.1) (2019-06-25)

**Note:** Version bump only for package kyber-charts






# [9.3.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.2.0&sourceBranch=refs%2Ftags%2Fv9.3.0) (2019-06-06)


### Features

* CE2-3065 - upgrade to React 16 ([b4c7c3d](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b4c7c3d))
* upgrade to babel 7 ([f1bcbd5](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f1bcbd5))






# [9.2.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.0.0&sourceBranch=refs%2Ftags%2Fv9.2.0) (2019-05-02)

### Bug Fixes

-   **kyber-charts:** interactionEnabled on area and area range charts ([d7eae8f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/d7eae8f))

### Features

-   jsconfigs for vscode usage ([def00aa](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/def00aa))
-   **kyber-charts:** add loading state to area and area range charts ([037a0fa](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/037a0fa))

# [9.1.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.0.0&sourceBranch=refs%2Ftags%2Fv9.1.0) (2019-04-16)

### Bug Fixes

-   CE2-3335 - stop hovering on MeteredDonutChart ([854ac3e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/854ac3e))
-   CE2-3340 - export Formatters ([d120ad7](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/d120ad7))

### Features

-   jsconfigs for vscode usage ([def00aa](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/def00aa))

## [9.0.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.0.0&sourceBranch=refs%2Ftags%2Fv9.0.1) (2019-04-02)

**Note:** Version bump only for package kyber-charts

# [9.0.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv8.3.0&sourceBranch=refs%2Ftags%2Fv9.0.0) (2019-03-27)

### Bug Fixes

-   add series building to area and area range chart ([b4939de](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b4939de))
-   BarChart xAxis default value ([f513869](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f513869))
-   barchart y-axis should default to empty ([a6be844](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a6be844))
-   deep merge chart options. CE2-3117 ([3ff1449](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3ff1449))
-   delete commented code ([691e88c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/691e88c))
-   don't exit develop builds on ESLint errors ([91b2834](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/91b2834))
-   donut chart hover and interaction enabled bug ([82fc248](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/82fc248))
-   eslint ignore kyber-components when building charts ([6765dde](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/6765dde))
-   fix negative rounding in shortCurrencyFormatter ([3cda915](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3cda915))
-   fix spacing issue when no name is available for tooltip ([7517d1e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/7517d1e))
-   make AMD react lower case in Kyber-Charts ([c12beb7](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/c12beb7))
-   optimize package json scripts and webpack plugins ([afa7bb1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/afa7bb1))
-   pass x and y axis labels to base chart ([55a5d51](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/55a5d51))
-   remove chartType from props that are passed to highcharts ([29c8e02](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/29c8e02))
-   remove watch flag from kyber-charts start script ([fab7fd3](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/fab7fd3))
-   **kyber-charts:** support no data state ([51906ef](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/51906ef))
-   reset subtitle text so toggling data prop works ([9601f87](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/9601f87))
-   skeleton circle import in test ([a7b1c2e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a7b1c2e))
-   skeleton component imports for charts ([32fbd77](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/32fbd77))
-   toggling no data in BarChart visual issues ([7cdf3f8](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/7cdf3f8))

### Code Refactoring

-   change donut chart data object to accept y instead of value ([0feb8b7](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/0feb8b7))

### Features

-   accept `formatType` prop in AreaRange chart ([2341d52](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/2341d52))
-   accept `formatType` prop in LineChart ([f715922](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f715922))
-   accept `formatType` prop in PieChart component ([096aedf](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/096aedf))
-   add `chartCallback` prop ([374af8b](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/374af8b))
-   add `chartCallback` prop to charts ([48a8282](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/48a8282))
-   add and configure speed-measure-webpack-plugin ([f9011f2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f9011f2))
-   add support for a multiple point tooltip ([2304dfa](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/2304dfa))
-   area chart implementation ([8bf020c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8bf020c))
-   enable js sourcemaps ([34a7be8](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/34a7be8))
-   implement multiple data format handling function ([635c245](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/635c245))
-   refactor and improve TreeMap ([38e25c3](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/38e25c3))
-   support tooltip custom value formatting ([18e15a3](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/18e15a3))
-   update scripts so kyber-components is built first ([220bc3b](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/220bc3b))
-   upgrade highcharts to 7.0.2 ([1680532](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1680532))
-   use css modules ([5cdb103](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/5cdb103))
-   wire up series builder from data for remaining charts ([3ded2cf](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3ded2cf))

### BREAKING CHANGES

-   donut chart data format changed to match highcharts expectations
