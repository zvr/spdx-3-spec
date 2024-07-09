<!-- Automatically generated by spec-parser v2.3.0 on 2024-07-09T12:43:38.633388+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# AnyLicenseInfo

## Summary

Abstract class representing a license combination consisting of one or more
licenses (optionally including additional text), which may be combined
according to the SPDX license expression syntax.


## Description

An AnyLicenseInfo is used by licensing properties of software artifacts.
It can be a NoneLicense, a NoAssertionLicense,
single license (either on the SPDX License List or a custom-defined license);
a single license with an "or later" operator applied; the foregoing with
additional text applied; or a set of licenses combined by applying "AND" and
"OR" operators recursively.


## Metadata

`https://spdx.org/rdf/3.0.0/terms/SimpleLicensing/AnyLicenseInfo`


| | |
|---|---|
| Name | AnyLicenseInfo |
| Instantiability | Abstract |
| SubclassOf | [/Core/Element](../../Core/Classes/Element.md) |


## Superclasses

* [/Core/Element](../../Core/Classes/Element.md)






## All properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [comment](../../Core/Properties/comment.md) | xsd:string | 0 | 1 |
| [creationInfo](../../Core/Properties/creationInfo.md) | [CreationInfo](../../Core/Classes/CreationInfo.md) | 1 | 1 |
| [description](../../Core/Properties/description.md) | xsd:string | 0 | 1 |
| [extension](../../Core/Properties/extension.md) | [Extension](../../Extension/Classes/Extension.md) | 0 | * |
| [externalIdentifier](../../Core/Properties/externalIdentifier.md) | [ExternalIdentifier](../../Core/Classes/ExternalIdentifier.md) | 0 | * |
| [externalRef](../../Core/Properties/externalRef.md) | [ExternalRef](../../Core/Classes/ExternalRef.md) | 0 | * |
| [name](../../Core/Properties/name.md) | xsd:string | 1 | 1 |
| [spdxId](../../Core/Properties/spdxId.md) | xsd:anyURI | 1 | 1 |
| [summary](../../Core/Properties/summary.md) | xsd:string | 0 | 1 |
| [verifiedUsing](../../Core/Properties/verifiedUsing.md) | [IntegrityMethod](../../Core/Classes/IntegrityMethod.md) | 0 | * |


