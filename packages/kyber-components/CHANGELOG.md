# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [10.0.5](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.4&sourceBranch=refs%2Ftags%2Fv10.0.5) (2020-08-11)


### Bug Fixes

* **Modal:** remove fade classes from Kyber css CE2-5149 ([a89cd59](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a89cd59))






## [10.0.4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.3&sourceBranch=refs%2Ftags%2Fv10.0.4) (2020-07-29)


### Bug Fixes

* generate ids for AiraMenuItem and AriaListBoxOptions, adjust the selectedItem selector within list boxes to use a data attribute CE2-5119 ([20e11b2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/20e11b2))






## [10.0.3](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.0-alpha.7&sourceBranch=refs%2Ftags%2Fv10.0.3) (2020-07-22)


### Bug Fixes

**Note:** Version bump only for package @bisenterprises/kyber-components






## [10.0.2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.0-alpha.7&sourceBranch=refs%2Ftags%2Fv10.0.2) (2020-06-08)

**Note:** Version bump only for package @bisenterprises/kyber-components






## [10.0.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.0-alpha.7&sourceBranch=refs%2Ftags%2Fv10.0.1) (2020-06-03)


### Bug Fixes

* fix focus and blur behavior in PlusMinus CE2-4964 ([a0b55c8](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a0b55c8))






# [10.0.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv10.0.0-alpha.7&sourceBranch=refs%2Ftags%2Fv10.0.0) (2020-05-20)


### Bug Fixes

* **Modal:** add PortalContext.Provider to Modal so child components don't use portals ([8d63169](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8d63169))
* set unique ID on croutons in filter popover CE2-4917 ([054c9e4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/054c9e4))
* **AutoDismissableAlert:** change auto dismissible alert min-width to be more narrow ([f283cc7](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f283cc7))
* **Modal:** fix issue where tab focus was not scoped to modal CE2-4810 ([a4a4caf](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a4a4caf))
* **NumberField:** fix NumberField readOnly focus styles to be consistent with other read only form inputs CE2-3812 ([7e37bec](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/7e37bec))
* **PlusMinus:** fix PlusMinus adding className value in multiple places CE2-4846 ([50cda1a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/50cda1a))
* **PlusMinus:** fix PlusMinus so it doesn't capture focus when in readonly mode CE2-4809 ([e2e3000](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/e2e3000))
* **Search, SelectBox:** send space event to AriaComboBox trigger CE2-4858 ([de6d01f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/de6d01f))
* fix chart loading styles so they are responsive and match chart size CE2-4783 ([4b2a445](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4b2a445))
* labels for Checkbox and Radio component will only be as long as their text CE2-4547 ([6bd8d3f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/6bd8d3f))


### Code Refactoring

* remove deprecated props and helpers CE2-4833 ([01e9e6e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/01e9e6e))
* remove noPortal props and use Context instead CE2-4808 ([00c6489](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/00c6489))
* **Pagination:** make PaginationNew the default and remove the old Pagination component CE2-4807 ([7eec554](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/7eec554))
* stop modularizing className props CE2-4788 ([bbe3d37](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/bbe3d37))
* drop support for React 15 CE2-4527 ([b65273f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b65273f))
* remove Dropdown component CE2-4535 ([6699bfd](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/6699bfd))
* rename TabsNew to Tabs CE2-4516 ([e97816a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/e97816a))


### Features

* add signLeft prop to TextField CE2-4794 ([bf95ef0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/bf95ef0))
* add support for React nodes in Tooltip's title prop CE2-4832 ([2f25f7d](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/2f25f7d))
* update ButtonWithDropdown keyboard behavior CE2-4789 ([3175ebb](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3175ebb))
* create @bisenterprises/kyber-forms package CE2-4532 ([20ff849](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/20ff849))
* create the @bisenterprises/kyber-tables package CE2-4532 ([a1ab597](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a1ab597))
* update clickDebounceTime behavior in Button so the event is fired at the leading edge of the timeout instead of the trailing edge CE2-4518 ([d247949](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/d247949))


### chore

* fix "contraintName" and "contraintLabel" typos in SmartField ([90d0b5c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/90d0b5c))
* remove legacy portal component ([16c8612](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/16c8612))
* **Modal:** rename Modal buttons and links `name` props to `children` to prevent overriding default `name` prop CE2-3205 ([332fccf](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/332fccf))
* remove core-js polyfills ([2e511be](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/2e511be))
* remove dropdown-item-wrapper class CE2-4525 ([665ad0a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/665ad0a))


