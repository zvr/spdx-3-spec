<!-- Automatically generated by spec-parser v2.5.0 on 2024-08-10T18:46:28.607668+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# CvssV3VulnAssessmentRelationship

## Summary

Provides a CVSS version 3 assessment for a vulnerability.


## Description

A CvssV3VulnAssessmentRelationship relationship describes the determined score,
severity, and vector of a vulnerability as defined in
[Common Vulnerability Scoring System v3.0: Specification Document](https://www.first.org/cvss/v3.0/specification-document)
or
[Common Vulnerability Scoring System v3.1: Specification Document](https://www.first.org/cvss/v3.1/specification-document).

It is intended to communicate the results of using a CVSS calculator.

*Constraints*

- The relationship type must be set to `hasAssessmentFor`.

*Example*

```json
{
  "type": "CvssV3VulnAssessmentRelationship",
  "spdxId": "urn:spdx.dev:cvssv3-cve-2020-28498",
  "relationshipType": "hasAssessmentFor",
  "security_score": "6.8",
  "security_severity": "medium",
  "security_vectorString": "CVSS:3.1/AV:N/AC:H/PR:N/UI:N/S:C/C:H/I:N/A:N",
  "from": "urn:spdx.dev:vuln-cve-2020-28498",
  "to": ["urn:product-acme-application-1.3"],
  "security_assessedElement": "urn:npm-elliptic-6.5.2",
  "externalRef": [
    {
      "type": "ExternalRef",
      "externalRefType": "securityAdvisory",
      "locator": "https://nvd.nist.gov/vuln/detail/CVE-2020-28498"
    },
    {
      "type": "ExternalRef",
      "externalRefType": "securityAdvisory",
      "locator": "https://snyk.io/vuln/SNYK-JS-ELLIPTIC-1064899"
    },
    {
      "type": "ExternalRef",
      "externalRefType": "securityFix",
      "locator": "https://github.com/indutny/elliptic/commit/441b742"
    }
  ],
  "suppliedBy": ["urn:spdx.dev:agent-my-security-vendor"],
  "publishedTime": "2023-05-06T10:06:13Z"
},
{
  "type": "Relationship",
  "spdxId": "urn:spdx.dev:vulnAgentRel-1",
  "relationshipType": "publishedBy",
  "from": "urn:spdx.dev:cvssv3-cve-2020-28498",
  "to": ["urn:spdx.dev:agent-snyk"],
  "startTime": "2021-03-08T16:06:50Z"
}
```


## Metadata

`https://spdx.org/rdf/3.0.1/terms/Security/CvssV3VulnAssessmentRelationship`


| | |
|---|---|
| Name | CvssV3VulnAssessmentRelationship |
| Instantiability | Concrete |
| SubclassOf | [VulnAssessmentRelationship](../Classes/VulnAssessmentRelationship.md) |


## Superclasses

* [/Security/VulnAssessmentRelationship](../../Security/Classes/VulnAssessmentRelationship.md)
* [/Core/Relationship](../../Core/Classes/Relationship.md)
* [/Core/Element](../../Core/Classes/Element.md)




## Properties

| Property | Type | minCount | maxCount |
|---|---|:---:|:---:|
| [score](../Properties/score.md) | xsd:decimal | 1 | 1 |
| [severity](../Properties/severity.md) | [CvssSeverityType](../Vocabularies/CvssSeverityType.md) | 1 | 1 |
| [vectorString](../Properties/vectorString.md) | xsd:string | 1 | 1 |



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
| [publishedTime](../../Security/Properties/publishedTime.md) | [DateTime](../../Core/Datatypes/DateTime.md) | 0 | 1 |
| [relationshipType](../../Core/Properties/relationshipType.md) | [RelationshipType](../../Core/Vocabularies/RelationshipType.md) | 1 | 1 |
| [score](../../Security/Properties/score.md) | xsd:decimal | 1 | 1 |
| [severity](../../Security/Properties/severity.md) | [CvssSeverityType](../../Security/Vocabularies/CvssSeverityType.md) | 1 | 1 |
| [spdxId](../../Core/Properties/spdxId.md) | xsd:anyURI | 1 | 1 |
| [startTime](../../Core/Properties/startTime.md) | [DateTime](../../Core/Datatypes/DateTime.md) | 0 | 1 |
| [summary](../../Core/Properties/summary.md) | xsd:string | 0 | 1 |
| [suppliedBy](../../Core/Properties/suppliedBy.md) | [Agent](../../Core/Classes/Agent.md) | 0 | 1 |
| [to](../../Core/Properties/to.md) | [Element](../../Core/Classes/Element.md) | 1 | * |
| [vectorString](../../Security/Properties/vectorString.md) | xsd:string | 1 | 1 |
| [verifiedUsing](../../Core/Properties/verifiedUsing.md) | [IntegrityMethod](../../Core/Classes/IntegrityMethod.md) | 0 | * |
| [withdrawnTime](../../Security/Properties/withdrawnTime.md) | [DateTime](../../Core/Datatypes/DateTime.md) | 0 | 1 |



