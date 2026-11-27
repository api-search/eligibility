---
api_specs:
- filename: colacloud-us-colas-api-openapi.yml
  format: yaml
  label: COLA Cloud COLAs API
  slug: colacloud-us-colas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/colacloud-us/openapi/colacloud-us-colas-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, organized under the laws of, or ordinarily resident in a country or territory subject to comprehensive U.S. sanctions, and that you are not identified on a restricted-party list.
  entity_types:
  - text: If you use the Services on behalf of a company or other organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated decisions
    text: Use the Services to make automated decisions that create legal or similarly significant effects without appropriate safeguards and human review.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require authentication, usage controls, rate limits, identity verification, billing verification, or additional account review before allowing access to some features.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: COLA Cloud
provenance_date: '2026-11-09'
provider_name: COLA Cloud
provider_slug: colacloud-us
slug: colacloud-us-eligibility
source_date: '2026-11-09'
source_filename: colacloud-us-eligibility.yml
source_heading: Eligibility
source_page: https://colacloud.us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: COLA Cloud\naid: colacloud-us\nurl: https://colacloud.us/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, organized under the laws of, or ordinarily resident in a country\n    or territory subject to comprehensive U.S. sanctions, and that you are not identified on a restricted-party\n    list.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other organization, you represent that you have authority\n    to bind that organization.\nrestricted_uses:\n- summary: Automated decisions\n  text: Use\
  \ the Services to make automated decisions that create legal or similarly significant effects without\n    appropriate safeguards and human review.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require authentication, usage controls, rate limits, identity verification, billing verification,\n    or additional account review before allowing access to some features.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/colacloud-us/eligibility/colacloud-us-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from COLA Cloud's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Alcohol
- Compliance
- Open Data
---
