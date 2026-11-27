---
api_specs:
- filename: plausible-customprops-api-openapi.yml
  format: yaml
  label: Plausible CustomProps API
  slug: plausible-customprops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-customprops-api-openapi.yml
- filename: plausible-events-api-openapi.yml
  format: yaml
  label: Plausible Events API
  slug: plausible-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-events-api-openapi.yml
- filename: plausible-goals-api-openapi.yml
  format: yaml
  label: Plausible Goals API
  slug: plausible-goals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-goals-api-openapi.yml
- filename: plausible-guests-api-openapi.yml
  format: yaml
  label: Plausible Guests API
  slug: plausible-guests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-guests-api-openapi.yml
- filename: plausible-query-api-openapi.yml
  format: yaml
  label: Plausible Query API
  slug: plausible-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-query-api-openapi.yml
- filename: plausible-sites-api-openapi.yml
  format: yaml
  label: Plausible Sites API
  slug: plausible-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-sites-api-openapi.yml
- filename: plausible-teams-api-openapi.yml
  format: yaml
  label: Plausible Teams API
  slug: plausible-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-teams-api-openapi.yml
- filename: plausible-shared-links-api-openapi.yml
  format: yaml
  label: Plausible Shared Links API
  slug: plausible-shared-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-shared-links-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive personal data
    text: You agree not to use the service to send sensitive information such as credit card numbers, government identifiers, financial account information, real-time geolocation or other highly sensitive personal data.
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
name: Plausible
provenance_date: '2026-11-10'
provider_name: Plausible
provider_slug: plausible
slug: plausible-eligibility
source_date: '2026-11-10'
source_filename: plausible-eligibility.yml
source_heading: Eligibility
source_page: https://plausible.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plausible\naid: plausible\nurl: https://plausible.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sensitive personal data\n  text: You agree not to use the service to send sensitive information such as credit card numbers, government identifiers,\n    financial account information, real-time geolocation or other highly sensitive personal data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/plausible/eligibility/plausible-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Plausible's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Cookie-Free
- Event Tracking
- GDPR
- Goal Conversions
- Open Source
- Privacy
- Self-Hosted
- Site Management
- Web Analytics
---
