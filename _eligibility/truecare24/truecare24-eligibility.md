---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are only eligible to use our App or Website if you are located within our service area, which is available in detail on the Website.
  entity_types:
  - text: You must be at least 18 (eighteen) years of age to use the App or Website.
    type: individual
  minimum_age:
    text: You must be at least 18 (eighteen) years of age to use the App or Website.
    value: '18'
  restricted_uses:
  - summary: Discount medical plan limited to California residents
    text: Only available to CA residents.
  - summary: No sign-up or requests under a false name
    text: You shall not sign up, contact or request a Medical Services Provider under a false name.
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
name: TrueCare24
provenance_date: '2026-11-10'
provider_name: TrueCare24
provider_slug: truecare24
slug: truecare24-eligibility
source_date: '2026-11-10'
source_filename: truecare24-eligibility.yml
source_heading: Eligibility
source_page: https://www.truecare24.com/terms-service-truecare24/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrueCare24\naid: truecare24\nurl: https://www.truecare24.com/terms-service-truecare24/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are only eligible to use our App or Website if you are located within our service area, which is available\n    in detail on the Website.\nentity_types:\n- type: individual\n  text: You must be at least 18 (eighteen) years of age to use the App or Website.\nrestricted_uses:\n- summary: Discount medical plan limited to California residents\n  text: Only available to CA residents.\n- summary: No sign-up or requests under a false name\n  text: You\
  \ shall not sign up, contact or request a Medical Services Provider under a false name.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 (eighteen) years of age to use the App or Website.\n"
source_yaml_url: https://artifacts.apis.io/truecare24/eligibility/truecare24-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from TrueCare24's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Home Care
- Healthcare Staffing
- Vaccinations
- Behavioral Health
---
