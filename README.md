# FOCUS Specification (focus-spec)

FOCUS, the FinOps Open Cost and Usage Specification, is an open standard maintained under the FinOps Foundation that normalizes cost and usage data across cloud, SaaS, data center, and other technology vendors. FOCUS defines a common data schema, a controlled vocabulary of column names, allowed values, and pricing attributes so that practitioners can apply a consistent set of FinOps practices regardless of which provider generated the underlying billing dataset.

FOCUS is purely a data specification rather than a REST API. Conforming providers expose exports of their billing data in the FOCUS format, and tooling consumes those exports against the published column library, data model, and validator.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/focus-spec/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producing
- **Access:** 3rd-Party

## Tags

- Billing
- Cost and Usage
- FinOps
- Open Standard
- Specification

## APIs

### FOCUS Specification

FOCUS does not expose a REST API. The artifact tracked by this repository is a JSON Schema representation of a single FOCUS-conformant billing record, derived from the column attributes defined in the FOCUS specification. The schema lists the normative columns (BilledCost, EffectiveCost, ContractedCost, ListCost, BillingAccountId, BillingCurrency, ChargeCategory, ChargePeriodStart/End, ProviderName, PublisherName, ServiceName, ServiceCategory, etc.) and reflects the allowed values, nullability, and requirement levels documented in the FOCUS data model.

- **Specification Site:** [https://focus.finops.org/](https://focus.finops.org/)
- **Getting Started:** [https://focus.finops.org/focus-getting-started/](https://focus.finops.org/focus-getting-started/)
- **GitHub Repository:** [https://github.com/FinOps-Open-Cost-and-Usage-Spec/FOCUS_Spec](https://github.com/FinOps-Open-Cost-and-Usage-Spec/FOCUS_Spec)
- **JSON Schema:** [json-schema/focus-billing-record-schema.json](json-schema/focus-billing-record-schema.json)

## Common Properties

- [Website](https://focus.finops.org/)
- [Documentation](https://focus.finops.org/)
- [GitHub Repository](https://github.com/FinOps-Open-Cost-and-Usage-Spec/FOCUS_Spec)
- [GitHub Organization](https://github.com/FinOps-Open-Cost-and-Usage-Spec)
- [JSON Schema](json-schema/focus-billing-record-schema.json)

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-28

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
