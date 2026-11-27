---
api_specs:
- filename: hydracept-com-public-api-api-openapi.yml
  format: yaml
  label: hydracept-com Public API
  slug: hydracept-com-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydracept-com/openapi/hydracept-com-public-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for an organization, you confirm that you have authority to bind that organization.
    type: business
  minimum_age:
    text: The Service is intended for adults and for organizations whose authorized users are adults.
    value: null
  restricted_uses:
  - summary: Safety-critical reliance
    text: Do not rely on preview capabilities for safety-critical, life-critical, or other uses where failure could cause serious harm.
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
name: hydracept-com
provenance_date: '2026-11-09'
provider_name: hydracept-com
provider_slug: hydracept-com
slug: hydracept-com-eligibility
source_date: '2026-11-09'
source_filename: hydracept-com-eligibility.yml
source_heading: Eligibility
source_page: https://hydracept.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hydracept-com\naid: hydracept-com\nurl: https://hydracept.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for an organization, you confirm that you have authority to bind that organization.\nrestricted_uses:\n- summary: Safety-critical reliance\n  text: Do not rely on preview capabilities for safety-critical, life-critical, or other uses where failure could\n    cause serious harm.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ The Service is intended for adults and for organizations whose authorized users are adults.\n"
source_yaml_url: https://artifacts.apis.io/hydracept-com/eligibility/hydracept-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from hydracept-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- ExternalCapabilities
- DurableJobs
- Billing
---
