# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [10.0.5](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.4&sourceBranch=refs%2Ftags%2Fv10.0.5) (2020-08-11)

**Note:** Version bump only for package @bisenterprises/kyber-filters






## [10.0.4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.3&sourceBranch=refs%2Ftags%2Fv10.0.4) (2020-07-29)

**Note:** Version bump only for package @bisenterprises/kyber-filters






## [10.0.3](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.0-alpha.7&sourceBranch=refs%2Ftags%2Fv10.0.3) (2020-07-22)


### Bug Fixes

* **BooleanInput:** add label class to BooleanInput wrapper div CE2-4882 ([b43ddc2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b43ddc2))
* set unique ID on croutons in filter popover CE2-4917 ([054c9e4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/054c9e4))






## [10.0.2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.0-alpha.7&sourceBranch=refs%2Ftags%2Fv10.0.2) (2020-06-08)


### Bug Fixes

* **BooleanInput:** add label class to BooleanInput wrapper div CE2-4882 ([b43ddc2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b43ddc2))
* set unique ID on croutons in filter popover CE2-4917 ([054c9e4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/054c9e4))






## [10.0.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.0-alpha.7&sourceBranch=refs%2Ftags%2Fv10.0.1) (2020-06-03)

**Note:** Version bump only for package @bisenterprises/kyber-filters






# [10.0.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.0-alpha.7&sourceBranch=refs%2Ftags%2Fv10.0.0) (2020-05-20)


### Bug Fixes

* set unique ID on croutons in filter popover CE2-4917 ([054c9e4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/054c9e4))
* **Label:** label within a boolean input will now be position relative CE2-4882 ([6268e63](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/6268e63))
* **NumberField:** fix NumberField readOnly focus styles to be consistent with other read only form inputs CE2-3812 ([7e37bec](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/7e37bec))
* **PlusMinus:** fix PlusMinus adding className value in multiple places CE2-4846 ([50cda1a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/50cda1a))
* **FormattedInput:** fix to pass "type" prop to underlying Input component ([20b3594](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/20b3594))
* labels for Checkbox and Radio component will only be as long as their text CE2-4547 ([6bd8d3f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/6bd8d3f))


### Code Refactoring

* remove noPortal props and use Context instead CE2-4808 ([00c6489](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/00c6489))
* stop modularizing className props CE2-4788 ([bbe3d37](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/bbe3d37))
* drop support for React 15 CE2-4527 ([b65273f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b65273f))
* add [@bisenterprises](http://github.com/bisenterprises.com:7999/bisenterprises) scope to kyber packages CE2-2998 ([527240b](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/527240b))
* **ChartLegend:** remove depedency on bootstrap grid ([0ece422](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/0ece422))


### Features

* add signLeft prop to TextField CE2-4794 ([bf95ef0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/bf95ef0))
* create @bisenterprises/kyber-forms package CE2-4532 ([20ff849](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/20ff849))
* create single CSS file for each package CE2-4643 ([8c6da03](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8c6da03))
* kyber-components styles are now separate from ema styles CE2-3501 ([f78a835](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f78a835))
* support IDs in all components and subcomponents - CE2-3681 ([59ea474](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/59ea474))


### chore

* fix "contraintName" and "contraintLabel" typos in SmartField ([90d0b5c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/90d0b5c))


### BREAKING CHANGES

* all "noPortal" props have been removed in favor of using PortalContext. See Migration Guide for details.
* className props will no longer be mangled if they match one of the component's classNames. See migration guide for details.
* React 15 is no longer supported - please upgrade to 16.8.6. See migration guide for details.
* con(s)traintName and con(s)traintLabel are now spelled correctly. See Migration Guide for details.
* all kyber imports are now scoped to @bisenterprises. See migration guide for details
* each package has a similarly named css file that must be
used to get that package's styles. See migration guide for details.
* **ChartLegend:** ChartLegend's className will no longer default to using bootstrap grid columns. See migration guide for details.
* kyber-component styles will no long include bootstrap styles. All bootstrap styles exist within ema.css. See migration guide for details.
* ID prop is required for all components






## [9.8.6](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.5&sourceBranch=refs%2Ftags%2Fv9.8.6) (2020-05-12)

**Note:** Version bump only for package kyber-filters






## [9.8.5](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.4&sourceBranch=refs%2Ftags%2Fv9.8.5) (2020-05-05)


### Bug Fixes

* **Label:** label within a boolean input will now be position relative CE2-4882 ([a140cd6](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a140cd6))






## [9.8.4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.2&sourceBranch=refs%2Ftags%2Fv9.8.4) (2020-04-29)


### Bug Fixes

* kyber package dependency on kyber-filters and word wrap behavior for SearchableMultiSelectFilter CE2-4878 ([a2ef91e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a2ef91e))






## [9.8.3](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.2&sourceBranch=refs%2Ftags%2Fv9.8.3) (2020-04-27)

**Note:** Version bump only for package kyber-filters






## [9.8.2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.1&sourceBranch=refs%2Ftags%2Fv9.8.2) (2020-04-22)

**Note:** Version bump only for package kyber-filters






## [9.8.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.0&sourceBranch=refs%2Ftags%2Fv9.8.1) (2020-02-25)

**Note:** Version bump only for package kyber-filters






# [9.8.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.7.0&sourceBranch=refs%2Ftags%2Fv9.8.0) (2020-02-07)


### Features

* add CollapsibleMultiSelectFilter component CE2-4520 ([6d14272](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/6d14272))
* add kyber-filters package and NumberFilter component CE2-4146 ([c304d34](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/c304d34))
* add MultiSelectFilter to kyber-filters package CE2-4476 ([3acc26c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3acc26c))
* add searchable functionality to SingleSelectFilter - CE2-4475 ([37530ab](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/37530ab))
* add Searchable MultiSelectFilter CE2-4477 ([b3627a8](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b3627a8))
* add SingleSelectFilter - CE2-4474 ([8bdb7d7](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8bdb7d7))
* added new DateRangeFilter - CE2-4662 ([291afbf](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/291afbf))
* implement add filters button to FilterBar - CE2-4471 ([1c42de4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1c42de4))
* **CollapsibleSingleSelectFilter:** add new CollapsibleSingleSelectFilter CE2-4661 ([8ad5ccf](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8ad5ccf))
