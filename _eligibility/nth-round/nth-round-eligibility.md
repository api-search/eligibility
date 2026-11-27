---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms are applicable to all persons who use or access the Platform and/or the Services, in their company’s capacity or in an individual capacity
    type: business
  minimum_age:
    text: User may use the Services only if User is eighteen (18) years of age or older
    value: '18'
  restricted_uses:
  - summary: Fraudulent or illegal practices
    text: Engage in any fraudulent, deceptive, or illegal practices or activities
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Nth Round may, at its discretion, decline to offer the Services for any reason, including in the event that the Services enrollment process is not satisfactorily completed
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nth Round
provenance_date: '2026-11-10'
provider_name: Nth Round
provider_slug: nth-round
slug: nth-round-eligibility
source_date: '2026-11-10'
source_filename: nth-round-eligibility.yml
source_heading: Eligibility
source_page: https://www.nthround.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nth Round\naid: nth-round\nurl: https://www.nthround.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Terms are applicable to all persons who use or access the Platform and/or the Services, in their company’s\n    capacity or in an individual capacity\nrestricted_uses:\n- summary: Fraudulent or illegal practices\n  text: Engage in any fraudulent, deceptive, or illegal practices or activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Nth Round may, at its\
  \ discretion, decline to offer the Services for any reason, including in the event that\n    the Services enrollment process is not satisfactorily completed\nminimum_age:\n  value: '18'\n  text: User may use the Services only if User is eighteen (18) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/nth-round/eligibility/nth-round-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Nth Round's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Shareholder-Management
- Cap Table
- Private-Business
- Equity-Administration
---
