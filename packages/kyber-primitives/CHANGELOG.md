# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [10.0.5](http://github.com/bisenterpriseskyber/compare/v10.0.4...v10.0.5) (2020-08-11)


### Bug Fixes

* **Modal:** remove fade classes from Kyber css CE2-5149 ([a89cd59](http://github.com/bisenterpriseskyber/commits/a89cd59))






## [10.0.4](http://github.com/bisenterpriseskyber/compare/v10.0.3...v10.0.4) (2020-07-29)

**Note:** Version bump only for package @bisenterprises/kyber-primitives






## [10.0.3](http://github.com/bisenterpriseskyber/compare/v10.0.0-alpha.7...v10.0.3) (2020-07-22)


### Bug Fixes

* **Switch:** use BooleanInputIcon with Switch to keep switch UI elements contained together CE2-4684 ([4cf2b71](http://github.com/bisenterpriseskyber/commits/4cf2b71))






## [10.0.2](http://github.com/bisenterpriseskyber/compare/v10.0.0-alpha.7...v10.0.2) (2020-06-08)


### Bug Fixes

* **BooleanInput:** add label class to BooleanInput wrapper div CE2-4882 ([b43ddc2](http://github.com/bisenterpriseskyber/commits/b43ddc2))






## [10.0.1](http://github.com/bisenterpriseskyber/compare/v10.0.0-alpha.7...v10.0.1) (2020-06-03)

**Note:** Version bump only for package @bisenterprises/kyber-primitives






# [10.0.0](http://github.com/bisenterpriseskyber/compare/v10.0.0-alpha.7...v10.0.0) (2020-05-20)


### Bug Fixes

* **Label:** label within a boolean input will now be position relative CE2-4882 ([6268e63](http://github.com/bisenterpriseskyber/commits/6268e63))
* **PlusMinus:** fix PlusMinus adding className value in multiple places CE2-4846 ([50cda1a](http://github.com/bisenterpriseskyber/commits/50cda1a))
* **SearchResult:** escape all regex escape required characters that could be within a query CE2-4883 ([135af39](http://github.com/bisenterpriseskyber/commits/135af39))
* fix modal not showing in safari ([3873461](http://github.com/bisenterpriseskyber/commits/3873461))
* labels for Checkbox and Radio component will only be as long as their text CE2-4547 ([6bd8d3f](http://github.com/bisenterpriseskyber/commits/6bd8d3f))


### Code Refactoring

* stop modularizing className props CE2-4788 ([bbe3d37](http://github.com/bisenterpriseskyber/commits/bbe3d37))
* drop support for React 15 CE2-4527 ([b65273f](http://github.com/bisenterpriseskyber/commits/b65273f))
* add [@bisenterprises](http://github.com/bisenterprises.com:7999/bisenterprises) scope to kyber packages CE2-2998 ([527240b](http://github.com/bisenterpriseskyber/commits/527240b))


### Features

* create single CSS file for each package CE2-4643 ([8c6da03](http://github.com/bisenterpriseskyber/commits/8c6da03))
* kyber-components styles are now separate from ema styles CE2-3501 ([f78a835](http://github.com/bisenterpriseskyber/commits/f78a835))
* support IDs in all components and subcomponents - CE2-3681 ([59ea474](http://github.com/bisenterpriseskyber/commits/59ea474))


### BREAKING CHANGES

* className props will no longer be mangled if they match one of the component's classNames. See migration guide for details.
* React 15 is no longer supported - please upgrade to 16.8.6. See migration guide for details.
* all kyber imports are now scoped to @bisenterprises. See migration guide for details
* each package has a similarly named css file that must be
used to get that package's styles. See migration guide for details.
* kyber-component styles will no long include bootstrap styles. All bootstrap styles exist within ema.css. See migration guide for details.
* ID prop is required for all components






## [9.8.6](http://github.com/bisenterpriseskyber/compare/v9.8.5...v9.8.6) (2020-05-12)

**Note:** Version bump only for package kyber-primitives






## [9.8.5](http://github.com/bisenterpriseskyber/compare/v9.8.4...v9.8.5) (2020-05-05)

* **Label:** label within a boolean input will now be position relative CE2-4882 ([a140cd6](http://github.com/bisenterpriseskyber/commits/a140cd6))
* **SearchResult:** escape all regex escape required characters that could be within a query CE2-4883 ([e792d3f](http://github.com/bisenterpriseskyber/commits/e792d3f))






## [9.8.4](http://github.com/bisenterpriseskyber/compare/v9.8.2...v9.8.4) (2020-04-29)

**Note:** Version bump only for package kyber-primitives






## [9.8.3](http://github.com/bisenterpriseskyber/compare/v9.8.2...v9.8.3) (2020-04-27)

**Note:** Version bump only for package kyber-primitives






## [9.8.2](http://github.com/bisenterpriseskyber/compare/v9.8.1...v9.8.2) (2020-04-22)

**Note:** Version bump only for package kyber-primitives






## [9.8.1](http://github.com/bisenterpriseskyber/compare/v9.8.0...v9.8.1) (2020-02-25)

**Note:** Version bump only for package kyber-primitives






# [9.8.0](http://github.com/bisenterpriseskyber/compare/v9.7.0...v9.8.0) (2020-02-07)


### Bug Fixes

* **Button:** add missing styles for icons within buttons- CE2-4368 ([257cbf1](http://github.com/bisenterpriseskyber/commits/257cbf1))
* fix Switch styles when its inside a table - CE2-4418 ([267f027](http://github.com/bisenterpriseskyber/commits/267f027))
* show/hide body scrollbar in Modal and AutoDismissableAlert based on whether it was shown before opening CE2-2873 ([925f0e8](http://github.com/bisenterpriseskyber/commits/925f0e8))
* use flexbox instead of table layout for input groups CE2-4482 ([b8f247f](http://github.com/bisenterpriseskyber/commits/b8f247f))


### Features

* add searchable functionality to SingleSelectFilter - CE2-4475 ([37530ab](http://github.com/bisenterpriseskyber/commits/37530ab))
* static analysis with sonarjs CE2-3744 ([01853af](http://github.com/bisenterpriseskyber/commits/01853af))






# [9.7.0](http://github.com/bisenterpriseskyber/compare/v9.6.2...v9.7.0) (2019-10-29)


### Bug Fixes

* autoDismissableAlert styles CE2-3908 ([a4c13c7](http://github.com/bisenterpriseskyber/commits/a4c13c7))
* fix TableRowToggle styles for web components - CE2-4256 ([613094e](http://github.com/bisenterpriseskyber/commits/613094e))
* focus on element with data-autofocus in Modal CE2-4266 ([95f8199](http://github.com/bisenterpriseskyber/commits/95f8199))
* rename components and chart packages so they can be externalized - CE2-4334 ([f34eabe](http://github.com/bisenterpriseskyber/commits/f34eabe))


### Features

* fixed header and footer in mobile Modal CE2-3729 ([bedd0ba](http://github.com/bisenterpriseskyber/commits/bedd0ba))






## [9.6.2](http://github.com/bisenterpriseskyber/compare/v9.6.1...v9.6.2) (2019-10-21)

**Note:** Version bump only for package kyber-primitives






## [9.6.1](http://github.com/bisenterpriseskyber/compare/v9.6.0...v9.6.1) (2019-09-30)

**Note:** Version bump only for package kyber-primitives






# [9.6.0](http://github.com/bisenterpriseskyber/compare/v9.5.1...v9.6.0) (2019-09-24)


### Bug Fixes

* **kyber-components:** context subscriptions for Table CE2-3770 ([3a4a62a](http://github.com/bisenterpriseskyber/commits/3a4a62a))
* add prefix to primitive classes to avoid naming conflict - CE2-4161 ([c13f9bb](http://github.com/bisenterpriseskyber/commits/c13f9bb))
* fix backdrop shadow for AutoDimissiableAlert - CE2-3878 ([091c8bd](http://github.com/bisenterpriseskyber/commits/091c8bd))
* fix focus styling on switch - CE-3572 ([cbe50fe](http://github.com/bisenterpriseskyber/commits/cbe50fe))


### Features

* add form component primitives to kyber-primitives - CE2-3833 ([c7e8f09](http://github.com/bisenterpriseskyber/commits/c7e8f09))
* add saveRef to table primitives ([4fb2649](http://github.com/bisenterpriseskyber/commits/4fb2649))






## [9.5.1](http://github.com/bisenterpriseskyber/compare/v9.5.0...v9.5.1) (2019-08-07)

**Note:** Version bump only for package kyber-primitives






# [9.5.0](http://github.com/bisenterpriseskyber/compare/v9.4.2...v9.5.0) (2019-08-06)


### Features

* export Modal primitives CE2-3755 ([55f8846](http://github.com/bisenterpriseskyber/commits/55f8846))
* export Table primitives CE2-3755 ([b83635c](http://github.com/bisenterpriseskyber/commits/b83635c))






## [9.4.2](http://github.com/bisenterpriseskyber/compare/v9.4.1...v9.4.2) (2019-07-22)

**Note:** Version bump only for package kyber-primitives






## [9.4.1](http://github.com/bisenterpriseskyber/compare/v9.4.0...v9.4.1) (2019-07-17)


### Bug Fixes

* primitive and formfield styling lost CE2-3738 ([91f2be1](http://github.com/bisenterpriseskyber/commits/91f2be1))






# [9.4.0](http://github.com/bisenterpriseskyber/compare/v9.3.0...v9.4.0) (2019-07-10)


### Features

* generate a css file instead of embedding styles CE2-3716 ([3f6465c](http://github.com/bisenterpriseskyber/commits/3f6465c))






## [9.3.2](http://github.com/bisenterpriseskyber/compare/v9.3.1...v9.3.2) (2019-07-09)

**Note:** Version bump only for package kyber-primitives






# [9.3.0](http://github.com/bisenterpriseskyber/compare/v9.2.0...v9.3.0) (2019-06-06)


### Features

* **primitives:** create kyber primitives package ([54855ec](http://github.com/bisenterpriseskyber/commits/54855ec))
* CE2-3065 - upgrade to React 16 ([b4c7c3d](http://github.com/bisenterpriseskyber/commits/b4c7c3d))
