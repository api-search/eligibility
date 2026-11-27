---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You are at least 18 years old or have been legally emancipated
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You may use the Services only for lawful purposes and in accordance with these Terms.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Once We determine that You are eligible, You will receive an email inviting You to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Salvo Health
provenance_date: '2026-11-10'
provider_name: Salvo Health
provider_slug: salvo-health
slug: salvo-health-eligibility
source_date: '2026-11-10'
source_filename: salvo-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.salvohealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Salvo Health\naid: salvo-health\nurl: https://www.salvohealth.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: You may use the Services only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Once We determine that You are eligible, You will receive an email inviting You to register to use the Services.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old or have been legally emancipated\n"
source_yaml_url: https://artifacts.apis.io/salvo-health/eligibility/salvo-health-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Salvo Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Gastrointestinal
- Metabolic Health
- Remote Patient Monitoring
- Virtual Care
- EHR Integration
---
