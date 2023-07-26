# WordPress Build Tester

This repository contains workflows for testing the installation and upgrade of a build on a variety of PHP versions.

Installation tests include jobs for:
- PHP: 7.0-8.2
- MySQL: 5.7 and 8.0
- Site Type: Single site and Multisite - Sub-directory.

Upgrade tests include jobs for:
- PHP: 7.0-8.2
- MySQL: 5.7 and 8.0
- WordPress: The earliest version receiving security updates and all versions up to the latest stable release.
- Site Type: Single site and Multisite - Sub-directory.

Workflows are triggered manually with a single input, `new_version`, containing the version string of the build.