### BREAKING CHANGES

* DonutChart and MeteredDonutChart's "chartLineWidth" prop and SkeletonCircle's "lineWidth" prop now used as a percentage relative to the chart's radius. See Migration Guide for details.
* deprecated props and helpers have been removed from Kyber. See migration guide for details.
* all "noPortal" props have been removed in favor of using PortalContext. See Migration Guide for details.
* **Pagination:** Pagination component replaced by PaginationNew. See migration guide for details on prop changes.
* className props will no longer be mangled if they match one of the component's classNames. See migration guide for details.
* React 15 is no longer supported - please upgrade to 16.8.6. See migration guide for details.
* Portal component only uses the new React 16 Portal API and is not compatible with React 15. Used by Popover, Tooltip, DatePickerCalendarWrapper, ButtonWithDropdown, ContextMenu, and SelectBox. See Migration Guide for details.
* con(s)traintName and con(s)traintLabel are now spelled correctly. See Migration Guide for details.
* Dropdown component has been removed. See migration guide for details.
* Table and related components have been moved to a separate package: @bisenterprises/kyber-tables. See migration guide for details.
* **Modal:** Modal `buttons > name` and `links > name` prop renamed to `children`. See migration guide for details.
* core-js polyfills are no longer included. See migration guide for details.
* the dropdown-item-wrapper class no longer exists. See migration guide for details.
* Tabs has been replaced with what was formerly named TabsNew. See migration guide for details






## [9.8.6](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.5&sourceBranch=refs%2Ftags%2Fv9.8.6) (2020-05-12)

**Note:** Version bump only for package kyber-components






## [9.8.5](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.4&sourceBranch=refs%2Ftags%2Fv9.8.5) (2020-05-05)

**Note:** Version bump only for package kyber-components






## [9.8.4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.2&sourceBranch=refs%2Ftags%2Fv9.8.4) (2020-04-29)

**Note:** Version bump only for package kyber-components






## [9.8.3](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.2&sourceBranch=refs%2Ftags%2Fv9.8.3) (2020-04-27)

**Note:** Version bump only for package kyber-components






## [9.8.2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.1&sourceBranch=refs%2Ftags%2Fv9.8.2) (2020-04-22)

**Note:** Version bump only for package kyber-components






## [9.8.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.8.0&sourceBranch=refs%2Ftags%2Fv9.8.1) (2020-02-25)


### Bug Fixes

* nested Portal issue with Slider in a Popover CE2-4718 ([eed3f91](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/eed3f91))






# [9.8.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.7.0&sourceBranch=refs%2Ftags%2Fv9.8.0) (2020-02-07)


### Bug Fixes

* **ButtonWithDropdown:** having to double tap to open menu after it was closed on iOS CE2-4354 ([3edc4c6](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3edc4c6))
* **HorizontalScrollingList:** scroll HorizontalScrollingList on window resize CE2-4293 ([856fda4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/856fda4))
* **kyber-components:** collapsible table executes row subscriptions CE2-4406 ([5140aa0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/5140aa0))
* **Modal:** pass className and restProps through Modal's "buttons" and "links" props CE2-4491 ([82d6e14](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/82d6e14))
* **PillNav:** update active pill when "activePill" prop changes ([f9e81a6](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f9e81a6))
* **Popover:** fix disabled button closing Popover CE2-4317 ([4fa20e9](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4fa20e9))
* add bottom border to full width of page for TabsNew - CE2-4480 ([57cf0a2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/57cf0a2))
* close multiselect nonsearchable selectbox on click outside component CE2-4390 ([9afac43](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/9afac43))
* close popover when clicking on a chart CE2-4374 ([781c231](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/781c231))
* fix Radio and custom component styling in dropdowns CE2-4389 ([4533a95](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4533a95))
* **TreeNav:** remove icon underline on hover in TreeNav in IE CE2-4407 ([d55e3f9](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/d55e3f9))
* prevent scrolling while using Slider on mobile devices CE2-4328 ([58749fb](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/58749fb))
* remove unnecessary ScrollTopButton border - CE2-1974 ([e39d6e3](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/e39d6e3))
* **TreeNav:** remove icon underline on hover in TreeNav in Edge CE2-4407 ([392d87f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/392d87f))
* Search and SearchNew no longer throw an error when label is not set - CE2-2736 ([63558c6](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/63558c6))
* show/hide body scrollbar in Modal and AutoDismissableAlert based on whether it was shown before opening CE2-2873 ([925f0e8](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/925f0e8))
* **ProgressTracker:** fix issues when inside web components CE2-4007 ([356baa4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/356baa4))
* **SelectBox:** pressing enter or space on crouton in multiselect no longer opens dropdown - CE2-3321 ([763e675](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/763e675))
* **Slider:** step prop now controls slider drag position CE2-3808 ([bfd4f3e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/bfd4f3e))
* skeleton loader animation performance CE2-4479 ([1312b83](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1312b83))
* stop arrow key functionality from incrementing plusminus when its readonly - CE2-4269 ([5344379](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/5344379))
* TabsNew - children prop is no longer marked required - CE2-4324 ([85169fb](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/85169fb))
* use flexbox instead of table layout for input groups CE2-4482 ([b8f247f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b8f247f))
* validationRules and validationMessages props at the smartForm level will now be validated onSubmit - CE2-4378 ([b191479](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b191479))


