<!-- Automatically generated by spec-parser v2.3.0 on 2024-07-09T12:43:38.633388+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# licenseExpression

## Summary

A string in the license expression format.


## Description

A licenseExpression enables the representation, in a single string, of a
combination of one or more licenses, together with additions such as license
exceptions.

The syntax for a LicenseExpression string is set forth in the Annex D
of the SPDX Specification ("SPDX license expressions"). A LicenseExpression string is
not valid if it does not conform to the grammar set forth in that annex.

The ExpandedLicensing profile can be used to represent the complete parsed
license expression as a combination of license objects.


## Metadata

`https://spdx.org/rdf/3.0.0/terms/SimpleLicensing/licenseExpression`


| | |
|---|---|
| Name | licenseExpression |
| Nature | DataProperty |
| Range | xsd:string |




## Referenced

- [/SimpleLicensing/LicenseExpression](../../SimpleLicensing/Classes/LicenseExpression.md)
