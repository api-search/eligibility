---
api_specs:
- filename: capitalcompany-ai-openapi-generated.yml
  format: yaml
  label: Capital Company API
  slug: capitalcompany-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capitalcompany-ai/openapi/_ae-authored/capitalcompany-ai-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users may not be located within or a resident of any country or territory subject to United States trade and economic sanctions or embargoes.
  minimum_age:
    text: To use our Services, you must be at least 16 years old, and in some circumstances even older (please check your local law for the age of digital consent).
    value: '16'
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
name: Capital Company
provenance_date: '2026-11-09'
provider_name: Capital Company
provider_slug: capitalcompany-ai
slug: capitalcompany-ai-eligibility
source_date: '2026-11-09'
source_filename: capitalcompany-ai-eligibility.yml
source_heading: Eligibility
source_page: https://capitalcompany.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capital Company\naid: capitalcompany-ai\nurl: https://capitalcompany.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Users may not be located within or a resident of any country or territory subject to United States trade\n    and economic sanctions or embargoes.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: To use our Services, you must be at least 16 years old, and in some circumstances even older (please check\n    your local law for the age of digital consent).\n"
source_yaml_url: https://artifacts.apis.io/capitalcompany-ai/eligibility/capitalcompany-ai-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Capital Company's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Fund Administration
- SPV
- Investment
- CapitalManagement
---
