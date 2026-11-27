---
api_specs:
- filename: jobo-world-openapi-generated.yml
  format: yaml
  label: jobo-world API
  slug: jobo-world-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobo-world/openapi/_ae-authored/jobo-world-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access or use the Services from, or for the benefit of, any country, region, or person subject to U.S. sanctions or export restrictions
  entity_types:
  - text: The Services are offered only to businesses and professionals for business purposes. They are not offered to consumers.
    type: business
  minimum_age:
    text: You represent that you are at least 18 years old and that you are not using the Services for personal, family, or household purposes.
    value: '18'
  restricted_uses:
  - summary: No FCRA or consumer report use
    text: Use Delivered Data, in whole or in part, as a consumer report or as a factor in determining any individual's eligibility for employment, credit, insurance, housing, or any other purpose covered by the U.S. Fair Credit Reporting Act or similar laws
  - summary: No unlawful discrimination
    text: Use the Services or Delivered Data to discriminate unlawfully against any person, including on the basis of a protected characteristic
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
name: jobo-world
provenance_date: '2026-11-09'
provider_name: jobo-world
provider_slug: jobo-world
slug: jobo-world-eligibility
source_date: '2026-11-09'
source_filename: jobo-world-eligibility.yml
source_heading: Eligibility
source_page: https://jobo.world/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: jobo-world\naid: jobo-world\nurl: https://jobo.world/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access or use the Services from, or for the benefit of, any country, region, or person subject to U.S. sanctions\n    or export restrictions\nentity_types:\n- type: business\n  text: The Services are offered only to businesses and professionals for business purposes. They are not offered\n    to consumers.\nrestricted_uses:\n- summary: No FCRA or consumer report use\n  text: Use Delivered Data, in whole or in part, as a consumer report or as a factor in determining any individual's\n\
  \    eligibility for employment, credit, insurance, housing, or any other purpose covered by the U.S. Fair Credit\n    Reporting Act or similar laws\n- summary: No unlawful discrimination\n  text: Use the Services or Delivered Data to discriminate unlawfully against any person, including on the basis\n    of a protected characteristic\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 years old and that you are not using the Services for personal, family,\n    or household purposes.\n"
source_yaml_url: https://artifacts.apis.io/jobo-world/eligibility/jobo-world-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from jobo-world's own page on 2026-11-09.
synthetic: false
tags:
- Job Data
- Recruiting
- Platform
- Data Infrastructure
---
