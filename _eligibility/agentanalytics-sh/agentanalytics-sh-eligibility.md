---
api_specs:
- filename: agentanalytics-sh-api-openapi.yml
  format: yaml
  label: Agent Analytics API API
  slug: agent-analytics-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentanalytics-sh/openapi/_original/agentanalytics-sh-api-openapi.yml
claim_count: 3
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
  - summary: Protected health information
    text: Protected health information (PHI) — medical records, diagnoses, treatment information, or any data covered by HIPAA or equivalent regulations.
  - summary: Children's data under 16
    text: Children's personal data — any data from users known to be under 16 years of age, including data subject to COPPA.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must authenticate via GitHub or Google to create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agent Analytics
provenance_date: '2026-11-09'
provider_name: Agent Analytics
provider_slug: agentanalytics-sh
slug: agentanalytics-sh-eligibility
source_date: '2026-11-09'
source_filename: agentanalytics-sh-eligibility.yml
source_heading: Eligibility
source_page: https://agentanalytics.sh/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agent Analytics\naid: agentanalytics-sh\nurl: https://agentanalytics.sh/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Protected health information\n  text: Protected health information (PHI) — medical records, diagnoses, treatment information, or any data covered\n    by HIPAA or equivalent regulations.\n- summary: Children's data under 16\n  text: Children's personal data — any data from users known to be under 16 years of age, including data subject\n    to COPPA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: You must authenticate via GitHub or Google to create an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentanalytics-sh/eligibility/agentanalytics-sh-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Agent Analytics's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Artificial Intelligence
- Web Analytics
- Open Source
- Software-as-a-Service
---
