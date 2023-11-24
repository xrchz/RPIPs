---
rpip: #<to be assigned>
title: RPL Burn Mechanics
description: Adds a mechanism for burning RPL to improve RPL utility and close the loop on token issuance
author: Ramana Kumar (@xrchz), LookingForOwls (@LookingForOwls)
discussions-to: <URL>
status: Draft
type: Protocol
category: Core
created: 2023-11-22
# requires (*optional):
---

## Abstract
Adds a mechanism for a node operator to burn RPL to temporarily access higher commission for their minipools. A node operator's commission, paid by rETH holders on their staking rewards, can be boosted (increased by a percentage) for a period of time by the node operator sacrificing an amount of RPL to the protocol. These boosts can be stacked up to a maximum commission rate. The amount of RPL per boost, the time period, and the percentage increase in commission per boost are all protocol parameters that can be adjusted by the pDAO. The initial parameters are: TODO.

## Motivation
The motivation section should describe the "why" of this RPIP. What problem does it solve? Why should someone want to implement this standard? What benefit does it provide to the Ethereum ecosystem? What use cases does this RPIP address?

## Specification
The key words “MUST”, “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”, “SHOULD NOT”, “RECOMMENDED”, “MAY”, and “OPTIONAL” in this document are to be interpreted as described in RFC 2119.

The technical specification should describe the syntax and semantics of any new feature.

## Rationale
The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages.

## Backwards Compatibility
All RPIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The RPIP must explain how the author proposes to deal with these incompatibilities. RPIP submissions without a sufficient backwards compatibility treatise may be rejected outright.

## Test Cases
Test cases for an implementation are mandatory for RPIPs that are affecting protocol changes.  If the test suite is too large to reasonably be included inline, then consider adding it as one or more files in `../assets/rpip-####/`.

## Reference Implementation
An optional section that contains a reference/example implementation that people can use to assist in understanding or implementing this specification.  If the implementation is too large to reasonably be included inline, then consider adding it as one or more files in `../assets/rpip-####/`.

## Security Considerations
All RPIPs must contain a section that discusses the security implications/considerations relevant to the proposed change. Include information that might be important for security discussions, surfaces risks and can be used throughout the life cycle of the proposal. E.g. include security-relevant design decisions, concerns, important discussions, implementation-specific guidance and pitfalls, an outline of threats and risks and how they are being addressed. RPIP submissions missing the "Security Considerations" section will be rejected. An RPIP cannot proceed to status "Final" without a Security Considerations discussion deemed sufficient by the reviewers.

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
