---
api_specs:
- filename: customeros-billing-api-api-openapi.yml
  format: yaml
  label: CustomerOS Billing API
  slug: customeros-billing-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customeros/openapi/customeros-billing-api-api-openapi.yml
- filename: customeros-customerbase-api-api-openapi.yml
  format: yaml
  label: CustomerOS CustomerBASE API
  slug: customeros-customerbase-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customeros/openapi/customeros-customerbase-api-api-openapi.yml
- filename: customeros-domains-api-openapi.yml
  format: yaml
  label: CustomerOS Domains API
  slug: customeros-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customeros/openapi/customeros-domains-api-openapi.yml
- filename: customeros-email-verification-api-openapi.yml
  format: yaml
  label: CustomerOS Email Verification API
  slug: customeros-email-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customeros/openapi/customeros-email-verification-api-openapi.yml
- filename: customeros-enrichment-api-api-openapi.yml
  format: yaml
  label: CustomerOS Enrichment API
  slug: customeros-enrichment-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customeros/openapi/customeros-enrichment-api-api-openapi.yml
- filename: customeros-flows-api-openapi.yml
  format: yaml
  label: CustomerOS Flows API
  slug: customeros-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customeros/openapi/customeros-flows-api-openapi.yml
- filename: customeros-ip-intelligence-api-openapi.yml
  format: yaml
  label: CustomerOS IP Intelligence API
  slug: customeros-ip-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customeros/openapi/customeros-ip-intelligence-api-openapi.yml
- filename: customeros-mailboxes-api-openapi.yml
  format: yaml
  label: CustomerOS Mailboxes API
  slug: customeros-mailboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customeros/openapi/customeros-mailboxes-api-openapi.yml
- filename: customeros-outreach-api-openapi.yml
  format: yaml
  label: CustomerOS Outreach API
  slug: customeros-outreach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customeros/openapi/customeros-outreach-api-openapi.yml
- filename: customeros-graph-ql-api-openapi.yml
  format: yaml
  label: CustomerOS Graph QL API
  slug: customeros-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customeros/openapi/customeros-graph-ql-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THE SERVICES ARE INTENDED FOR BUSINESS USE ONLY.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-Risk Activities
    text: (viii) use the Product with any High-Risk Activities or with activity prohibited by Applicable Laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CustomerOS
provenance_date: '2026-11-09'
provider_name: CustomerOS
provider_slug: customeros
slug: customeros-eligibility
source_date: '2026-11-09'
source_filename: customeros-eligibility.yml
source_heading: Eligibility
source_page: https://customeros.ai/standard-agreement/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CustomerOS\naid: customeros\nurl: https://customeros.ai/standard-agreement/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: THE SERVICES ARE INTENDED FOR BUSINESS USE ONLY.\nrestricted_uses:\n- summary: High-Risk Activities\n  text: (viii) use the Product with any High-Risk Activities or with activity prohibited by Applicable Laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/customeros/eligibility/customeros-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CustomerOS's own page on 2026-11-09.
synthetic: false
tags:
- CRM
- Revenue
- Go-To-Market
- Lead Intelligence
- Visitor Identification
- Attribution
- Email Verification
- Data Enrichment
- GraphQL
- Open Source
- A2A
---
