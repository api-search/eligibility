---
api_specs:
- filename: ezel-ai-openapi-generated.yml
  format: yaml
  label: Ezel API
  slug: ezel-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezel-ai/openapi/_ae-authored/ezel-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access from embargoed countries is prohibited; the page does not name specific countries.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk AI use cases
    text: The Service is not intended, designed, or certified for "high-risk" AI system use cases as defined in Annex III of the EU AI Act.
  - summary: Prohibited AI practices
    text: You must not use the Service for any AI practices prohibited under Article 5 of the EU AI Act
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
name: Ezel
provenance_date: '2026-11-09'
provider_name: Ezel
provider_slug: ezel-ai
slug: ezel-ai-eligibility
source_date: '2026-11-09'
source_filename: ezel-ai-eligibility.yml
source_heading: Eligibility
source_page: https://ezel.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ezel\naid: ezel-ai\nurl: https://ezel.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access from embargoed countries is prohibited; the page does not name specific countries.\nentity_types: []\nrestricted_uses:\n- summary: High-risk AI use cases\n  text: The Service is not intended, designed, or certified for \"high-risk\" AI system use cases as defined in Annex\n    III of the EU AI Act.\n- summary: Prohibited AI practices\n  text: You must not use the Service for any AI practices prohibited under Article 5 of the EU AI Act\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ezel-ai/eligibility/ezel-ai-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Ezel's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Legal Tech
- Software-as-a-Service
- Platform
- Company
---
