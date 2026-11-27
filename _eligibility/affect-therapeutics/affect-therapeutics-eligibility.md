---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Certain Services may only be available to Users located in certain states.
  entity_types:
  - text: means an individual user (such as you) who is using the Services
    type: individual
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You will not use the Services to engage in any unlawful behavior
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: to determine whether and to what extent you are eligible to receive any treatment offered by that Provider
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Affect Therapeutics
provenance_date: '2026-11-09'
provider_name: Affect Therapeutics
provider_slug: affect-therapeutics
slug: affect-therapeutics-eligibility
source_date: '2026-11-09'
source_filename: affect-therapeutics-eligibility.yml
source_heading: Eligibility
source_page: https://www.affect.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Affect Therapeutics\naid: affect-therapeutics\nurl: https://www.affect.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Certain Services may only be available to Users located in certain states.\nentity_types:\n- type: individual\n  text: means an individual user (such as you) who is using the Services\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You will not use the Services to engage in any unlawful behavior\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: to determine whether and to what extent you are eligible to receive\
  \ any treatment offered by that Provider\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/affect-therapeutics/eligibility/affect-therapeutics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Affect Therapeutics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Telehealth
- Mental Health
- Behavioral Health
- Substance Use Disorder
- Addiction Treatment
- Medicaid
---
