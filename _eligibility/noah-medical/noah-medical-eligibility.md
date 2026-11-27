---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States. We make no representation that the Site is appropriate or available for use outside of the United States.
  entity_types:
  - text: You must be at least 18 years old to use the Site.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Site.
    value: '18'
  restricted_uses:
  - summary: Illegal access or use
    text: Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.
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
name: Noah Medical
provenance_date: '2026-11-10'
provider_name: Noah Medical
provider_slug: noah-medical
slug: noah-medical-eligibility
source_date: '2026-11-10'
source_filename: noah-medical-eligibility.yml
source_heading: Eligibility
source_page: https://www.noahmed.com/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Noah Medical\naid: noah-medical\nurl: https://www.noahmed.com/website-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States. We make no representation that the Site\n    is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Site.\nrestricted_uses:\n- summary: Illegal access or use\n  text: Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/noah-medical/eligibility/noah-medical-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Noah Medical's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medical Devices
- Surgical Robotics
- Robotics
- Bronchoscopy
- Interventional Pulmonology
- Medical Technology
---
