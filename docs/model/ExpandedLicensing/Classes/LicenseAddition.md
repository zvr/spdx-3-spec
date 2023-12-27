<!-- Automatically generated by spec-parser v2.0.0 on 2023-12-27T15:02:03.969017+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# LicenseAddition

## Summary

Abstract class for additional text intended to be added to a License, but
which is not itself a standalone License.


## Description

A LicenseAddition represents text which is intended to be added to a License
as additional text, but which is not itself intended to be a standalone
License.

It may be an exception which is listed on the SPDX Exceptions List
(ListedLicenseException), or may be any other additional text (as an exception
or otherwise) which is defined by an SPDX data creator (CustomLicenseAddition).


## Metadata

- Instantiability: Abstract
- name: LicenseAddition
- SubclassOf: /Core/Element



## Properties

| Property | Type | minCount | maxCount |
|---|---|---|---|
| additionText | xsd:string | 1 | 1 |
| isDeprecatedAdditionId | xsd:boolean | 0 | 1 |
| licenseXml | xsd:string | 0 | 1 |
| obsoletedBy | xsd:string | 0 | 1 |
| seeAlso | xsd:anyURI | 0 | * |
| standardAdditionTemplate | xsd:string | 0 | 1 |
