---
api_specs:
- filename: minicor-external-api-openapi.yml
  format: yaml
  label: Minicor External API
  slug: minicor-external-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/minicor/openapi/minicor-external-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial solicitation
    text: Using the Sites for any commercial solicitation purposes;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to reject any registration in our sole discretion and without any liability to us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Minicor
provenance_date: '2026-11-10'
provider_name: Minicor
provider_slug: minicor
slug: minicor-eligibility
source_date: '2026-11-10'
source_filename: minicor-eligibility.yml
source_heading: Eligibility
source_page: https://legal.laminar.run/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Minicor\naid: minicor\nurl: https://legal.laminar.run/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial solicitation\n  text: Using the Sites for any commercial solicitation purposes;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to reject any registration in our sole discretion and without any liability to us.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/minicor/eligibility/minicor-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Minicor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Desktop Automation
- RPA
- Computer Use Agents
- Workflow Automation
- Healthcare
- Legacy Systems
- AI Agents
- Integration
---
