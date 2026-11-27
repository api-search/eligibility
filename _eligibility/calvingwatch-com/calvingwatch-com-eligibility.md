---
api_specs:
- filename: calvingwatch-com-public-knowledge-api-openapi.yml
  format: yaml
  label: CalvingWatch Public knowledge API
  slug: calvingwatch-com-public-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calvingwatch-com/openapi/calvingwatch-com-public-knowledge-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have authority to accept these Terms for the farm or business using CalvingWatch.
    type: business
  minimum_age:
    text: You must be at least 18 years old and have authority to accept these Terms for the farm or business using CalvingWatch.
    value: '18'
  restricted_uses:
  - summary: No monitoring of people
    text: Do not use CalvingWatch to monitor people.
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
name: CalvingWatch
provenance_date: '2026-11-09'
provider_name: CalvingWatch
provider_slug: calvingwatch-com
slug: calvingwatch-com-eligibility
source_date: '2026-11-09'
source_filename: calvingwatch-com-eligibility.yml
source_heading: Eligibility
source_page: https://calvingwatch.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CalvingWatch\naid: calvingwatch-com\nurl: https://calvingwatch.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You must be at least 18 years old and have authority to accept these Terms for the farm or business using\n    CalvingWatch.\nrestricted_uses:\n- summary: No monitoring of people\n  text: Do not use CalvingWatch to monitor people.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have authority to accept these\
  \ Terms for the farm or business using\n    CalvingWatch.\n"
source_yaml_url: https://artifacts.apis.io/calvingwatch-com/eligibility/calvingwatch-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CalvingWatch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- Artificial Intelligence
- Livestock
- Monitoring
- Ireland
---
