---
api_specs:
- filename: ainsof-io-openapi-generated.yml
  format: yaml
  label: AINSOF API
  slug: ainsof-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ainsof-io/openapi/_ae-authored/ainsof-io-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Individual and Business plans are for one named person.
    type: individual
  minimum_age:
    text: The service is intended for music and video professionals and creators, and is not directed at children under 16
    value: '16'
  restricted_uses:
  - summary: Plan-limited uses
    text: Any use not listed for your plan needs a different plan or a separate agreement.
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
name: AINSOF
provenance_date: '2026-11-09'
provider_name: AINSOF
provider_slug: ainsof-io
slug: ainsof-io-eligibility
source_date: '2026-11-09'
source_filename: ainsof-io-eligibility.yml
source_heading: Eligibility
source_page: https://ainsof.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AINSOF\naid: ainsof-io\nurl: https://ainsof.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Individual and Business plans are for one named person.\nrestricted_uses:\n- summary: Plan-limited uses\n  text: Any use not listed for your plan needs a different plan or a separate agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The service is intended for music and video professionals and creators, and is not directed at children\n    under 16\n"
source_yaml_url: https://artifacts.apis.io/ainsof-io/eligibility/ainsof-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AINSOF's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Artificial Intelligence
- Licensing
- Media
---
