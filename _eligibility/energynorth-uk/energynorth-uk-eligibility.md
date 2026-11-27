---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Energy North connects homeowners, property managers and verified tradespeople across the UK
  entity_types:
  - text: One person per account; you're responsible for activity on your account.
    type: individual
  - text: tradespeople are independent businesses, not our employees or subcontractors.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Regulated trades need Green badge
    text: Regulated trades may only pick up regulated jobs with an active Green badge
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: earned by submitting valid insurance and a recognised government-scheme certificate, which our team checks.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: energynorth-uk
provenance_date: '2026-11-09'
provider_name: energynorth-uk
provider_slug: energynorth-uk
slug: energynorth-uk-eligibility
source_date: '2026-11-09'
source_filename: energynorth-uk-eligibility.yml
source_heading: Eligibility
source_page: https://energynorth.uk/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: energynorth-uk\naid: energynorth-uk\nurl: https://energynorth.uk/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Energy North connects homeowners, property managers and verified tradespeople across the UK\nentity_types:\n- type: individual\n  text: One person per account; you're responsible for activity on your account.\n- type: business\n  text: tradespeople are independent businesses, not our employees or subcontractors.\nrestricted_uses:\n- summary: Regulated trades need Green badge\n  text: Regulated trades may only pick up regulated jobs with an active Green badge\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: earned by submitting valid insurance and a recognised government-scheme certificate, which our team checks.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/energynorth-uk/eligibility/energynorth-uk-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from energynorth-uk's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Marketplace
- Homeowners
- Tradespeople
- United Kingdom
---
