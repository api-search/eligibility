---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: intended solely for use by United States residents who reside in the United States
  entity_types:
  - text: who are at least 18 years of age and have otherwise reached the age of majority
    type: individual
  minimum_age:
    text: at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Insurance only where legally sold
    text: Insurance products are only available to people in those jurisdictions in which they may be legally sold.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Approval of your application is not guaranteed and is subject to acceptance by the insurance company offering the policy that you have applied for
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ladder
provenance_date: '2026-11-09'
provider_name: Ladder
provider_slug: ladder
slug: ladder-eligibility
source_date: '2026-11-09'
source_filename: ladder-eligibility.yml
source_heading: Eligibility
source_page: https://www.ladderlife.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ladder\naid: ladder\nurl: https://www.ladderlife.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: intended solely for use by United States residents who reside in the United States\nentity_types:\n- type: individual\n  text: who are at least 18 years of age and have otherwise reached the age of majority\nrestricted_uses:\n- summary: Insurance only where legally sold\n  text: Insurance products are only available to people in those jurisdictions in which they may be legally sold.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Approval of\
  \ your application is not guaranteed and is subject to acceptance by the insurance company offering\n    the policy that you have applied for\nminimum_age:\n  value: '18'\n  text: at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/ladder/eligibility/ladder-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Ladder's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Life Insurance
- Embedded Finance
- Embedded Insurance
- Financial Services
- Fintech
- Quoting
---
