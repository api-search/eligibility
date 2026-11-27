---
api_specs:
- filename: moxiedocs-com-check-drift-api-openapi.yml
  format: yaml
  label: moxiedocs-com Check Drift API
  slug: moxiedocs-com-check-drift-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moxiedocs-com/openapi/moxiedocs-com-check-drift-api-openapi.yml
- filename: moxiedocs-com-docs-api-openapi.yml
  format: yaml
  label: moxiedocs-com Docs API
  slug: moxiedocs-com-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moxiedocs-com/openapi/moxiedocs-com-docs-api-openapi.yml
claim_count: 1
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
  - summary: Sensitive data submission
    text: Do not submit secrets, credentials, regulated data, or third-party confidential data unless you have permission and an agreement that covers that use.
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
name: moxiedocs-com
provenance_date: '2026-11-10'
provider_name: moxiedocs-com
provider_slug: moxiedocs-com
slug: moxiedocs-com-eligibility
source_date: '2026-11-10'
source_filename: moxiedocs-com-eligibility.yml
source_heading: Eligibility
source_page: https://moxiedocs.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: moxiedocs-com\naid: moxiedocs-com\nurl: https://moxiedocs.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sensitive data submission\n  text: Do not submit secrets, credentials, regulated data, or third-party confidential data unless you have permission\n    and an agreement that covers that use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/moxiedocs-com/eligibility/moxiedocs-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from moxiedocs-com's own page on 2026-11-10.
synthetic: false
tags:
- Documentation
- Artificial Intelligence
- GitHub
- Automation
- Developer Tools
---
