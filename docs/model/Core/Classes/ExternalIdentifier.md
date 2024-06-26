<!-- Automatically generated by spec-parser v2.1.0 on 2024-06-17T15:44:58.460830+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# ExternalIdentifier

## Summary

A reference to a resource identifier defined outside the scope of SPDX-3.0 content that uniquely identifies an Element.


## Description

An ExternalIdentifier is a reference to a resource outside the scope of SPDX-3.0 content
that provides a unique key within an established domain that can uniquely identify an Element.


## Metadata

`https://spdx.org/rdf/3.0.0/terms/Core/ExternalIdentifier`


| | |
|---|---|
| Name | ExternalIdentifier |
| Instantiability | Concrete |






## Properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [comment](../Properties/comment.md) | xsd:string | 0 | 1 |
| [externalIdentifierType](../Properties/externalIdentifierType.md) | [ExternalIdentifierType](../Vocabularies/ExternalIdentifierType.md) | 1 | 1 |
| [identifier](../Properties/identifier.md) | xsd:string | 1 | 1 |
| [identifierLocator](../Properties/identifierLocator.md) | xsd:anyURI | 0 | * |
| [issuingAuthority](../Properties/issuingAuthority.md) | xsd:string | 0 | 1 |


