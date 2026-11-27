---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use it on behalf of an organisation, you confirm that you may accept them for it.
    type: business
  minimum_age:
    text: must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Submitting personal or sensitive data
    text: submit personal data about other people without a lawful basis, or special categories of personal data
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a GitHub, Google or ChatGPT account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Atoma
provenance_date: '2026-11-09'
provider_name: Atoma
provider_slug: atoma-run
slug: atoma-run-eligibility
source_date: '2026-11-09'
source_filename: atoma-run-eligibility.yml
source_heading: Eligibility
source_page: https://atoma.run/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atoma\naid: atoma-run\nurl: https://atoma.run/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use it on behalf of an organisation, you confirm that you may accept them for it.\nrestricted_uses:\n- summary: Submitting personal or sensitive data\n  text: submit personal data about other people without a lawful basis, or special categories of personal data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with a GitHub, Google or ChatGPT account\nminimum_age:\n  value: '18'\n  text: must\
  \ be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/atoma-run/eligibility/atoma-run-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Atoma's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Workflows
- Coordination
- Platform
---
