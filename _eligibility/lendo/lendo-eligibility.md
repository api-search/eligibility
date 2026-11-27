---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - SA
    text: Lendo is operated by a Saudi company under the laws of the Kingdom of Saudi Arabia; the page does not list served countries explicitly.
  entity_types:
  - text: To access the website, you must be at least 18 years old, as per the Gregorian calendar.
    type: individual
  minimum_age:
    text: To access the website, you must be at least 18 years old, as per the Gregorian calendar.
    value: '18'
  restricted_uses:
  - summary: Fraudulent or illegal use
    text: Users must not use this website in any way that causes or may cause damage to the website or impairs its availability or accessibility, or in any way that is illegal, unlawful, fraudulent, harmful, or connected to any illegal, unlawful, fraudulent, or harmful activity.
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
name: Lendo
provenance_date: '2026-11-09'
provider_name: Lendo
provider_slug: lendo
slug: lendo-eligibility
source_date: '2026-11-09'
source_filename: lendo-eligibility.yml
source_heading: Eligibility
source_page: https://www.lendo.sa/en/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lendo\naid: lendo\nurl: https://www.lendo.sa/en/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SA\n  excluded: []\n  text: Lendo is operated by a Saudi company under the laws of the Kingdom of Saudi Arabia; the page does not list\n    served countries explicitly.\nentity_types:\n- type: individual\n  text: To access the website, you must be at least 18 years old, as per the Gregorian calendar.\nrestricted_uses:\n- summary: Fraudulent or illegal use\n  text: Users must not use this website in any way that causes or may cause damage to the website or impairs its\n    availability or accessibility,\
  \ or in any way that is illegal, unlawful, fraudulent, harmful, or connected to\n    any illegal, unlawful, fraudulent, or harmful activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To access the website, you must be at least 18 years old, as per the Gregorian calendar.\n"
source_yaml_url: https://artifacts.apis.io/lendo/eligibility/lendo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Lendo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Lending
- Crowdfunding
- Invoice Financing
- SME Finance
- Islamic Finance
- Saudi Arabia
- Middle East
---
