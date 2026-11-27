---
api_specs:
- filename: allspice-io-repos-api-openapi.yml
  format: yaml
  label: AllSpice.io Repos API
  slug: allspice-io-repos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allspice-io/openapi/allspice-io-repos-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: (i) by any individual or entity in any country to which the United States has embargoed goods
  entity_types:
  - text: solely for Customer's internal business operations up to the Quantities specified on the Order Form
    type: business
  minimum_age:
    text: NOT FOR USE BY CHILDREN UNDER 13 YEARS OF AGE
    value: '13'
  restricted_uses:
  - summary: Export control restrictions
    text: Customer and each Affiliate may not access or use the AllSpice Assets or any underlying information or technology except in full compliance with all applicable United States export control laws.
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
name: AllSpice.io
provenance_date: '2026-11-09'
provider_name: AllSpice.io
provider_slug: allspice-io
slug: allspice-io-eligibility
source_date: '2026-11-09'
source_filename: allspice-io-eligibility.yml
source_heading: Eligibility
source_page: https://allspice.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AllSpice.io\naid: allspice-io\nurl: https://allspice.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: (i) by any individual or entity in any country to which the United States has embargoed goods\nentity_types:\n- type: business\n  text: solely for Customer's internal business operations up to the Quantities specified on the Order Form\nrestricted_uses:\n- summary: Export control restrictions\n  text: Customer and each Affiliate may not access or use the AllSpice Assets or any underlying information or technology\n    except in full compliance with all applicable United States\
  \ export control laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: NOT FOR USE BY CHILDREN UNDER 13 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/allspice-io/eligibility/allspice-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AllSpice.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hardware
- Collaboration
- Artificial Intelligence
- Design
---
