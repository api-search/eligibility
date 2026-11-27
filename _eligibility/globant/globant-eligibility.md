---
api_specs:
- filename: globant-catalog-api-openapi.yml
  format: yaml
  label: Globant Catalog API
  slug: globant-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globant/openapi/globant-catalog-api-openapi.yml
- filename: globant-health-api-openapi.yml
  format: yaml
  label: Globant Health API
  slug: globant-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globant/openapi/globant-health-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Site and our services are not designed for minors, and we do not knowingly collect personal data from minors.
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In case we need to verify your identity, we may require you to send us a copy of a valid government issued identification document.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Globant
provenance_date: '2026-11-09'
provider_name: Globant
provider_slug: globant
slug: globant-eligibility
source_date: '2026-11-09'
source_filename: globant-eligibility.yml
source_heading: Eligibility
source_page: https://glob.ai/en/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Globant\naid: globant\nurl: https://glob.ai/en/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In case we need to verify your identity, we may require you to send us a copy of a valid government issued\n    identification document.\nminimum_age:\n  value: null\n  text: The Site and our services are not designed for minors, and we do not knowingly collect personal data from\n    minors.\n"
source_yaml_url: https://artifacts.apis.io/globant/eligibility/globant-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from Globant's own page on 2026-11-09.
synthetic: false
tags:
- Software
- Digital Transformation
- Artificial Intelligence
- Agents
- MCP
- Consulting
- Enterprise
---
