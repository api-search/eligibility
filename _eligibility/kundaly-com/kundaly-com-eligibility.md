---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter into a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to enter into a binding contract.
    value: '18'
  restricted_uses:
  - summary: Decisions about other people
    text: use Kundaly, or its readings, to make decisions about another person's employment, housing, credit, insurance, education or immigration
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Every account starts with an email address you confirm with a code we send to it.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: kundaly-com
provenance_date: '2026-11-09'
provider_name: kundaly-com
provider_slug: kundaly-com
slug: kundaly-com-eligibility
source_date: '2026-11-09'
source_filename: kundaly-com-eligibility.yml
source_heading: Eligibility
source_page: https://kundaly.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: kundaly-com\naid: kundaly-com\nurl: https://kundaly.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into a binding contract.\nrestricted_uses:\n- summary: Decisions about other people\n  text: use Kundaly, or its readings, to make decisions about another person's employment, housing, credit, insurance,\n    education or immigration\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Every account starts with an email address you confirm with\
  \ a code we send to it.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/kundaly-com/eligibility/kundaly-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from kundaly-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Astrology
- Vedic
- Western
- BirthChart
---
