---
api_specs:
- filename: disconetwork-discobeat-api-openapi.yml
  format: yaml
  label: Disconetwork Discobeat API
  slug: disconetwork-discobeat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disconetwork/openapi/disconetwork-discobeat-api-openapi.yml
- filename: disconetwork-events-api-openapi.yml
  format: yaml
  label: Disconetwork Events API
  slug: disconetwork-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disconetwork/openapi/disconetwork-events-api-openapi.yml
- filename: disconetwork-recommendations-api-openapi.yml
  format: yaml
  label: Disconetwork Recommendations API
  slug: disconetwork-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disconetwork/openapi/disconetwork-recommendations-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer represents, warrants and covenants that (i) it possesses all necessary rights and consents
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal use prohibited
    text: use the Services for any purpose that is illegal in any way or that advocates illegal activity
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
name: Disconetwork
provenance_date: '2026-11-09'
provider_name: Disconetwork
provider_slug: disconetwork
slug: disconetwork-eligibility
source_date: '2026-11-09'
source_filename: disconetwork-eligibility.yml
source_heading: Eligibility
source_page: https://disconetwork.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Disconetwork\naid: disconetwork\nurl: https://disconetwork.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer represents, warrants and covenants that (i) it possesses all necessary rights and consents\nrestricted_uses:\n- summary: Illegal use prohibited\n  text: use the Services for any purpose that is illegal in any way or that advocates illegal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/disconetwork/eligibility/disconetwork-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Disconetwork's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commerce Media
- Retail Media
- Post-Purchase
- Advertising
- E-Commerce
- AdTech
- Marketing
- Analytics
- Reporting
---
