---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that all products, services and/or material described on the Site, or the Services available through the Site, are appropriate or available for use in locations outside the United States or all states and territories within the United States.
  minimum_age:
    text: The Services are available for use by children (under 18 years of age), but children are not authorized to become Members and may not use the Services without the supervision and verifiable consent of a parent or legal guardian.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: You may use the Site only for your own personal, non-commercial use.
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
name: Summer Health
provenance_date: '2026-11-10'
provider_name: Summer Health
provider_slug: summer-health
slug: summer-health-eligibility
source_date: '2026-11-10'
source_filename: summer-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.summerhealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Summer Health\naid: summer-health\nurl: https://www.summerhealth.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that all products, services and/or material described on the Site, or the Services\n    available through the Site, are appropriate or available for use in locations outside the United States or all\n    states and territories within the United States.\nentity_types: []\nrestricted_uses:\n- summary: No commercial use\n  text: You may use the Site only for your own personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are available for use by children (under 18 years of age), but children are not authorized\n    to become Members and may not use the Services without the supervision and verifiable consent of a parent or\n    legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/summer-health/eligibility/summer-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Summer Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Pediatrics
- Digital Health
- Blood Testing
- Consumer Health
---
