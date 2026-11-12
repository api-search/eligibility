---
api_specs:
- filename: courtdelta-com-attorney-cta-api-openapi.yml
  format: yaml
  label: Court Delta Attorney Cta API
  slug: courtdelta-com-attorney-cta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-attorney-cta-api-openapi.yml
- filename: courtdelta-com-calendar-api-openapi.yml
  format: yaml
  label: Court Delta Calendar API
  slug: courtdelta-com-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-calendar-api-openapi.yml
- filename: courtdelta-com-case-lookup-public-api-openapi.yml
  format: yaml
  label: Court Delta Case Lookup Public API
  slug: courtdelta-com-case-lookup-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-case-lookup-public-api-openapi.yml
- filename: courtdelta-com-case-summary-api-openapi.yml
  format: yaml
  label: Court Delta Case Summary API
  slug: courtdelta-com-case-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-case-summary-api-openapi.yml
- filename: courtdelta-com-citation-check-api-openapi.yml
  format: yaml
  label: Court Delta Citation Check API
  slug: courtdelta-com-citation-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-citation-check-api-openapi.yml
- filename: courtdelta-com-court-date-lookup-api-openapi.yml
  format: yaml
  label: Court Delta Court Date Lookup API
  slug: courtdelta-com-court-date-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-court-date-lookup-api-openapi.yml
- filename: courtdelta-com-courthouse-info-api-openapi.yml
  format: yaml
  label: Court Delta Courthouse Info API
  slug: courtdelta-com-courthouse-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-courthouse-info-api-openapi.yml
- filename: courtdelta-com-expunction-options-api-openapi.yml
  format: yaml
  label: Court Delta Expunction Options API
  slug: courtdelta-com-expunction-options-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-expunction-options-api-openapi.yml
- filename: courtdelta-com-license-points-api-openapi.yml
  format: yaml
  label: Court Delta License Points API
  slug: courtdelta-com-license-points-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-license-points-api-openapi.yml
- filename: courtdelta-com-public-api-openapi.yml
  format: yaml
  label: Court Delta Public API
  slug: courtdelta-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-public-api-openapi.yml
- filename: courtdelta-com-settings-api-openapi.yml
  format: yaml
  label: Court Delta Settings API
  slug: courtdelta-com-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-settings-api-openapi.yml
- filename: courtdelta-com-subscribe-api-openapi.yml
  format: yaml
  label: Court Delta Subscribe API
  slug: courtdelta-com-subscribe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-subscribe-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old. By registering, you represent that you meet this requirement.
    type: individual
  - text: Attorney Users (Paid Tiers) Monitor multiple cases based on subscription tier
    type: business
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Service only for lawful purposes.
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
name: Court Delta
provenance_date: '2026-11-09'
provider_name: Court Delta
provider_slug: courtdelta-com
slug: courtdelta-com-eligibility
source_date: '2026-11-09'
source_filename: courtdelta-com-eligibility.yml
source_heading: Eligibility
source_page: https://app.courtdelta.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Court Delta\naid: courtdelta-com\nurl: https://app.courtdelta.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old. By registering, you represent that you meet this requirement.\n- type: business\n  text: Attorney Users (Paid Tiers) Monitor multiple cases based on subscription tier\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Service only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/courtdelta-com/eligibility/courtdelta-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Court Delta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Court Records
- Case Tracking
- Notifications
- North Carolina
- MCP
---
