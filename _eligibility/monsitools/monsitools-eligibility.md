---
api_specs:
- filename: monsitools-api-tools-json-api-openapi.yml
  format: yaml
  label: MonsiTools Api Tools.json API
  slug: monsitools-api-tools-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monsitools/openapi/monsitools-api-tools-json-api-openapi.yml
- filename: monsitools-calculate-api-openapi.yml
  format: yaml
  label: MonsiTools Calculate API
  slug: monsitools-calculate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monsitools/openapi/monsitools-calculate-api-openapi.yml
- filename: monsitools-keys-api-openapi.yml
  format: yaml
  label: MonsiTools Keys API
  slug: monsitools-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monsitools/openapi/monsitools-keys-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using monsitools, you confirm that you are at least 18 years old (or the age of majority in your jurisdiction) and possess the legal authority to enter into this agreement.
    type: individual
  - text: If you are using our tools on behalf of a company or entity, you agree to these terms on their behalf.
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years old (or the age of majority in your jurisdiction)
    value: '18'
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
name: MonsiTools
provenance_date: '2026-11-10'
provider_name: MonsiTools
provider_slug: monsitools
slug: monsitools-eligibility
source_date: '2026-11-10'
source_filename: monsitools-eligibility.yml
source_heading: Eligibility
source_page: https://monsitools.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MonsiTools\naid: monsitools\nurl: https://monsitools.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using monsitools, you confirm that you are at least 18 years old (or the age of majority in your jurisdiction)\n    and possess the legal authority to enter into this agreement.\n- type: business\n  text: If you are using our tools on behalf of a company or entity, you agree to these terms on their behalf.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: you confirm that you are at least 18 years old (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/monsitools/eligibility/monsitools-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from MonsiTools's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Calculators
- Finance
- Workflows
- MCP
- Data Tools
---
