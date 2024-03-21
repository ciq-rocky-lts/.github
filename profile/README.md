# CIQ Long-Term Support (LTS) for Rocky Linux

Welcome to the official GitHub repository for CIQ's Long-Term Support (LTS) for Rocky Linux. Our LTS offering is designed to provide extended support for Rocky Linux versions even after they have been declared End-Of-Life (EOL) by the upstream rockylinux.org project.

## What We Offer

CIQ is the leading provider of Rocky Linux support, focusing on extending the lifecycle of your software infrastructure. Our services include:

- **Extended Package Updates**: For minor versions of Rocky Linux post their EOL announcement, CIQ engineers backport fixes from newer versions into the EOL releases. These updates are made available to subscribed customers via our Mountain and CIQ's Repo-As-A-Service (RaaS) repositories.

- **Supported Minor Versions and Lifecycle**: CIQ's LTS product is available for non-zero, even-numbered releases like 8.6, 8.8, 9.2, and 9.4. The standard LTS support period extends 18 months past the version's expiration date.

- **Extended LTS Option**: For those needing support beyond the standard LTS period, CIQ offers an "Extended LTS" option. Please contact us for more details.

- **Final Version Support**: CIQ also supports the final minor version of a major release cycle, providing updates for a significantly extended period, typically 5 years after the release of the last minor version.

## Security Vulnerability Policy

Our LTS program prioritizes security:

- **Critical and Important Updates**: Packages marked as Important or Critical for security from upstream may be eligible for backports, generally focusing on those with a CVSS score of 8.0 or higher.
  
- **Discretionary Backports**: Packages with a CVSS score lower than 8.0 may receive backports at CIQ's discretion, including necessary bug fixes not related to security.
- 

## Using These Repositories

The repositories contained within this organization are dist-git style repositories using a lookaside cache hosted at https://ctrliq.download/HASH where HASH is the has specified in the package *.metadata file.
