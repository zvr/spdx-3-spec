<!-- Automatically generated by spec-parser v2.0.0 on 2024-01-26T22:18:46.241893+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# WithAdditionOperator

## Summary

Portion of an AnyLicenseInfo representing a License which has additional
text applied to it.


## Description

A WithAdditionOperator indicates that the designated License is subject to the
designated LicenseAddition, which might be a license exception on the SPDX
Exceptions List (ListedLicenseException) or may be other additional text
(CustomLicenseAddition). It is represented in the SPDX License Expression
Syntax by the `WITH` operator.


## Metadata

`https://rdf.spdx.org/v3/ExpandedLicensing/WithAdditionOperator`


| | |
|---|---|
| Name | WithAdditionOperator |
| Instantiability | Concrete |
| SubclassOf | [/SimpleLicensing/AnyLicenseInfo](../../SimpleLicensing/Classes/AnyLicenseInfo.md) |




## Properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [subjectAddition](../Properties/subjectAddition.md) | [LicenseAddition](../Classes/LicenseAddition.md) | 1 | 1 |
| [subjectLicense](../Properties/subjectLicense.md) | [ExtendableLicense](../Classes/ExtendableLicense.md) | 1 | 1 |

