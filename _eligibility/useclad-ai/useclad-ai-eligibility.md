---
api_specs:
- filename: useclad-ai-openapi-generated.yml
  format: yaml
  label: Clad Labs API
  slug: useclad-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/useclad-ai/openapi/_ae-authored/useclad-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services in violation of U.S. export control or sanctions laws, and you represent you are not a prohibited party or in a restricted jurisdiction.
  entity_types:
  - text: Clad is a business product intended for organizations and their authorized users.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Highly regulated data
    text: Process HIPAA-regulated health information, PCI cardholder data, government-classified information, or other highly regulated data without our express written authorization
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
name: Clad Labs
provenance_date: '2026-11-10'
provider_name: Clad Labs
provider_slug: useclad-ai
slug: useclad-ai-eligibility
source_date: '2026-11-10'
source_filename: useclad-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.useclad.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clad Labs\naid: useclad-ai\nurl: https://www.useclad.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services in violation of U.S. export control or sanctions laws, and you represent you\n    are not a prohibited party or in a restricted jurisdiction.\nentity_types:\n- type: business\n  text: Clad is a business product intended for organizations and their authorized users.\nrestricted_uses:\n- summary: Highly regulated data\n  text: Process HIPAA-regulated health information, PCI cardholder data, government-classified information, or other\n    highly\
  \ regulated data without our express written authorization\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/useclad-ai/eligibility/useclad-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Clad Labs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Support
- Software-as-a-Service
- Automation
---
