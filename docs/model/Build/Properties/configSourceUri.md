<!-- Automatically generated by spec-parser v2.3.0 on 2024-07-29T18:25:30.305944+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# configSourceUri

## Summary

Property that describes the URI of the build configuration source file.


## Description

If a build configuration exists for the toolchain or platform performing the
build, the configSourceUri of a build is the URI of that build configuration.

For example, a build triggered by a GitHub Action is defined by a build
configuration YAML file. In this case, the configSourceUri is the URL of that
YAML file.


## Metadata

`https://spdx.org/rdf/3.0.0/terms/Build/configSourceUri`


| | |
|---|---|
| Name | configSourceUri |
| Nature | DataProperty |
| Range | xsd:anyURI |




## Referenced

- [/Build/Build](../../Build/Classes/Build.md)

