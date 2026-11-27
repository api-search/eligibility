---
api_specs:
- filename: attestari-ai-health-api-openapi.yml
  format: yaml
  label: Attestari Health API
  slug: attestari-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestari-ai/openapi/attestari-ai-health-api-openapi.yml
- filename: attestari-ai-manifest-api-openapi.yml
  format: yaml
  label: Attestari Manifest API
  slug: attestari-ai-manifest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestari-ai/openapi/attestari-ai-manifest-api-openapi.yml
- filename: attestari-ai-remote-api-openapi.yml
  format: yaml
  label: Attestari Remote API
  slug: attestari-ai-remote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestari-ai/openapi/attestari-ai-remote-api-openapi.yml
- filename: attestari-ai-verdict-api-openapi.yml
  format: yaml
  label: Attestari Verdict API
  slug: attestari-ai-verdict-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestari-ai/openapi/attestari-ai-verdict-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Export and sanctions laws apply to your use of Attestari; do not use it where they prohibit it.
  entity_types:
  - text: if you use Attestari as an individual for personal purposes
    type: individual
  - text: If you use Attestari for an organisation, you accept these terms for it and confirm you may do so
    type: business
  minimum_age:
    text: You must be at least 16, and old enough to form a binding contract where you live.
    value: '16'
  restricted_uses:
  - summary: No harassment
    text: use Attestari to harass anyone, including publishers
  - summary: No misrepresenting grades
    text: misrepresent a grade, alter it, or imply we endorse you
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
name: Attestari
provenance_date: '2026-11-09'
provider_name: Attestari
provider_slug: attestari-ai
slug: attestari-ai-eligibility
source_date: '2026-11-09'
source_filename: attestari-ai-eligibility.yml
source_heading: Eligibility
source_page: https://attestari.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Attestari\naid: attestari-ai\nurl: https://attestari.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Export and sanctions laws apply to your use of Attestari; do not use it where they prohibit it.\nentity_types:\n- type: individual\n  text: if you use Attestari as an individual for personal purposes\n- type: business\n  text: If you use Attestari for an organisation, you accept these terms for it and confirm you may do so\nrestricted_uses:\n- summary: No harassment\n  text: use Attestari to harass anyone, including publishers\n- summary: No misrepresenting grades\n  text:\
  \ misrepresent a grade, alter it, or imply we endorse you\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16, and old enough to form a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/attestari-ai/eligibility/attestari-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Attestari's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- MCP
- Security
- Compliance
- Open Source
---
