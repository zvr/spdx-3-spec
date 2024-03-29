<!-- Automatically generated by spec-parser v2.0.0 on 2024-01-26T22:18:46.241893+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# Annotation

## Summary

An assertion made in relation to one or more elements.


## Description

An Annotation is an assertion made in relation to one or more elements. The `contentType` property describes the format of the `statement` property.


## Metadata

`https://rdf.spdx.org/v3/Core/Annotation`


| | |
|---|---|
| Name | Annotation |
| Instantiability | Concrete |
| SubclassOf | [Element](../Classes/Element.md) |




## Properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [annotationType](../Properties/annotationType.md) | [AnnotationType](../Vocabularies/AnnotationType.md) | 1 | 1 |
| [contentType](../Properties/contentType.md) | [MediaType](../Datatypes/MediaType.md) | 0 | 1 |
| [statement](../Properties/statement.md) | xsd:string | 0 | 1 |
| [subject](../Properties/subject.md) | [Element](../Classes/Element.md) | 1 | 1 |

