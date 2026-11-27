---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Platform is limited exclusively to users located in states within the United States where the Platform is available. Services are not available to users located outside the United States.
  minimum_age:
    text: you represent and warrant that you are 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: These Terms of Use permit you to use the Platform for your personal, non-commercial use only.
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
name: Parsley Health
provenance_date: '2026-11-10'
provider_name: Parsley Health
provider_slug: parsley-health
slug: parsley-health-eligibility
source_date: '2026-11-10'
source_filename: parsley-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.parsleyhealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Parsley Health\naid: parsley-health\nurl: https://www.parsleyhealth.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Platform is limited exclusively to users located in states within the United States\n    where the Platform is available. Services are not available to users located outside the United States.\nentity_types: []\nrestricted_uses:\n- summary: Personal use only\n  text: These Terms of Use permit you to use the Platform for your personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/parsley-health/eligibility/parsley-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Parsley Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Functional Medicine
- Primary Care
- Wellness
- Nutrition
- Diagnostics
- Lab Testing
- Membership
- Digital Health
- Consumer Health
- E-Commerce
- Agentic Commerce
- MCP
- Supplements
---
