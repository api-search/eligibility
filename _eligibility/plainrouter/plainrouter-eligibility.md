---
api_specs:
- filename: plainrouter-actiondryrunapi-api-openapi.yml
  format: yaml
  label: Plainrouter Action Dry Run API
  slug: plainrouter-actiondryrunapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-actiondryrunapi-api-openapi.yml
- filename: plainrouter-actionproposalapi-api-openapi.yml
  format: yaml
  label: Plainrouter Action Proposal API
  slug: plainrouter-actionproposalapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-actionproposalapi-api-openapi.yml
- filename: plainrouter-actionreadapi-api-openapi.yml
  format: yaml
  label: Plainrouter Action Read API
  slug: plainrouter-actionreadapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-actionreadapi-api-openapi.yml
- filename: plainrouter-actionruleapi-api-openapi.yml
  format: yaml
  label: Plainrouter Action Rule API
  slug: plainrouter-actionruleapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-actionruleapi-api-openapi.yml
- filename: plainrouter-adtestapi-api-openapi.yml
  format: yaml
  label: Plainrouter Ad Test API
  slug: plainrouter-adtestapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-adtestapi-api-openapi.yml
- filename: plainrouter-agentcontext-api-openapi.yml
  format: yaml
  label: Plainrouter Agent Context API
  slug: plainrouter-agentcontext-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-agentcontext-api-openapi.yml
- filename: plainrouter-cookiedeclaration-api-openapi.yml
  format: yaml
  label: Plainrouter Cookie Declaration API
  slug: plainrouter-cookiedeclaration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-cookiedeclaration-api-openapi.yml
- filename: plainrouter-creative-api-openapi.yml
  format: yaml
  label: Plainrouter Creative API
  slug: plainrouter-creative-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-creative-api-openapi.yml
- filename: plainrouter-deploymentplan-api-openapi.yml
  format: yaml
  label: Plainrouter Deployment Plan API
  slug: plainrouter-deploymentplan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-deploymentplan-api-openapi.yml
- filename: plainrouter-draftbatchfileimport-api-openapi.yml
  format: yaml
  label: Plainrouter Draft Batch File Import API
  slug: plainrouter-draftbatchfileimport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-draftbatchfileimport-api-openapi.yml
- filename: plainrouter-event-api-openapi.yml
  format: yaml
  label: Plainrouter Event API
  slug: plainrouter-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-event-api-openapi.yml
- filename: plainrouter-launchpolicy-api-openapi.yml
  format: yaml
  label: Plainrouter Launch Policy API
  slug: plainrouter-launchpolicy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-launchpolicy-api-openapi.yml
- filename: plainrouter-metainventoryexposure-api-openapi.yml
  format: yaml
  label: Plainrouter Meta Inventory Exposure API
  slug: plainrouter-metainventoryexposure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-metainventoryexposure-api-openapi.yml
- filename: plainrouter-operations-api-openapi.yml
  format: yaml
  label: Plainrouter Operations API
  slug: plainrouter-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-operations-api-openapi.yml
- filename: plainrouter-sandbox-api-openapi.yml
  format: yaml
  label: Plainrouter Sandbox API
  slug: plainrouter-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plainrouter/openapi/plainrouter-sandbox-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering into these Terms.
    type: individual
  - text: The Service is intended for business and professional use.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering into these Terms.
    value: '18'
  restricted_uses:
  - summary: No sole basis for legally significant decisions
    text: Do not use the Service as the sole basis for decisions that could produce legal or similarly significant effects on an individual.
  - summary: Special-category or highly sensitive data
    text: The Customer must not submit special-category personal data, children's data, payment-card data, credentials, or other highly sensitive data unless the feature is expressly designed for it and the parties have agreed appropriate safeguards.
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
name: Plainrouter
provenance_date: '2026-11-10'
provider_name: Plainrouter
provider_slug: plainrouter
slug: plainrouter-eligibility
source_date: '2026-11-10'
source_filename: plainrouter-eligibility.yml
source_heading: Eligibility
source_page: https://plainrouter.com/terms.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plainrouter\naid: plainrouter\nurl: https://plainrouter.com/terms.md\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering into these Terms.\n- type: business\n  text: The Service is intended for business and professional use.\nrestricted_uses:\n- summary: No sole basis for legally significant decisions\n  text: Do not use the Service as the sole basis for decisions that could produce legal or similarly significant\n    effects on an individual.\n- summary: Special-category\
  \ or highly sensitive data\n  text: The Customer must not submit special-category personal data, children's data, payment-card data, credentials,\n    or other highly sensitive data unless the feature is expressly designed for it and the parties have agreed appropriate\n    safeguards.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/plainrouter/eligibility/plainrouter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Plainrouter's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advertising
- Developer Tools
- Paid Ads
---
