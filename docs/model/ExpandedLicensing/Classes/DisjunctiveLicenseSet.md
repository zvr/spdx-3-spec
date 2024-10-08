<!-- Automatically generated by spec-parser v2.5.0 on 2024-08-10T18:46:28.607668+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# DisjunctiveLicenseSet

## Summary

Portion of an AnyLicenseInfo representing a set of licensing information where
only one of the elements applies.


## Description

A DisjunctiveLicenseSet indicates that _only one_ of its subsidiary
AnyLicenseInfos is required to apply. In other words, a DisjunctiveLicenseSet
of two or more licenses represents a licensing situation where _only one_ of
the specified licenses are to be complied with.

A consumer of SPDX data would typically understand this to permit the recipient
of the licensed content to choose which of the corresponding license they would
prefer to use. It is represented in the SPDX License Expression Syntax by the
`OR` operator.


## Metadata

`https://spdx.org/rdf/3.0.1/terms/ExpandedLicensing/DisjunctiveLicenseSet`


| | |
|---|---|
| Name | DisjunctiveLicenseSet |
| Instantiability | Concrete |
| SubclassOf | [/SimpleLicensing/AnyLicenseInfo](../../SimpleLicensing/Classes/AnyLicenseInfo.md) |


## Superclasses

* [/SimpleLicensing/AnyLicenseInfo](../../SimpleLicensing/Classes/AnyLicenseInfo.md)
* [/Core/Element](../../Core/Classes/Element.md)




## Properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [member](../Properties/member.md) | [/SimpleLicensing/AnyLicenseInfo](../../SimpleLicensing/Classes/AnyLicenseInfo.md) | 2 | * |



## All properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [comment](../../Core/Properties/comment.md) | xsd:string | 0 | 1 |
| [creationInfo](../../Core/Properties/creationInfo.md) | [CreationInfo](../../Core/Classes/CreationInfo.md) | 1 | 1 |
| [description](../../Core/Properties/description.md) | xsd:string | 0 | 1 |
| [extension](../../Core/Properties/extension.md) | [Extension](../../Extension/Classes/Extension.md) | 0 | * |
| [externalIdentifier](../../Core/Properties/externalIdentifier.md) | [ExternalIdentifier](../../Core/Classes/ExternalIdentifier.md) | 0 | * |
| [externalRef](../../Core/Properties/externalRef.md) | [ExternalRef](../../Core/Classes/ExternalRef.md) | 0 | * |
| [member](../../ExpandedLicensing/Properties/member.md) | [AnyLicenseInfo](../../SimpleLicensing/Classes/AnyLicenseInfo.md) | 2 | * |
| [name](../../Core/Properties/name.md) | xsd:string | 0 | 1 |
| [spdxId](../../Core/Properties/spdxId.md) | xsd:anyURI | 1 | 1 |
| [summary](../../Core/Properties/summary.md) | xsd:string | 0 | 1 |
| [verifiedUsing](../../Core/Properties/verifiedUsing.md) | [IntegrityMethod](../../Core/Classes/IntegrityMethod.md) | 0 | * |



