# Changelog

All notable changes to this project will be documented in this file.

## [1.0.9.9.1] - 2022-10-06

### Changed

- Renamed script without version number, UnRen-Linux-<version_number>.sh to UnRen-Linux.sh
- Moved version and versiondate to top of the file for easily checking version number
- Changed gamename in initial setup as it excludes the script by name, and the filename has changed to remove the version number [Line 237]
- Set x64 Python directory first, then will check others including 32bit

### Fixed

- Check if any RPA file in Game folder and advise "No RPA files found" instead of giving an Error
- Set PYTHONPATH correctly

## [1.0.9.9.0] - 2022-10-05

### Added

- Code to detect the Game script name, and the Game and Python files under the relevant LIB folder, and make them executable.
- Added all the License information as I could find and research.
- New Github repo made under MIT License as per original UnRen.bat.

### Changed

- rpatool code from UnRen-Ultrahackv9

### Fixed

- unren-skip.rpy not being created. The issue was not editing the lines when copying and pasting code so unren-skip.rpy was being overwritten by unren-rollback.rpy.

[comment]: ### Added
[comment]: ### Changed
[comment]: ### Fixed
[comment]: ### Removed
