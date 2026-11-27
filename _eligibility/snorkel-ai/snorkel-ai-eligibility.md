---
api_specs:
- filename: snorkel-ai-openapi-generated.yml
  format: yaml
  label: Snorkel Platform REST API
  slug: snorkel-platform-rest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snorkel-ai/openapi/_ae-authored/snorkel-ai-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Export control compliance
    text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired from Company, or any products utilizing such data, in violation of the United States export laws or regulations.
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
name: Snorkel AI
provenance_date: '2026-11-10'
provider_name: Snorkel AI
provider_slug: snorkel-ai
slug: snorkel-ai-eligibility
source_date: '2026-11-10'
source_filename: snorkel-ai-eligibility.yml
source_heading: Eligibility
source_page: https://snorkel.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Snorkel AI\naid: snorkel-ai\nurl: https://snorkel.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control compliance\n  text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired\n    from Company, or any products utilizing such data, in violation of the United States export laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE\
  \ TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/snorkel-ai/eligibility/snorkel-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Snorkel AI's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Data Development
- Programmatic Labeling
- Weak Supervision
- Evaluation
- SDK
---
