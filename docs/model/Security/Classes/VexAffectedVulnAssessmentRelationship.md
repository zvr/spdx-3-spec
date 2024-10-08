<!-- Automatically generated by spec-parser v2.5.0 on 2024-08-10T18:46:28.607668+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# VexAffectedVulnAssessmentRelationship

## Summary

Connects a vulnerability and an element designating the element as a product
affected by the vulnerability.


## Description

VexAffectedVulnAssessmentRelationship connects a vulnerability and a number of
elements. The relationship marks these elements as products affected by the
vulnerability. This relationship corresponds to the VEX affected status.

*Constraints*

When linking elements using a VexAffectedVulnAssessmentRelationship, the
following requirements must be observed:

- Elements linked with a VulnVexAffectedAssessmentRelationship are constrained
  to the affects relationship type.

*Example*

```json
{
  "type": "VexAffectedVulnAssessmentRelationship",
  "spdxId": "urn:spdx.dev:vex-affected-1",
  "relationshipType": "affects",
  "from": "urn:spdx.dev:vuln-cve-2020-28498",
  "to": ["urn:product-acme-application-1.3"],
  "security_assessedElement": "urn:npm-elliptic-6.5.2",
  "security_actionStatement": "Upgrade to version 1.4 of ACME application.",
  "suppliedBy": ["urn:spdx.dev:agent-jane-doe"],
  "publishedTime": "2021-03-09T11:04:53Z"
}
```


## Metadata

`https://spdx.org/rdf/3.0.1/terms/Security/VexAffectedVulnAssessmentRelationship`


| | |
|---|---|
| Name | VexAffectedVulnAssessmentRelationship |
| Instantiability | Concrete |
| SubclassOf | [VexVulnAssessmentRelationship](../Classes/VexVulnAssessmentRelationship.md) |


## Superclasses

* [/Security/VexVulnAssessmentRelationship](../../Security/Classes/VexVulnAssessmentRelationship.md)
* [/Security/VulnAssessmentRelationship](../../Security/Classes/VulnAssessmentRelationship.md)
* [/Core/Relationship](../../Core/Classes/Relationship.md)
* [/Core/Element](../../Core/Classes/Element.md)




## Properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [actionStatement](../Properties/actionStatement.md) | xsd:string | 0 | 1 |
| [actionStatementTime](../Properties/actionStatementTime.md) | [/Core/DateTime](../../Core/Datatypes/DateTime.md) | 0 | * |



## All properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [actionStatement](../../Security/Properties/actionStatement.md) | xsd:string | 0 | 1 |
| [actionStatementTime](../../Security/Properties/actionStatementTime.md) | [DateTime](../../Core/Datatypes/DateTime.md) | 0 | * |
| [assessedElement](../../Security/Properties/assessedElement.md) | [Element](../../Core/Classes/Element.md) | 0 | 1 |
| [comment](../../Core/Properties/comment.md) | xsd:string | 0 | 1 |
| [completeness](../../Core/Properties/completeness.md) | [RelationshipCompleteness](../../Core/Vocabularies/RelationshipCompleteness.md) | 0 | 1 |
| [creationInfo](../../Core/Properties/creationInfo.md) | [CreationInfo](../../Core/Classes/CreationInfo.md) | 1 | 1 |
| [description](../../Core/Properties/description.md) | xsd:string | 0 | 1 |
| [endTime](../../Core/Properties/endTime.md) | [DateTime](../../Core/Datatypes/DateTime.md) | 0 | 1 |
| [extension](../../Core/Properties/extension.md) | [Extension](../../Extension/Classes/Extension.md) | 0 | * |
| [externalIdentifier](../../Core/Properties/externalIdentifier.md) | [ExternalIdentifier](../../Core/Classes/ExternalIdentifier.md) | 0 | * |
| [externalRef](../../Core/Properties/externalRef.md) | [ExternalRef](../../Core/Classes/ExternalRef.md) | 0 | * |
| [from](../../Core/Properties/from.md) | [Element](../../Core/Classes/Element.md) | 1 | 1 |
| [modifiedTime](../../Security/Properties/modifiedTime.md) | [DateTime](../../Core/Datatypes/DateTime.md) | 0 | 1 |
| [name](../../Core/Properties/name.md) | xsd:string | 0 | 1 |
| [publishedTime](../../Security/Properties/publishedTime.md) | [DateTime](../../Core/Datatypes/DateTime.md) | 0 | 1 |
| [relationshipType](../../Core/Properties/relationshipType.md) | [RelationshipType](../../Core/Vocabularies/RelationshipType.md) | 1 | 1 |
| [spdxId](../../Core/Properties/spdxId.md) | xsd:anyURI | 1 | 1 |
| [startTime](../../Core/Properties/startTime.md) | [DateTime](../../Core/Datatypes/DateTime.md) | 0 | 1 |
| [statusNotes](../../Security/Properties/statusNotes.md) | xsd:string | 0 | 1 |
| [summary](../../Core/Properties/summary.md) | xsd:string | 0 | 1 |
| [suppliedBy](../../Core/Properties/suppliedBy.md) | [Agent](../../Core/Classes/Agent.md) | 0 | 1 |
| [to](../../Core/Properties/to.md) | [Element](../../Core/Classes/Element.md) | 1 | * |
| [verifiedUsing](../../Core/Properties/verifiedUsing.md) | [IntegrityMethod](../../Core/Classes/IntegrityMethod.md) | 0 | * |
| [vexVersion](../../Security/Properties/vexVersion.md) | xsd:string | 0 | 1 |
| [withdrawnTime](../../Security/Properties/withdrawnTime.md) | [DateTime](../../Core/Datatypes/DateTime.md) | 0 | 1 |



