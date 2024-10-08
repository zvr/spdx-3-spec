<!-- Automatically generated by spec-parser v2.5.0 on 2024-08-10T18:46:28.607668+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# LifecycleScopeType

## Summary

Provide an enumerated set of lifecycle phases that can provide context to relationships.


## Description

This enumeration summarizes common phases when dependency and other relationships, have different implications, based on their context.  For example,  a build dependency, may have different implications than a operational dependency.


## Metadata

`https://spdx.org/rdf/3.0.1/terms/Core/LifecycleScopeType`


| | |
|---|---|
| Name | LifecycleScopeType |




## Entries

- build: A relationship has specific context implications during an element's build phase, during development.
- design: A relationship has specific context implications during an element's design.
- development: A relationship has specific context implications during development phase of an element.
- other: A relationship has other specific context information necessary to capture that the above set of enumerations does not handle.
- runtime: A relationship has specific context implications during the execution phase of an element.
- test: A relationship has specific context implications during an element's testing phase, during development.

