---
api_specs:
- filename: leo-labs-catalog-api-openapi.yml
  format: yaml
  label: LeoLabs Catalog API
  slug: leo-labs-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leo-labs/openapi/leo-labs-catalog-api-openapi.yml
- filename: leo-labs-instruments-api-openapi.yml
  format: yaml
  label: LeoLabs Instruments API
  slug: leo-labs-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leo-labs/openapi/leo-labs-instruments-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using this Website, you represent and warrant that you are of legal age to form a binding contract in the jurisdiction in which you live.
    value: null
  restricted_uses:
  - summary: Unlawful or commercial use
    text: You may use the Website only for lawful purposes and in accordance with these Terms.
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
name: LeoLabs
provenance_date: '2026-11-09'
provider_name: LeoLabs
provider_slug: leo-labs
slug: leo-labs-eligibility
source_date: '2026-11-09'
source_filename: leo-labs-eligibility.yml
source_heading: Eligibility
source_page: https://leolabs.space/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LeoLabs\naid: leo-labs\nurl: https://leolabs.space/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or commercial use\n  text: You may use the Website only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: By using this Website, you represent and warrant that you are of legal age to form a binding contract in\n    the jurisdiction in which you live.\n"
source_yaml_url: https://artifacts.apis.io/leo-labs/eligibility/leo-labs-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from LeoLabs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Space
- Satellite
- Space Situational Awareness
- Space Traffic Management
- Orbital Data
- Radar
- Aerospace
- Defense
- Geospatial
---
