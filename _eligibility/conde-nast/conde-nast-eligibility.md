---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation, warranty, covenant or guarantee that the Service or any Products are appropriate, available, or legal in any particular geographic location.
  minimum_age:
    text: The Service is not intended for users under the age of 13
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: Unless otherwise specified, the Service is intended for your personal, non-commercial use only.
  - summary: No LLM development or training without consent
    text: Non-commercial use does not include use of the Service
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
name: Condé Nast
provenance_date: '2026-11-09'
provider_name: Condé Nast
provider_slug: conde-nast
slug: conde-nast-eligibility
source_date: '2026-11-09'
source_filename: conde-nast-eligibility.yml
source_heading: Eligibility
source_page: https://www.condenast.com/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Condé Nast\naid: conde-nast\nurl: https://www.condenast.com/user-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation, warranty, covenant or guarantee that the Service or any Products are appropriate,\n    available, or legal in any particular geographic location.\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: Unless otherwise specified, the Service is intended for your personal, non-commercial use only.\n- summary: No LLM development or training without consent\n  text: Non-commercial use does not\
  \ include use of the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Service is not intended for users under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/conde-nast/eligibility/conde-nast-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Condé Nast's own page on 2026-11-09.
synthetic: false
tags:
- Media
- Publishing
- Magazines
- News
- Journalism
- RSS
- Video
- JSON-LD
- Schema.org
---
