---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: But not all services mentioned may be available in your country.
  entity_types:
  - text: If you’re a business user or organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Professional advice
    text: DON’T RELY ON THE SERVICES FOR MEDICAL, LEGAL, FINANCIAL, OR OTHER PROFESSIONAL ADVICE.
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
name: Google Patents
provenance_date: '2026-11-09'
provider_name: Google Patents
provider_slug: google-patents
slug: google-patents-eligibility
source_date: '2026-11-09'
source_filename: google-patents-eligibility.yml
source_heading: Eligibility
source_page: https://policies.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Patents\naid: google-patents\nurl: https://policies.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: But not all services mentioned may be available in your country.\nentity_types:\n- type: business\n  text: If you’re a business user or organization\nrestricted_uses:\n- summary: Professional advice\n  text: DON’T RELY ON THE SERVICES FOR MEDICAL, LEGAL, FINANCIAL, OR OTHER PROFESSIONAL ADVICE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-patents/eligibility/google-patents-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Google Patents's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Patents
- Search
- Intellectual Property
- Google
---
