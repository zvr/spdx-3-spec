<!-- Automatically generated by spec-parser v2.0.0 on 2024-01-26T22:18:46.241893+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# VexVulnAssessmentRelationship

## Summary

Asbtract ancestor class for all VEX relationships


## Description

VexVulnAssessmentRelationship is an abstract subclass that defined the common
properties shared by all the SPDX-VEX status relationships. 

**Constraints**

When linking elements using a VexVulnAssessmentRelationship, the following
requirements must be observed:

- The from: end must be a /Security/Vulnerability classed element
- The to: end must point to elements representing the VEX _products_. To
specify a different element where the vulnerability was detected, the VEX
relationship can optionally specify _subcomponents_ using the assessedElement
property.

VEX inherits information from the document level down to its statements. When a
statement is missing information it can be completed by reading the equivalent 
field from the containing document. For example, if a VEX relationship is
missing data in its createdBy property, tools must consider the entity
listed in the CreationInfo section of the document as the VEX author.
In the same way, when a VEX relationship does not have a created property,
the document's date must be considered as authoritative.


## Metadata

`https://rdf.spdx.org/v3/Security/VexVulnAssessmentRelationship`


| | |
|---|---|
| Name | VexVulnAssessmentRelationship |
| Instantiability | Abstract |
| SubclassOf | [VulnAssessmentRelationship](../Classes/VulnAssessmentRelationship.md) |




## Properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [statusNotes](../Properties/statusNotes.md) | xsd:string | 0 | 1 |
| [vexVersion](../Properties/vexVersion.md) | xsd:string | 0 | 1 |

