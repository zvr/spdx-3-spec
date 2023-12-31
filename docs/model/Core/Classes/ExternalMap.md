<!-- Automatically generated by spec-parser v2.0.0 on 2024-01-08T22:20:56.273795+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# ExternalMap

## Summary

A map of Element identifiers that are used within a Document but defined external to that Document.


## Description

An External Map is a map of Element identifiers that are used within a Document
but defined external to that Document.
The external map provides details about the externally-defined Element
such as its provenance, where to retrieve it, and how to verify its integrity.


## Metadata

- Instantiability: Concrete
- name: ExternalMap



## Properties

| Property | Type | minCount | maxCount |
|---|---|---|---|
| [definingArtifact](../Properties/definingArtifact.md) | [Artifact](../Classes/Artifact.md) | 0 | 1 |
| [externalSpdxId](../Properties/externalSpdxId.md) | xsd:anyURI | 1 | 1 |
| [locationHint](../Properties/locationHint.md) | xsd:anyURI | 0 | 1 |
| [verifiedUsing](../Properties/verifiedUsing.md) | [IntegrityMethod](../Classes/IntegrityMethod.md) | 0 | * |

