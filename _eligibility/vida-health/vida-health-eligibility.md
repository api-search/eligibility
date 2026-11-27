---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Services for use only by persons located in the United States. We make no claims or representations that the Services or any material included in the Services are accessible or appropriate outside of the United States.
  entity_types:
  - text: In these Terms, the terms “you” and “yours” refer to the person using the Services.
    type: individual
  minimum_age:
    text: Our Services are intended for use by you only if you are 18 years of age or over.
    value: '18'
  restricted_uses:
  - summary: Medical emergencies
    text: THE SERVICES ARE NOT INTENDED FOR USE IN A MEDICAL EMERGENCY.
  - summary: Access from outside the US
    text: Access to the Services may not be legal by certain persons or in certain countries.
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
name: Vida Health
provenance_date: '2026-11-10'
provider_name: Vida Health
provider_slug: vida-health
slug: vida-health-eligibility
source_date: '2026-11-10'
source_filename: vida-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.vida.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vida Health\naid: vida-health\nurl: https://www.vida.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Services for use only by persons located in the United States. We make no claims or representations\n    that the Services or any material included in the Services are accessible or appropriate outside of the United\n    States.\nentity_types:\n- type: individual\n  text: In these Terms, the terms “you” and “yours” refer to the person using the Services.\nrestricted_uses:\n- summary: Medical emergencies\n  text: THE SERVICES ARE NOT INTENDED FOR\
  \ USE IN A MEDICAL EMERGENCY.\n- summary: Access from outside the US\n  text: Access to the Services may not be legal by certain persons or in certain countries.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Services are intended for use by you only if you are 18 years of age or over.\n"
source_yaml_url: https://artifacts.apis.io/vida-health/eligibility/vida-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vida Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Virtual Care
- Chronic Care
- Behavioral Health
- Telehealth
- Employee Benefits
- Health Plans
---
