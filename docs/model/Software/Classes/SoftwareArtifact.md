<!-- Automatically generated by spec-parser v2.0.0 on 2023-12-27T15:02:03.969017+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# SoftwareArtifact

## Summary

A distinct article or unit related to Software.


## Description

A software artifact is a distinct article or unit related to software
such as a package, a file, or a snippet.


## Metadata

- Instantiability: Abstract
- name: SoftwareArtifact
- SubclassOf: /Core/Artifact



## Properties

| Property | Type | minCount | maxCount |
|---|---|---|---|
| additionalPurpose | SoftwarePurpose | 0 | * |
| attributionText | xsd:string | 0 | * |
| contentIdentifier | xsd:anyURI | 0 | 1 |
| copyrightText | xsd:string | 0 | 1 |
| primaryPurpose | SoftwarePurpose | 0 | 1 |
