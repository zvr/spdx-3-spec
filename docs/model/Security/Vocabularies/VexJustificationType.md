<!-- Automatically generated by spec-parser v2.0.0 on 2023-12-27T15:02:03.969017+00:00 -->
<!-- SPDX-License-Identifier: Community-Spec-1.0 -->

# VexJustificationType

## Summary

Specifies the VEX justification type.


## Description

VexJustificationType specifies the type of Vulnerability Exploitability eXchange (VEX) justification.


## Metadata

- name: VexJustificationType



## Entries

- componentNotPresent: The software is not affected because the vulnerable component is not in the product.
- inlineMitigationsAlreadyExist: Built-in inline controls or mitigations prevent an adversary from leveraging the vulnerability.
- vulnerableCodeCannotBeControlledByAdversary: The vulnerable component is present, and the component contains the vulnerable code. However, vulnerable code is used in such a way that an attacker cannot mount any anticipated attack.
- vulnerableCodeNotInExecutePath: The affected code is not reachable through the execution of the code, including non-anticipated states of the product.
- vulnerableCodeNotPresent: The product is not affected because the code underlying the vulnerability is not present in the product.
