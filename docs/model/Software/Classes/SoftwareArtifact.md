<!-- Automatically generated by spec-parser v2.1.0 on 2024-06-17T15:44:58.460830+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# SoftwareArtifact

## Summary

A distinct article or unit related to Software.


## Description

A software artifact is a distinct article or unit related to software
such as a package, a file, or a snippet.


## Metadata

`https://spdx.org/rdf/3.0.0/terms/Software/SoftwareArtifact`


| | |
|---|---|
| Name | SoftwareArtifact |
| Instantiability | Abstract |
| SubclassOf | [/Core/Artifact](../../Core/Classes/Artifact.md) |


## Superclasses

* [/Core/Artifact](../../Core/Classes/Artifact.md)
* [/Core/Element](../../Core/Classes/Element.md)




## Properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [additionalPurpose](../Properties/additionalPurpose.md) | [SoftwarePurpose](../Vocabularies/SoftwarePurpose.md) | 0 | * |
| [attributionText](../Properties/attributionText.md) | xsd:string | 0 | * |
| [contentIdentifier](../Properties/contentIdentifier.md) | [ContentIdentifier](../Classes/ContentIdentifier.md) | 0 | * |
| [copyrightText](../Properties/copyrightText.md) | xsd:string | 0 | 1 |
| [primaryPurpose](../Properties/primaryPurpose.md) | [SoftwarePurpose](../Vocabularies/SoftwarePurpose.md) | 0 | 1 |


