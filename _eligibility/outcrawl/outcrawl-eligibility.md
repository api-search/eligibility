---
api_specs:
- filename: outcrawl-scrape-api-openapi.yml
  format: yaml
  label: Outcrawl Scrape API
  slug: outcrawl-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/outcrawl/openapi/outcrawl-scrape-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the service.
    type: individual
  - text: if you are acting for an organisation, on its behalf too.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the service.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a Google or GitHub account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Outcrawl
provenance_date: '2026-11-10'
provider_name: Outcrawl
provider_slug: outcrawl
slug: outcrawl-eligibility
source_date: '2026-11-10'
source_filename: outcrawl-eligibility.yml
source_heading: Eligibility
source_page: https://outcrawl.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Outcrawl\naid: outcrawl\nurl: https://outcrawl.ai/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the service.\n- type: business\n  text: if you are acting for an organisation, on its behalf too.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with a Google or GitHub account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the service.\n"
source_yaml_url: https://artifacts.apis.io/outcrawl/eligibility/outcrawl-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Outcrawl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Web Infrastructure
- Data Extraction
- Automation
---
