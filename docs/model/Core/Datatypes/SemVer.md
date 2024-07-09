<!-- Automatically generated by spec-parser v2.3.0 on 2024-07-09T12:43:38.633388+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# SemVer

## Summary

A string constrained to the SemVer 2.0.0 specification.


## Description

A semantic version is a string that is following the specification of
[Semantic Versioning 2.0.0](https://semver.org/).


## Metadata

`https://spdx.org/rdf/3.0.0/terms/Core/SemVer`


| | |
|---|---|
| Name | SemVer |
| SubclassOf | xsd:string |




## Format

- Pattern: `^(0|[1-9]\d*)\.(0|[1-9]\d*)\.(0|[1-9]\d*)(?:-((?:0|[1-9]\d*|\d*[a-zA-Z-][0-9a-zA-Z-]*)(?:\.(?:0|[1-9]\d*|\d*[a-zA-Z-][0-9a-zA-Z-]*))*))?(?:\+([0-9a-zA-Z-]+(?:\.[0-9a-zA-Z-]+)*))?$`
