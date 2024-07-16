<!-- Automatically generated by spec-parser v2.3.0 on 2024-07-16T15:00:52.540788+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# suppliedBy

## Summary

Identifies who or what supplied the artifact or VulnAssessmentRelationship
referenced by the Element.


## Description

Identify the actual distribution source for the artifact (e.g., snippet, file,
package, vulnerability) or VulnAssessmentRelationship being referenced.

This might or might not be different from the originating distribution source
for the artifact (e.g., snippet, file, package, vulnerability) or
VulnAssessmentRelationship.


## Metadata

`https://spdx.org/rdf/3.0.0/terms/Core/suppliedBy`


| | |
|---|---|
| Name | suppliedBy |
| Nature | ObjectProperty |
| Range | [Agent](../Classes/Agent.md) |




## Referenced

- [/Core/Artifact](../../Core/Classes/Artifact.md)
- [/Security/VulnAssessmentRelationship](../../Security/Classes/VulnAssessmentRelationship.md)
