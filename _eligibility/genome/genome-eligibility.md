---
api_specs:
- filename: genome-host-to-host-api-openapi.yml
  format: yaml
  label: Genome Host-to-Host API
  slug: genome-host-to-host-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genome/openapi/genome-host-to-host-api-openapi.yml
- filename: genome-payouts-api-openapi.yml
  format: yaml
  label: Genome Payouts API
  slug: genome-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genome/openapi/genome-payouts-api-openapi.yml
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
  - summary: No face-to-face transactions
    text: Not to accept or present for processing any face-to-face Transactions
  - summary: Illegal or prohibited activities
    text: Not to use Genome Wallet or the Service for any illegal purposes or prohibited activities listed in the General T&Cs and included in the List of Prohibited Activities
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
name: Genome
provenance_date: '2026-11-09'
provider_name: Genome
provider_slug: genome
slug: genome-eligibility
source_date: '2026-11-09'
source_filename: genome-eligibility.yml
source_heading: Eligibility
source_page: https://genome.eu/merchant-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Genome\naid: genome\nurl: https://genome.eu/merchant-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No face-to-face transactions\n  text: Not to accept or present for processing any face-to-face Transactions\n- summary: Illegal or prohibited activities\n  text: Not to use Genome Wallet or the Service for any illegal purposes or prohibited activities listed in the\n    General T&Cs and included in the List of Prohibited Activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/genome/eligibility/genome-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Genome's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Payments
- Banking
- Open Banking
- PSD2
- SEPA
- Card Processing
- Payouts
- Electronic Money Institution
- Europe
---