### Features

* add disabled prop to DropdownItem and MultiLineDropdownItem - CE2-3843 ([057edbe](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/057edbe))
* add kyber-filters package and NumberFilter component CE2-4146 ([c304d34](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/c304d34))
* **SmartField:** add validationLabel prop CE2-3727 ([706c148](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/706c148))
* add PaginationNew component - CE2-3658 ([c125bbb](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/c125bbb))
* **Modal:** add new "footerRenderer" prop to Modal CE2-4604 ([747d3d1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/747d3d1))
* **Slider:** add roundLabelToStep prop CE2-2833 ([eb9a2f7](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/eb9a2f7))
* add searchable functionality to SingleSelectFilter - CE2-4475 ([37530ab](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/37530ab))
* add Searchable MultiSelectFilter CE2-4477 ([b3627a8](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b3627a8))
* change pagination selected color to fit the rest of Kyber - CE2-4330 ([eec1522](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/eec1522))
* static analysis with sonarjs CE2-3744 ([01853af](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/01853af))
* **SmartForm:** allow fields with validation to be removed CE2-4521 ([4bedaf4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4bedaf4))






# [9.7.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.6.2&sourceBranch=refs%2Ftags%2Fv9.7.0) (2019-10-29)


### Bug Fixes

* add support for numbers in DropdownItem CE2-4157 ([e5b02d8](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/e5b02d8))
* add wrapperClassName prop to tooltip for more custom styling flexibility - CE2-3725 ([6b859f9](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/6b859f9))
* aria usage issues for DonutChart, ComboBox, and MenuButton CE2-3838 ([4ed43b7](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4ed43b7))
* autoDismissableAlert styles CE2-3908 ([a4c13c7](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a4c13c7))
* circular progress loader CE2-3865 ([1c41e08](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1c41e08))
* classname being replaced by restProps ([a1b97a6](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a1b97a6))
* disabled buttons text will no longer shift when pressed - CE2-4261 ([5f0ef56](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/5f0ef56))
* dont call onTabClick on disabled tabs - CE2-3449 ([daa3da5](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/daa3da5))
* fix plus minus styles in webcomponents - CE2-3848 ([185b337](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/185b337))
* fix TableRowToggle styles for web components - CE2-4256 ([613094e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/613094e))
* focus on element with data-autofocus in Modal CE2-4266 ([95f8199](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/95f8199))
* map Link saveRef prop to Button innerRef CE2-4259 ([869bc3b](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/869bc3b))
* pass anchorNode to portal in DatePicker CE2-3985 ([4ee29c4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4ee29c4))
* popover z-index order CE2-4327 ([e779e59](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/e779e59))
* rename components and chart packages so they can be externalized - CE2-4334 ([f34eabe](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f34eabe))
* support all valid formats when parsing dates for DatePicker's calendar CE2-4313 ([7492c68](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/7492c68))
* use displayName to determine option role in dropdown CE2-3336 ([5770fd2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/5770fd2))


### Features

* add `percent` format type to NumberField and PlusMinus CE2-4270 ([0526555](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/0526555))
* add `styleChildren` prop to DropdownItem CE2-4157 ([17ccdd9](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/17ccdd9))
* convert SearchNew to use css modules - CE2-3454 ([efa094b](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/efa094b))
* create SearchNew component CE2-2033 ([af6d83b](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/af6d83b))






