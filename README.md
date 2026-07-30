# FortiGate Configuration Examples

Public collection of FortiGate CLI examples for network-security engineering and defensive administration.

## Status and scope

- **Classification:** Data and configuration collection
- **Purpose:** Reusable FortiGate examples and reference snippets
- **Production readiness:** No file is production-ready without environment-specific review
- **Support:** Best-effort reference material, not an official Fortinet or Mornex product

## Safe use

Before applying any configuration:

1. Confirm the target FortiGate model, FortiOS version, VDOM, interfaces, and existing object names.
2. Review every address, subnet, country code, FQDN, service, and policy dependency.
3. Verify external data against an authoritative and current source.
4. Take a complete configuration backup and define the rollback procedure.
5. Apply the smallest required scope during an approved change window.
6. Validate intended traffic and verify that unrelated traffic remains unaffected.

## Important limitations

Geo-IP allocations, ASN ownership, country mappings, provider ranges, and service endpoints change over time. Files containing such data are snapshots and must be revalidated before use.

Blocking all countries except one is a high-impact control. It can interrupt remote administration, cloud services, software updates, monitoring, DNS, authentication, content delivery, and third-party integrations. Review explicit exceptions and maintain an out-of-band recovery path.

## Repository requirements

New or changed files should include, in the file or pull-request description:

- intended outcome and FortiOS compatibility;
- source and verification date for external data;
- prerequisites and expected side effects;
- validation commands or acceptance checks;
- rollback or cleanup steps.

Do not commit customer configurations, credentials, private keys, pre-shared keys, tokens, certificates, or confidential infrastructure details.

## Disclaimer

These examples are provided for defensive and educational use. The operator is responsible for reviewing, testing, approving, and validating every change before production use.
