<!-- Automatically generated by spec-parser v2.3.0 on 2024-07-16T15:00:52.540788+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# EpssVulnAssessmentRelationship

## Summary

Provides an EPSS assessment for a vulnerability.


## Description

An EpssVulnAssessmentRelationship relationship describes the likelihood or
probability that a vulnerability will be exploited in the wild, and the
percentile ranking of probability relative to all other vulnerabilities' EPSS
scores, using the Exploit Prediction Scoring System (EPSS) as defined at
[https://www.first.org/epss/model](https://www.first.org/epss/model).

**Constraints**

- The relationship type must be set to hasAssessmentFor.
- The probability must be between 0 and 1.
- The percentile must be between 0 and 1.

**Syntax**

```json
{
  "@type": "EpssVulnAssessmentRelationship",
  "@id": "urn:spdx.dev:epss-CVE-2020-28498",
  "relationshipType": "hasAssessmentFor",
  "probability": 0.00105,
  "percentile": 0.42356,
  "from": "urn:spdx.dev:vuln-cve-2020-28498",
  "to": ["urn:product-acme-application-1.3"],
  "suppliedBy": ["urn:spdx.dev:agent-jane-doe"],
  "publishedTime": "2023-10-05T00:00:30Z"
}
```


## Metadata

`https://spdx.org/rdf/3.0.0/terms/Security/EpssVulnAssessmentRelationship`


| | |
|---|---|
| Name | EpssVulnAssessmentRelationship |
| Instantiability | Concrete |
| SubclassOf | [VulnAssessmentRelationship](../Classes/VulnAssessmentRelationship.md) |


## Superclasses

* [/Security/VulnAssessmentRelationship](../../Security/Classes/VulnAssessmentRelationship.md)
* [/Core/Relationship](../../Core/Classes/Relationship.md)
* [/Core/Element](../../Core/Classes/Element.md)




## Properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [percentile](../Properties/percentile.md) | xsd:decimal | 1 | 1 |
| [probability](../Properties/probability.md) | xsd:decimal | 1 | 1 |
| [publishedTime](../Properties/publishedTime.md) | [/Core/DateTime](../../Core/Datatypes/DateTime.md) | 1 | 1 |



## All properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
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
| [percentile](../../Security/Properties/percentile.md) | xsd:decimal | 1 | 1 |
| [probability](../../Security/Properties/probability.md) | xsd:decimal | 1 | 1 |
| [publishedTime](../../Security/Properties/publishedTime.md) | [DateTime](../../Core/Datatypes/DateTime.md) | 0 | 1 |
| [relationshipType](../../Core/Properties/relationshipType.md) | [RelationshipType](../../Core/Vocabularies/RelationshipType.md) | 1 | 1 |
| [spdxId](../../Core/Properties/spdxId.md) | xsd:anyURI | 1 | 1 |
| [startTime](../../Core/Properties/startTime.md) | [DateTime](../../Core/Datatypes/DateTime.md) | 0 | 1 |
| [summary](../../Core/Properties/summary.md) | xsd:string | 0 | 1 |
| [suppliedBy](../../Core/Properties/suppliedBy.md) | [Agent](../../Core/Classes/Agent.md) | 0 | 1 |
| [to](../../Core/Properties/to.md) | [Element](../../Core/Classes/Element.md) | 1 | * |
| [verifiedUsing](../../Core/Properties/verifiedUsing.md) | [IntegrityMethod](../../Core/Classes/IntegrityMethod.md) | 0 | * |
| [withdrawnTime](../../Security/Properties/withdrawnTime.md) | [DateTime](../../Core/Datatypes/DateTime.md) | 0 | 1 |


