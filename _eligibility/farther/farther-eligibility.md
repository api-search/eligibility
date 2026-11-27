---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no claims concerning whether the Content may be downloaded, viewed, or be appropriate for use outside of the United States.
  entity_types:
  - text: Clients are individuals that have entered into a separate Investment Advisory Agreement (“Investment Advisory Agreement”) with Farther
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal non-commercial use only
    text: Use the Platform solely for your personal, non-commercial use.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Farther is under no obligation to accept any individual as a Client and may accept or reject any registration in its sole and complete discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Farther
provenance_date: '2026-11-09'
provider_name: Farther
provider_slug: farther
slug: farther-eligibility
source_date: '2026-11-09'
source_filename: farther-eligibility.yml
source_heading: Eligibility
source_page: https://www.farther.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Farther\naid: farther\nurl: https://www.farther.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no claims concerning whether the Content may be downloaded, viewed, or be appropriate for use outside\n    of the United States.\nentity_types:\n- type: individual\n  text: Clients are individuals that have entered into a separate Investment Advisory Agreement (“Investment Advisory\n    Agreement”) with Farther\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: Use the Platform solely for your personal, non-commercial use.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: Farther is under no obligation to accept any individual as a Client and may accept or reject any registration\n    in its sole and complete discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/farther/eligibility/farther-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Farther's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Wealth Management
- Financial Services
- Registered Investment Advisor
- Financial Planning
- Investment Management
- WealthTech
---
