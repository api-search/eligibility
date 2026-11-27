---
api_specs:
- filename: citevana-com-openapi-generated.yml
  format: yaml
  label: Citevana API
  slug: citevana-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citevana-com/openapi/_ae-authored/citevana-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Citevana for an organisation, you confirm you can accept these terms for it.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal use or infringing rights
    text: Do not use Citevana to break the law or other people's rights.
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
name: Citevana
provenance_date: '2026-11-09'
provider_name: Citevana
provider_slug: citevana-com
slug: citevana-com-eligibility
source_date: '2026-11-09'
source_filename: citevana-com-eligibility.yml
source_heading: Eligibility
source_page: https://citevana.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Citevana\naid: citevana-com\nurl: https://citevana.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use Citevana for an organisation, you confirm you can accept these terms for it.\nrestricted_uses:\n- summary: Illegal use or infringing rights\n  text: Do not use Citevana to break the law or other people's rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/citevana-com/eligibility/citevana-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Citevana's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- SEO
- SearchVisibility
---
