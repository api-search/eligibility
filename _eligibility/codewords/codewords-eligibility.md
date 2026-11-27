---
api_specs:
- filename: codewords-workflows-api-openapi.yml
  format: yaml
  label: Agemo Workflows API
  slug: codewords-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codewords/openapi/codewords-workflows-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: refer to you as an individual if you access our Platform as an individual
    type: individual
  - text: the organisation you represent where you access our Platform on behalf of an organisation
    type: business
  minimum_age:
    text: You represent and warrant that you are at least eighteen (18) years old or the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: use the Platform in connection with any unlawful, illegal, fraudulent, deceptive or harmful purpose or activity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may require you or your Personnel to register for an account and provide certain information about themselves
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agemo
provenance_date: '2026-11-09'
provider_name: Agemo
provider_slug: codewords
slug: codewords-eligibility
source_date: '2026-11-09'
source_filename: codewords-eligibility.yml
source_heading: Eligibility
source_page: https://www.codewords.ai/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agemo\naid: codewords\nurl: https://www.codewords.ai/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: refer to you as an individual if you access our Platform as an individual\n- type: business\n  text: the organisation you represent where you access our Platform on behalf of an organisation\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: use the Platform in connection with any unlawful, illegal, fraudulent, deceptive or harmful purpose or activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: we may require you or your Personnel to register for an account and provide certain information about themselves\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least eighteen (18) years old or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/codewords/eligibility/codewords-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Agemo's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Workflows
- No-Code
- Software-as-a-Service
- Productivity
---
