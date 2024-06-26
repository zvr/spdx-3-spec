<!-- Automatically generated by spec-parser v2.1.0 on 2024-06-17T15:44:58.460830+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# LicenseExpression

## Summary

An SPDX Element containing an SPDX license expression string.


## Description

A LicenseExpression enables the representation, in a single string, of a
combination of one or more licenses, together with additions such as license
exceptions.

The syntax for a LicenseExpression string is set forth in the Annex D
of the SPDX Specification ("SPDX license expressions"). A LicenseExpression string is
not valid if it does not conform to the grammar set forth in that annex.

The ExpandedLicensing profile can be used to represent the complete parsed
license expression as a combination of license objects.


## Metadata

`https://spdx.org/rdf/3.0.0/terms/SimpleLicensing/LicenseExpression`


| | |
|---|---|
| Name | LicenseExpression |
| Instantiability | Concrete |
| SubclassOf | [AnyLicenseInfo](../Classes/AnyLicenseInfo.md) |


## Superclasses

* [/SimpleLicensing/AnyLicenseInfo](../../SimpleLicensing/Classes/AnyLicenseInfo.md)
* [/Core/Element](../../Core/Classes/Element.md)




## Properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [customIdToUri](../Properties/customIdToUri.md) | [/Core/DictionaryEntry](../../Core/Classes/DictionaryEntry.md) | 0 | * |
| [licenseExpression](../Properties/licenseExpression.md) | xsd:string | 1 | 1 |
| [licenseListVersion](../Properties/licenseListVersion.md) | [/Core/SemVer](../../Core/Datatypes/SemVer.md) | 0 | 1 |


