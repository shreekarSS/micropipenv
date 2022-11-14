# Changelog for Thoth's micropipenv

## Release 0.1.1 (2022-11-14T16:02:16)
* a7addcb test
* 564a8d8 Update OWNERS
* 0f84210 Update README.rst
* 74ecfec Update .thoth.yaml
* 5c468bd Adding myself (Max Gautier) as maintainer
* cdc0862 Release 1.4.3
* 4f9ba46 Fix compatibility with pip==22.3
* 111d690 Improve handling on poetry source type = "legacy"
* 474f623 Test with pip==22.2.2
* 952d59b :arrow_up: update ci config
* f05f19b Test with pip==22.2.1
* 03a4e96 Remove duplicates of the LICENSE file and use newer setuptools
* 414e338 Fix small typo in README.rst
* 4ee82dc Release 1.4.1
* 7084bdc Fix a problem with extras_require and environment markers
* 2127293 Release 1.4.0
* d414da9 Update tests for Python 3.11 and tomllib from stdlib
* e6fb8ad Support the latest release of pip (22.2)
* ec11e10 Add Python 3.11 into classifiers
* 925f036 Add Python 3.11 to the CI
* cff6962 Use tomllib from the standard library on Python 3.11+
* b357323 Release 1.3.2
* e172b52 pip 22.2 will no longer support deprecated html5lib backend
* bd14e06 Fix regression for VCS requirements with ref and add some tests
* b7166f8 Release 1.3.1
* 94dbc6c One of the tests needs newer pip with support for PEP 600
* 4455aef Update supported pip version
* f29508b Fix support for subdirectories in VCS requirements
* e6a927b :sparkles: update the copyright
* 77658d0 Test with pip==22.1
* dbc5d03 Update pre-commit container image
* 21f5eaf Version 1.3.0
* fc812c8 Update pre-commit
* 16f0566 Improve error message about invalid categories and test it.
* dde5854 Improve poetry → requirements and handling of transitive deps
* 038a32e Improve handling of poetry → requirements
* bcec97b reuse installed python version string
* 17d37b6 Extract poetry python version check to a function
* 6c478b5 s/check/verify
* aef9a3a Add latest pip release (22.0.4) to _SUPPORTED_PIP_STR
* 732a745 Add `check` subcommand to validate lockfiles
* d87774d Improved testing of markers
* 19a9ba5 Implement correct handling for "extras" marker from poetry.lock
* eaf6ffe New test misses `mark.online` decorator
* 93ec4de Fix pip version mentioned in the CHANGELOG
* 4d94837 Version 1.2.1
* 136743b Python 3.6 is not supported by pip >= 22
* 4a1c4fb Test with pip==22.0.3
* 29546e7 Fix trailing whitespace in setup.cfg
* 30cb85e Pin older setuptools for pip 9
* 1eb49a9 Add tests for invalid TOML files
* 0a6e8b3 Switch from git:// to https:// for links to VCS
* 5400a49 Handle differences between TOML backends
* 75a12f7 Test with tomli
* d0c37c1 Use setup.cfg (#213)
* 72407d4 Version 1.2.0 (#211)
* ede5dc4 Add Python 3.10 to trove classifiers (#212)
* a6aa43a Update micropipenv.py
* 7b61d08 Implement warning to make users aware of the missing check
* f7d82d6 Add a test for the path formats we support
* 335ef42 Check that the local dependency can be installed
* cee4c4e Support directory-based dependencies
* 8b4ec67 Fix typo in an error message reported
* e05eacb Drop Python 3.6 & pip master branch combo from tests
* 419b81d updating to https routes for pre-commit
* ad49190 New flexmock does not support module-level import
* 92dc118 Test with pip==21.3.1
* 36c1725 Version 1.1.3
* a78e111 Refactor automatic method discovery to a function
* 30257b8 Perform method discovery for requirements sub-command
* af446ea Use newer requests in tests, 1.0.0 is not compatible with Py 3.10
* 0e03e73 The oldest pip does not work with Python 3.10
* 8606ade Test with latest pip and refresh CI config
* d93f14c Fix subcommand in the README
* 917f822 Version 1.1.2
* 10fa04e Add type annotation for category which might also be None
* 1521d06 Fix markers handling for no-dev/no-default options
* c032484 For _poetry2pipfile_lock, test also all no_dev, no_default combos
* 97f3894 Skip markers if dependency is requested at least once without them
* 5ef5ffc Add missing test - poetry_markers_transitive_deps
* 637c2ee Version 1.1.1
* 0cff7fa Reformat decorators with Black
* a83f3ad Use a little bit stricker types
* 94509bf Test with the latest pip version
* 75a3d77 Implement poetry markers for dependencies
* 09bb65c Implement PEP 503 package name normalization
* bad4fbd Allow to run tests without pip version to check
* 747ad1a Test with pip==21.1.3
* 4f4fba4 Version 1.1.0
* abf5494 Add resolving enviroment variables in Pipfile URL. (#178)
* 1469101 Set development status trove classifier to production/stable (#180)
* c757761 Adjust copyright in headers (#179)
* 020c503 Test with pip==21.1.2 (#176)
* c1d6064 Add CI use case of micropipenv (#175)
* b34e81a Run mypy only once in a specific tox environment  (#172)
* aa4d161 :robot: ci updates include prow, aicoe-ci and pre-commit (#173)
* c5de3bb Add a link to article published on developers.redhat.com
* 2d80b34 Ignore types for stuff imported from pip
* 73b9243 Test check_pip_version with the pip from the venv
* f7fddf3 Fix typing error reported by mypy
* c03373c Test with pip<=21.1.1
* 87bd18e Add a helper script to prepare windows gh-action config from tox
* be1bbd4 Add Windows to CI
* ab03eb9 Version 1.0.4
* 8263abb Add a coment to explain why we need to open tmp_file twice
* 9159b5f fix: Permission error on Windows
* 7555f97 Adjust copyright notice in README
* 43dc898 Version 1.0.3
* 88ed75d Provide ability to pass pip path in install
* 537df19 Test with pip==21.0.1 (#156)
* bccd4ee Migrate CI from Travis to Github Actions (#154)
* ef5e5f3 Test with pip==21.0 (#153)
* deed020 State how to enable micropipenv in s2i container images (#152)
* 8b95277 Add a link to RPM package (#150)
* 754c7ba Version 1.0.2 (#147)
* bcab3a7 Test with pip==20.3.1 (#146)
* 2962d3e :hatching_chick: Allow aicoe-ci to do only tox and precommit checks (#145)
* 5abddd8 Test against pip==20.3 (#144)
* f3de12f bump python version (#142)
* 1e014bb Support Python versions with multiple digits (#141)
* 5921555 Version 1.0.1 (#140)
* 4700692 Make the installation log prettier (#139)
* c32f973 Fix testsuite (#137)
* fe145fa Link to Thoth's homepage in the README file
* b457072 Test against 20.2.4 (#135)
* 47933d3 State TDS article
* 879c66f Version 1.0.0 (#131)
* 0ecd2e5 Test using pip==20.2.3 (#129)
* 5689195 Version 0.6.0
* c2a6fd0 Produce error message if any issue is raised during pip imports (#124)
* 06cdacd Drop Python 3.5 support (#128)
* 2e7c872 Produce pip compatibility warning only on issues (#121)
* 993cc13 :pushpin: Automatic update of dependency pip from 20.1.1 to None (#127)
* 22fc4b5 Test micropipenv against pip from the master branch (#122)
* 13e1ed3 Remove unused imports from setup.py (#119)
* 560c43c Version 0.5.3
* 767b65a Test against pip==20.2.2 (#118)
* fa32452 Enable Thoth integration for automatic pip updates
* 4c9d803 Version 0.5.2
* 2d2592c Test against pip 20.2.1 (#115)
* 9195698 Add pip version compatibility check (#114)
* 9c6d43d Version 0.5.1
* 951ff06 Add notes to CHANGELOG
* 5cc0528 Add OWNERS file for Prow
* 05d8a34 Include pytest.ini file
* cdcc319 Print pip version to logs in a test session
* 3fc131a Skip tests automatically on missing pytest-venv
* 354881d Mark online tests with a pytest.mark.online
* 95abbf3 Version 0.5.0 (#107)
* f4884c0 Update tests/test_micropipenv.py
* c990ac3 Add test for a direct reference install
* c511940 Implement conditional test skip based on pip version
* b87756c Be more descriptive in the unpinned warning message produced
* e928e46 Add support for file spec requirements (#100)
* 3ebb9eb Version 0.4.0
* 7b2866c Pytoml support (#98)
* 5207d6c State no container technology limitation
* fbd57cc Use fedorapython/fedora-python-tox container image in CI
* 9f50191 Fix pip's latest CI test
* a9b2503 Version 0.3.0
* 8315f7d Run CI for the most latest pip
* a3a9c96 Add pip==19.2 support
* 774ae1c Raise an appropriate exception for unsupported VCS installations
* 58c64f8 Rename PIP_VERSION to MICROPIPENV_TEST_PIP_VERSION
* 80df52d Some more badges
* c37339b Extend the list of supported pip versions
* 5739db2 Add Travis CI badge
* ec178e5 Use Python as Travis CI language
* e77dbb4 Save traversals when requirements file is discovered
* a343110 Initial Travis CI configuration
* 0fff63c Version 0.2.1
* f5d01b2 Extend document string
* b1ba957 Fix OrderedDict initialization
* 00afa9f Provide LICENSE file with LGPL v3+ for GitHub
* 5a30bc2 Change relative order of license files referenced
* fad0481 Add licensing and copyright notice
* 37ffd2c Fix license declared in setup.py
* 7c0459f Do not suggest thoth-pipenv anymore
* a98a352 Add a note about available RPM packages in Fedora
* 352fb92 Version 0.2.0
* 92d6ec0 fixup! Fix automatic selection of the installation method
* 1925254 Fix automatic selection of the installation method
* fe1fe16 Run tests with multiple versions of pip
* d3714fa added a 'tekton trigger tag_release pipeline issue'
* ca56637 Fix LGPL in Python's trove classifier
* b61217f Relicensing to LGPL v3+
* d44c7d4 Remove Thoth's configuration file
* d699444 Remove __all__
* 1b1aaf5 Create pretty suffix for temporary requirements file
* fb3929f Remove thoth-pytest
* 6f46ec7 Revisit setup.py structure
* 7131c39 Add Lumir to CODEOWNERS so he can review each change
* 36f9cce Remove Pipenv files
* 1e08bfe State version constraint for pip
* 641ccd8 Use black to format sources
* 0fb7c38 Add support for pip 20+
* 0a92d12 Do not install empty editables
* ebcda8c Disable pytest-mypy on Python 3.8
* 665db10 Ignore errors when removing installation dir
* 1349519 Run micropipenv in debug mode during tests
* 0fd65f8 Version 0.1.6
* 6c19856 Reformat using black
* 4cc5442 Do not treat multiple indexes as mirrors
* 02d8a86 Update README.rst
* c040a71 Update setup.py
* 5bf317f Remove latest version restriction from .thoth.yaml
* 6d75257 Version 0.1.5
* 2619cb0 Link demos in the README
* ba98cd8 Respect index configuration when installing packages
* bf849b4 Add a test for unlocked editable requirements.txt file
* ca4dd47 Increase lines per file allowed
* 1eed3ca Be more careful when treating editables as part of a lock file
* a8fad9e Add dirty hack for pytest-mypy to ignore setup.py files
* 1557dfa Detect editables in requirements.txt when used as a lock file
* cfb6901 Fix coala complains
* 1ff09cb Add support for editable install in requirements.txt
* beaae60 Add support for editable install when Pipenv is used
* dcd33db Implement tox to test micropipenv with all supported Pythons
* f8e3c9f Produce a more descriptive message if no requirements file is found
* 39e6fcc Add pip as a dependency
* d68e7c7 Fix requirements creation when Git version of a package is used
* c3b57ac Include LICENSE file via MANIFEST.in instead of data_files in setup.py.
* f5c489d Version 0.1.4
* 27d825a Add more sections stating differences with pip, Pipenv and Poetry
* a962b92 Version 0.1.3
* a3d8212 Add LICENSE file to setup.py
* a6881dd Version v0.1.2
* 584ec3b Version 0.1.1
* a23f249 Add LICENSE file to setup.py
* 9c6d925 Fix installation from git
* 1f0097d Change discovery order of installation method
* 221cf9c Version 0.1.0
* 484d4f2 Make Poetry tests Python version agnostic
* 149b08e Update README.rst
* b61071f Update README.rst
* 29ff87e Update README.rst
* c1e296d Document example usage in the README file
* 3860eee Adjust project description
* 96250e2 Add tests for Poetry requirements parsing
* 2cb028d Fix some typos in the README file
* de81765 Extend testsuite to cover all installation methods
* c1bb5fa Assign index when Poetry is used when only one index is used
* 1a0db43 Add Poetry support
* 8e2bb3a pip and pip-tools support
* dea77ed Add period into the docstring
* 0216557 Updated zuul configuration file for the repo
* 92ca5f0 Version 0.0.4
* c8b9561 Add execute bit
* 86421af Install dependencies iterativelly with a fallback
* a1e64eb Fix testsuite - the hash computation has been fixed
* fd8bdd1 Version 0.0.3
* ac947ec Fix computing digest if no requires are specified
* 74159fc Version 0.0.2
* c780076 Run pip install with --no-deps
* 9408039 Remove unused function
* cebc2be Add URL to project
* 6f9a51a Version 0.0.1
* ac773ee State dev-requirements.{in,txt} in README
* 6fcb841 Link to pip-tools on PyPI
* f60b3a3 Add option to propagate arguments to pip options
* f61b612 Fix tests in test suite
* 6a68825 Add templates for releases
* 6094957 Remove redundant else part
* c08efbd Minor fixes in README file
* 84a026a Delete app.py
* ce4be0c Initial project import

## [1.4.3] - 2022-Oct-04 - Lumír Balhar <lbalhar@redhat.com>

### Added

* Test with pip==22.2.2

### Fixed

* Compatibility with pip==22.3 (not released yet)
* Compatibility with source type "legacy" in poetry.lock

## [1.4.2] - 2022-Aug-01 - Lumír Balhar <lbalhar@redhat.com>

### Added

* Test with pip==22.2.1

## [1.4.1] - 2022-Jul-26 - Lumír Balhar <lbalhar@redhat.com>

### Fixed

* Fixed installation of `micropipenv[toml]` see https://github.com/pypa/setuptools/issues/3467

## [1.4.0] - 2022-Jul-22 - Lumír Balhar <lbalhar@redhat.com>

### Added

* Test with pip==22.2
* Python 3.11 is now officially supported and tested
* Use tomllib from standard libraty for Python 3.11+


## [1.3.2] - 2022-Jul-21 - Lumír Balhar <lbalhar@redhat.com>

### Fixed

* Fixed regression caused by misplaced newline character in VCS requirement.
* Preps for pip 22.2 where PackageFinder will no longer support deprecated html5lib.

## [1.3.1] - 2022-Jul-15 - Lumír Balhar <lbalhar@redhat.com>

### Fixed

* Fixed support for subdirectories in VCS requirements

### Added

* Test with pip==22.1.2

## [1.3.0] - 2022-May-09 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Improve poetry → requirements and handling of transitive deps
  Contribution thanks to @frenzymadness

* Add check subcommand to validate lockfiles
  Contribution thanks to @matt-carr

* Test with pip==22.0.4

### Fixes

* Implement correct handling for "extras" marker from poetry.lock
  Contribution thanks to @frenzymadness

## [1.2.1] - 2022-February-21 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Test with pip==22.0.3

* Add tomli support
  Contribution thanks to @frenzymadness

## [1.2.0] - 2021-December-06 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* micropipenv is no longer tested with Python 3.6 and development pip
  Contribution thanks to @frenzymadness

* Support directory-based dependencies
  Contribution thanks to @abompard

* micropipenv warns users if they use Poetry lockfiles and Python
  version is not checked by micropipenv
  Contribution thanks to @frenzymadness

## [1.1.3] - 2021-October-20 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Perform method discovery for requirements sub-command as documented
  Fix thanks to @frenzymadness, issue reported by @hanjos

## [1.1.2] - 2021-October-05 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Fix handling Poetry environment markers for direct dependencies #192
  Fix thanks to @frenzymadness, issue reported by @abompard
* Fix handling Poetry environment markers for `--no-default` and `--no-dev` options #193
  Fix thanks to @frenzymadness, issue reported by @macarr

## [1.1.1] - 2021-September-21 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Test with pip<=21.2.4
* Fix Poetry environment markers handling #188
  Fix thanks to @frenzymadness, issue reported by @wjhrdy

## [1.1.0] - 2021-Jun-21 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Add resolving enviroment variables in Pipfile URL
  thanks to @Misoslav and @frenzymadness
* Test with pip<=21.1.2
* Tests are now executed on Windows as well
  thanks to @frenzymadness

## [1.0.4] - 2021-April-29 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Fix permission error on Windows
  thanks to Julien Rottenberg (@jrottenberg)

## [1.0.3] - 2021-March-10 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Test with pip==20.0.1
* Test with pip==20.0
* Provide ability to pass pip path in install

## [1.0.2] - 2020-December-10 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Test with pip==20.3
* Test with pip==20.3.1

## [1.0.1] - 2020-November-09 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Make the installation log prettier
* Test with pip==20.2.4

## [1.0.0] - 2020-October-01 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* First major release
* Tested with pip==20.2.3

## [0.6.0] - 2020-September-03 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Produce error message if any issue is raised during pip imports (#124)
* Produce pip compatibility warning only on issues (#121)
* Test micropipenv against pip from the master branch (#122)

### Other

* Drop Python 3.5 support (#128)

## [0.5.3] - 2020-August-18 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Test against pip==20.2.2

## [0.5.2] - 2020-August-05 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Test against pip==20.2.1

## [0.5.1] - 2020-Jul-30 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Improvements in the test suite for online tests and different environments
  setup

## [0.5.0] - 2020-Jul-23 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Add support for a direct reference install using Pipenv and requirements.txt file
  thanks to Tomáš Coufal <tcoufal@redhat.com> for Pipenv support

* More descriptive warning message in the unpinned warning message

## [0.4.0] - 2020-Jul-07 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Added pytoml support needed for Red Hat Enterprise Linux
  thanks to Lumir 'Frenzy' Balhar <lbalhar@redhat.com>

## [0.3.0] - 2020-Jun-12 - Fridolin Pokorny <fridolin@redhat.com>

### Added

* Added support for pip in version >=19.2<20
* Introduced NotSupportedError exception raised when Mercurial, Subversion or
  Bazaar VCS are used
* Optimized traversals when requirements file is looked up
* Improvements in test-suite, now testing support matrix
  thanks to Lumir 'Frenzy' Balhar <lbalhar@redhat.com>

## [0.2.1] - 2020-Jun-9 - Fridolin Pokorny <fridolin@redhat.com>

### Fixes

* Fixed priority in lock files discovered
  thanks to Lumir 'Frenzy' Balhar <lbalhar@redhat.com>

### Docs

* Improved project documentation

## [0.2.0] - 2020-Jun-4 - Fridolin Pokorny <fridolin@redhat.com>

### Fixes
* Fixed automatic selection of desired installation method (not backwards
  compatible change, might break installations)

### Other

* Improved test suite, the test suite now considers a matrix of Python
  interpreter versions and different pip versions
* Relicensed to LGPL 3+

### Added

* Added support for pip in version 20

## [0.0.0] - 2020-Feb-10 - Fridolin Pokorny <fridolin@redhat.com>

### Added

Initial project import