## [9.6.2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.6.1&sourceBranch=refs%2Ftags%2Fv9.6.2) (2019-10-21)


### Bug Fixes

* fix SelectBox focus issue in Popover CE2-4325 ([3bf5806](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3bf5806))






## [9.6.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.6.0&sourceBranch=refs%2Ftags%2Fv9.6.1) (2019-09-30)


### Bug Fixes

* do not copy ES modules for primitives into kyber dist CE2-4295 ([f55c0f3](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f55c0f3))


### BREAKING CHANGES

* kyber-primitives ES modules will no longer be included as part of the kyber distribution, see [migration guide](https://confluence.bisenterprises.com/x/o42zBg)






# [9.6.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.5.1&sourceBranch=refs%2Ftags%2Fv9.6.0) (2019-09-24)


### Bug Fixes

* add additional check around ref to avoid null error - CE2-3309 ([77cabab](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/77cabab))
* arrow keys for AriaMenuButton CE2-3267 ([b48cff0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b48cff0))
* close menu and focus on input with esc/tab keys CE2-3794 ([d1c6eb3](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/d1c6eb3))
* don't open tooltip when disabled on touch CE2-4089 ([7eaef94](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/7eaef94))
* fix calendar selection for MMMM dd, YYYY dates - CE2-3734 ([90c703b](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/90c703b))
* fix console error when modal cant find focusable element - CE2-4070 ([dd0e15c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/dd0e15c))
* fix focusing of listgroup in safari to enable keyboard nav ([59176e8](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/59176e8))
* fix selectbox not closing within a webcomponent - CE2-3821 ([7c1452a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/7c1452a))
* nonSearchableSelectBox selected text color ([a33607e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a33607e))
* recalculate header/footer when columns change ([c9b7a83](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/c9b7a83))
* selectbox input border in web component CE2-3896 ([39e70ef](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/39e70ef))
* **kyber-components:** compose path for web component Tooltip CE2-3850 ([10bd022](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/10bd022))
* **kyber-components:** context subscriptions for Table CE2-3770 ([3a4a62a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3a4a62a))
* **kyber-components:** tooltip portal mount to anchor node CE2-3807 ([130e1a4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/130e1a4))


### Features

* add clickDebounceTime prop to Button - CE2-2698 ([ac896a8](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/ac896a8))
* add form component primitives to kyber-primitives - CE2-3833 ([c7e8f09](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/c7e8f09))
* convert ListGroup to use CSS Modules - CE2-3442 ([b359fdc](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b359fdc))
* convert PageHeader to use css modules - CE2-3447 ([a0a932a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a0a932a))
* convert Pagination component to use Css Modules - CE2-3448 ([d38bc6d](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/d38bc6d))
* convert ScrollTopButton to use css modules - CE2-3438 ([ca19602](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/ca19602))
* create web component resets css ([f663210](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f663210))
* css modules for Panel CE2-3449 ([c38e23e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/c38e23e))
* css-modules for Button CE2-3436 ([41beeae](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/41beeae))
* **kyber-components:** onChange of DatePicker includes js date CE2-3737 ([2ecb42e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/2ecb42e))
* refactor Microphone to use css modules - CE2-3445 ([dc00a00](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/dc00a00))
* refactor ProgressBar to utilize css modules - CE2-3452 ([aeb0eda](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/aeb0eda))
* use rollup to output modules with docgen ([d4fd83f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/d4fd83f))






## [9.5.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.5.0&sourceBranch=refs%2Ftags%2Fv9.5.1) (2019-08-07)

**Note:** Version bump only for package kyber-components






# [9.5.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.4.2&sourceBranch=refs%2Ftags%2Fv9.5.0) (2019-08-06)


### Bug Fixes

* align DatePicker blur event with other form inputs. CE2-3674 ([0fed1b5](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/0fed1b5))
* circular progress loader styling broken in modals. CE2-3759 ([8c89752](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8c89752))
* close non-searchable selectbox dropdown when clicking on target ([5a25b45](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/5a25b45))
* fix crouton styling or selectbox multi-select - CE2-3758 ([285714c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/285714c))
* fix DatePicker & NumberField style regressions - CE2-3757, CE2-3760 ([4fb123d](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4fb123d))
* fix numberfield readonly styling - CE2-3760 ([56decb8](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/56decb8))
* fix spacing issues in checkbox and radio groups - CE2-2712 ([bf4f319](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/bf4f319))
* override 8.4.0 styling for buttons in a form - CE2-3767 ([ac88cde](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/ac88cde))
* primitive and formfield styling lost CE2-3738 ([bda46d9](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/bda46d9))
* skeleton table border radius regression CE2-3839 ([bc54056](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/bc54056))
* skeleton table header border radius ([cd96f3e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/cd96f3e))


### Features

* add fixed footer support ([8c4858d](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8c4858d))
* add fixed table header to container functionality ([1149074](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1149074))
* add support for fixedHeader="window" prop ([9fd7185](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/9fd7185))
* **kyber-components:** css module ContextMenu CE2-3435 ([b24a27e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b24a27e))
* **kyber-storybook:** upgrade to Storybook 5 ([11e1483](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/11e1483))
* convert backlink to use css modules - CE2-3441 ([5f883b0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/5f883b0))
* export Modal primitives CE2-3755 ([55f8846](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/55f8846))
* export Table primitives CE2-3755 ([b83635c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b83635c))
* update CircularProgressLoader CE2-3444 ([0bda541](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/0bda541))






## [9.4.2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.4.1&sourceBranch=refs%2Ftags%2Fv9.4.2) (2019-07-22)


### Bug Fixes

* revert Table changes in 9.3.2 CE2-3792 ([c7ff4f0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/c7ff4f0))






## [9.4.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.4.0&sourceBranch=refs%2Ftags%2Fv9.4.1) (2019-07-17)


### Bug Fixes

* circular progress loader styling broken in modals. CE2-3759 ([742498d](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/742498d))
* fix crouton styling or selectbox multi-select - CE2-3758 ([15b6a89](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/15b6a89))
* fix DatePicker & NumberField style regressions - CE2-3757, CE2-3760 ([1e23a45](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1e23a45))
* fix numberfield readonly styling - CE2-3760 ([ccb04d4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/ccb04d4))
* override 8.4.0 styling for buttons in a form - CE2-3767 ([397d5a7](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/397d5a7))
* primitive and formfield styling lost CE2-3738 ([91f2be1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/91f2be1))






# [9.4.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.3.0&sourceBranch=refs%2Ftags%2Fv9.4.0) (2019-07-10)


### Bug Fixes

* fix select box error styling - CE2-3145 ([36af689](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/36af689))
* **kyber-components:** fix selectbox dropdown collision - CE2-3213 ([19f6b4d](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/19f6b4d))
* allow relative positioning for backlink - CE2-2943 ([7775951](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/7775951))
* fix selectbox stealing focus from other elements on page - CE2-3647 ([991a2db](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/991a2db))
* handle tree change and onBranchClick CE2-3582 CE2-3487 ([c491934](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/c491934))
* make crouton close styles more specific ([8d8bcfe](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8d8bcfe))
* remove ProgressTracker circular dependency warning CE2-3544 ([1833189](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1833189))
* removed check blocking selectbox prop updates - CE2-3579 ([48e38c5](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/48e38c5))
* **kyber-components:** table HOC checks for false child CE2-3626 ([e94b333](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/e94b333))
* **kyber-components:** table HOC checks for false child CE2-3626 ([9f164ba](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/9f164ba))
* **kyber-components:** traverse full Table for TableRowToggle CE2-3724 ([1e37e72](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1e37e72))


### Features

* **kyber-components:** withObjectMapping SelectBox HOC CE2-3214 ([6162709](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/6162709))
* add Modal classes prop to support microphone styling CE2-3704 ([8bb8597](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8bb8597))
* extend form footer customization CE2-3619 ([8d950fc](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8d950fc))
* generate a css file instead of embedding styles CE2-3716 ([3f6465c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3f6465c))
* include HOCs as part of rollup build  CE2-3594 ([5fe94f2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/5fe94f2))
* onDismiss callback for AutoDismissableAlert CE2-3013 ([268884f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/268884f))






## [9.3.2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.3.1&sourceBranch=refs%2Ftags%2Fv9.3.2) (2019-07-09)


### Bug Fixes

* **kyber-components:** traverse full Table for TableRowToggle CE2-3724 ([1e37e72](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1e37e72))






## [9.3.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.3.0&sourceBranch=refs%2Ftags%2Fv9.3.1) (2019-06-25)


### Bug Fixes

* **kyber-components:** table HOC checks for false child CE2-3626 ([e94b333](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/e94b333))






# [9.3.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.2.0&sourceBranch=refs%2Ftags%2Fv9.3.0) (2019-06-06)


### Bug Fixes

* CE2-2670 - ListGroupMobile selected text change on prop update ([a36cf48](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a36cf48))
* **kyber-components:** only set fixed button width when loading CE2-2767 ([7558536](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/7558536))
* **kyber-components:** padding on loading StatusButton CE2-3514 ([1a1f450](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1a1f450))
* **kyber-components:** resize StatusButton when text changes CE2-2767 ([d6ed47c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/d6ed47c))
* fix datepicker date shift onclick - CE2-2559 ([b797026](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b797026))


### Features

* **primitives:** create kyber primitives package ([54855ec](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/54855ec))
* CE2-3065 - upgrade to React 16 ([b4c7c3d](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/b4c7c3d))
* upgrade to babel 7 ([f1bcbd5](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f1bcbd5))






# [9.2.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.0.0&sourceBranch=refs%2Ftags%2Fv9.2.0) (2019-05-02)

### Bug Fixes

-   **kyber-components:** apply ProgressTracker anchor styles to buttons ([9425c20](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/9425c20))
-   manually focus breadcrumb item for safari ([8e45430](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8e45430))
-   **kyber-components:** CE2-3295 - resolve error when no search results ([389f4a9](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/389f4a9))
-   **kyber-components:** CE2-3403 - fix selectbox background color ([05b73fb](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/05b73fb))

### Code Refactoring

-   CE2-2958 - Refactor Tabs ([1dfd363](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1dfd363))
-   CE2-3162 - create TabNav component to handle tab bar ([1e94011](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1e94011))

### Features

-   **kyber-components:** add collapsible state management to table hoc ([a9ba275](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a9ba275))
-   **kyber-components:** adjust TableRowToggle icons CE2-2704 ([e14b115](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/e14b115))
-   **kyber-components:** new TableCells add bottom margin CE2-2533 ([bad0b48](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/bad0b48))
-   add isSubmitting prop for Form CE2-3345 ([a0b3851](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a0b3851))
-   CE2-2691 add render prop for ListGroup option ([823268c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/823268c))
-   CE2-2958 - Add backwards compatibility Tabs wrapper ([911ff2f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/911ff2f))
-   CE2-3401 - upgrade kyber-fonts to include folder-addepar icon ([ac99560](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/ac99560))
-   new Icon component CE2-1737 ([65a403d](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/65a403d))

### BREAKING CHANGES

-   Tabs API has changed and become stateless. Review the docs for more details
-   Tab changed from a tag to button. Id is required prop
    now and title is no longer used.

## [9.0.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.0.0-beta.6&sourceBranch=refs%2Ftags%2Fv9.0.1) (2019-03-27)

### Features

-   jsconfigs for vscode usage ([def00aa](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/def00aa))

# [9.1.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.0.0&sourceBranch=refs%2Ftags%2Fv9.1.0) (2019-04-16)

### Bug Fixes

-   **kyber-components:** CE2-3295 - fix search dropdown text wrapping ([e55ed24](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/e55ed24))
-   **kyber-components:** CE2-3295 - fix search styling for no results ([0548361](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/0548361))
-   **kyber-components:** CE2-3295 - resolve error when no search results ([389f4a9](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/389f4a9))
-   **kyber-components:** fix no results message styling ([e52d6f1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/e52d6f1))

### Features

-   add multiselect to nonsearchable SelectBox (CE2-3186) ([7ca3b95](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/7ca3b95))
-   jsconfigs for vscode usage ([def00aa](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/def00aa))
-   web component support for SelectBox, CE2-2519 ([376753c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/376753c))
-   CE2-3263 use rollup to create esm components ([0b883af](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/0b883af))

### BREAKING CHANGES

-   table and related components require strict composition see [migration guide](https://confluence.bisenterprises.com/x/ey0yBg)

## [9.0.1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv9.0.0&sourceBranch=refs%2Ftags%2Fv9.0.1) (2019-04-02)

### Bug Fixes

-   CE2-3306 - add missing export for withDataLoader helper ([326b810](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/326b810))

# [9.0.0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/compare/diff?targetBranch=refs%2Ftags%2Fv8.3.0&sourceBranch=refs%2Ftags%2Fv9.0.0) (2019-03-27)

### Bug Fixes

-   add children prop to DropdownItem proptypes ([370b781](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/370b781))
-   added missing context type to FieldValidator and validate CE2-3096 ([a0dc994](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a0dc994))
-   aria-current should be set to string true ([932a8a4](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/932a8a4))
-   change Keydown to KeyDown ([cc43749](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/cc43749))
-   curry Switch onBlur handler to pass value in opts CE2-3096 ([742d95c](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/742d95c))
-   div needs tabIndex to fire focus CE2-3277 ([784a122](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/784a122))
-   don't exit develop builds on ESLint errors ([91b2834](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/91b2834))
-   fix dropdown styles, tab behavior, and toggling multiple prop ([1e0bd5e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/1e0bd5e))
-   FocusManager is going to need those event handler props ([87fd4c0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/87fd4c0))
-   hidden SmartFields should not validate or include value. CE2-3160 ([046cf44](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/046cf44))
-   omit invalid html attributes from SearchField ([d307d37](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/d307d37))
-   prevent clash between formatter prop and argument ([77076c0](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/77076c0))
-   prevent default backspace behavior in CroutonBar ([aae80fc](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/aae80fc))
-   remove lingering 'this' reference ([8186ec9](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8186ec9))
-   remove nested ternary and add check if expanded ([5b02a83](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/5b02a83))
-   remove old lodash import ([8730363](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8730363))
-   remove style defintions from less variables ([4741762](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4741762))
-   remove usages of dotless formatstring ([089f09a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/089f09a))
-   search onDropDOwnClick prop misnamed ([09f5dfd](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/09f5dfd))
-   switch styles for checked and disabled ([03a57c6](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/03a57c6))
-   temporarily disable the duplicate BarChart export ([dc91573](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/dc91573))

### Code Refactoring

-   remove deprecated props from DropdownItem ([5e963a2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/5e963a2))

### Features

-   add and configure speed-measure-webpack-plugin ([f9011f2](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/f9011f2))
-   add config files from `kyber` ([06708ef](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/06708ef))
-   add Crouton component ([8745870](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8745870))
-   add CroutonBar component. CE2-3116 ([4c59105](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4c59105))
-   add multiselect functionality to SelectBox (CE2-3114) ([e6fa0eb](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/e6fa0eb))
-   add react-router-dom to dependencies ([8790524](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8790524))
-   add support for flipping tooltip ([8d26cd6](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8d26cd6))
-   allow dropdown-selectbox height to grow ([3a3877e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3a3877e))
-   copy config files from `kyber-charts` ([3120775](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3120775))
-   enable js sourcemaps ([34a7be8](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/34a7be8))
-   functioning webpack build of `kyber-components` ([544331b](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/544331b))
-   implement sequencing in SelectBox ([4c9fea1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4c9fea1))
-   import `kyber-component` styles into `kyber` ([6a60d0a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/6a60d0a))
-   move alias back to babelrc so it works with jest ([4a6138e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/4a6138e))
-   move arrow and close button to top right ([92a1272](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/92a1272))
-   move component less files ([cf3455a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/cf3455a))
-   move components and tests down one level to `components` directory ([3649e3d](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/3649e3d))
-   move components from `packages/kyber/src/components` to `kyber-components/src` ([7443d98](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/7443d98))
-   move dependencies ([2c96710](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/2c96710))
-   move exports ([0ab5423](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/0ab5423))
-   move flowconfig ([064504a](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/064504a))
-   move jsdom settings ([702d057](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/702d057))
-   move progress.less to be with other less files ([a97f57e](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/a97f57e))
-   move tests from `packages/kyber/test/components` to `pakcages/kyber-components/test` ([941202f](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/941202f))
-   move utils from `kyber` to `kyber-components` ([20b9acd](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/20b9acd))
-   output kyber-components css file with build ([8e0c9ea](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/8e0c9ea))
-   update components and tests to use new alias ([71a30b1](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/71a30b1))
-   use css modules ([5cdb103](https://github.com/bisenterprises.com/projects/APPDEV/repos/kyber/commits/5cdb103))

### BREAKING CHANGES

-   href and children props are no longer supported on DropdownItem
