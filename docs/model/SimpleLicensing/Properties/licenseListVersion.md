<!-- Automatically generated by spec-parser v2.5.0 on 2024-08-10T18:46:28.607668+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# licenseListVersion

## Summary

The version of the SPDX License List used in the license expression.


## Description

Recognizing that licenses are added to the
[SPDX License List](https://spdx.org/licenses/) with each
subsequent version, the intent is to provide consumers with the version of the
SPDX License List used.

This anticipates that in the future, license expression might have used a
version of the SPDX License List that is older than the then current one.

The specified version of the SPDX License List must include all listed licenses
and exceptions referenced in the expression.


## Metadata

`https://spdx.org/rdf/3.0.1/terms/SimpleLicensing/licenseListVersion`


| | |
|---|---|
| Name | licenseListVersion |
| Nature | DataProperty |
| Range | [/Core/SemVer](../../Core/Datatypes/SemVer.md) |




## Referenced

- [/SimpleLicensing/LicenseExpression](../../SimpleLicensing/Classes/LicenseExpression.md)

