<!-- Automatically generated by spec-parser v2.5.0 on 2024-08-10T18:46:28.607668+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# obsoletedBy

## Summary

Specifies the licenseId that is preferred to be used in place of a deprecated
License or LicenseAddition.


## Description

An obsoletedBy value for a deprecated License or LicenseAddition specifies
the licenseId of the replacement License or LicenseAddition that is preferred
to be used in its place. It should use the same format as specified for a
licenseId.

The License's or LicenseAddition's comment value may include more information
about the reason why the licenseId specified in the obsoletedBy value is
preferred.


## Metadata

`https://spdx.org/rdf/3.0.1/terms/ExpandedLicensing/obsoletedBy`


| | |
|---|---|
| Name | obsoletedBy |
| Nature | DataProperty |
| Range | xsd:string |




## Referenced

- [/ExpandedLicensing/License](../../ExpandedLicensing/Classes/License.md)
- [/ExpandedLicensing/LicenseAddition](../../ExpandedLicensing/Classes/LicenseAddition.md)

