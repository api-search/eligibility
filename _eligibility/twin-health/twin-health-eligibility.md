---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Services are not available to users located outside the United States.
  entity_types:
  - text: IN ORDER TO USE THE SERVICES, YOU MUST BE AT LEAST 18 YEARS OF AGE AND LOCATED IN THE UNITED STATES.
    type: individual
  - text: In the event that You are a business or other commercial entity accessing the Content and the Services, You understand that the terms of Your arrangement with Twin Health and access of the Content and the Services may be subject to additional terms and conditions set forth in a Master Services Agreement or other written agreement entered into by and between You and Twin Health.
    type: business
  minimum_age:
    text: IN ORDER TO USE THE SERVICES, YOU MUST BE AT LEAST 18 YEARS OF AGE AND LOCATED IN THE UNITED STATES.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: Access the Services and/or the App in any unlawful way or for any unlawful purpose;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We will validate Your right to receive the Services and create an Authorized User account on Your behalf
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Twin Health
provenance_date: '2026-11-10'
provider_name: Twin Health
provider_slug: twin-health
slug: twin-health-eligibility
source_date: '2026-11-10'
source_filename: twin-health-eligibility.yml
source_heading: Eligibility
source_page: https://usa.twinhealth.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Twin Health\naid: twin-health\nurl: https://usa.twinhealth.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: IN ORDER TO USE THE SERVICES, YOU MUST BE AT LEAST 18 YEARS OF AGE AND LOCATED IN THE UNITED STATES.\n- type: business\n  text: In the event that You are a business or other commercial entity accessing the Content and the Services,\n    You understand that the terms of Your arrangement with Twin Health and access of the Content and the Services\n\
  \    may be subject to additional terms and conditions set forth in a Master Services Agreement or other written\n    agreement entered into by and between You and Twin Health.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: Access the Services and/or the App in any unlawful way or for any unlawful purpose;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We will validate Your right to receive the Services and create an Authorized User account on Your behalf\nminimum_age:\n  value: '18'\n  text: IN ORDER TO USE THE SERVICES, YOU MUST BE AT LEAST 18 YEARS OF AGE AND LOCATED IN THE UNITED STATES.\n"
source_yaml_url: https://artifacts.apis.io/twin-health/eligibility/twin-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Twin Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Metabolic Health
- Digital Twin
- Diabetes
- Chronic Care
- Artificial Intelligence
- Health Plans
- Employer Benefits
---
