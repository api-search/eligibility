---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any individual or entity accessing or using Agency Handy services.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Agency Handy
provenance_date: '2026-11-09'
provider_name: Agency Handy
provider_slug: agencyhandy-com
slug: agencyhandy-com-eligibility
source_date: '2026-11-09'
source_filename: agencyhandy-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.agencyhandy.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agency Handy\naid: agencyhandy-com\nurl: https://www.agencyhandy.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any individual or entity accessing or using Agency Handy services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agencyhandy-com/eligibility/agencyhandy-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Agency Handy's own page on 2026-11-09.
synthetic: false
tags:
- Agency
- Software-as-a-Service
- Client Portal
- Project Management
- Invoicing
---
