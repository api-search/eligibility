---
api_specs:
- filename: openapi.json
  format: json
  label: Term Dates API
  slug: term-dates-api
  spec_type: OpenAPI
  url: https://termdatesapi.co.uk/openapi.json
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
  - summary: Not regulated advice; outputs not offers
    text: Nothing here is financial, legal, tax, medical or other regulated advice, and no tool output is a quote, an offer, or a recommendation to act.
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
name: termdatesapi-co-uk
provenance_date: '2026-11-10'
provider_name: termdatesapi-co-uk
provider_slug: termdatesapi-co-uk
slug: termdatesapi-co-uk-eligibility
source_date: '2026-11-10'
source_filename: termdatesapi-co-uk-eligibility.yml
source_heading: Eligibility
source_page: https://termdatesapi.co.uk/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: termdatesapi-co-uk\naid: termdatesapi-co-uk\nurl: https://termdatesapi.co.uk/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not regulated advice; outputs not offers\n  text: Nothing here is financial, legal, tax, medical or other regulated advice, and no tool output is a quote,\n    an offer, or a recommendation to act.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/termdatesapi-co-uk/eligibility/termdatesapi-co-uk-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from termdatesapi-co-uk's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- United Kingdom
- School
- Term-Dates
---
