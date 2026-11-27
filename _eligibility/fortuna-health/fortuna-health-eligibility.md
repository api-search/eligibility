---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Site and/or the Services is limited exclusively to users located in States within the United States where the Services are available. Services are not available to users located outside the United States.
  entity_types:
  - text: Fortuna's Services are only available to individuals 18 years of age and older who are located in a jurisdiction in which the Services are offered.
    type: individual
  minimum_age:
    text: Fortuna's Services are only available to individuals 18 years of age and older
    value: '18'
  restricted_uses:
  - summary: Emergency use
    text: NOT FOR USE IN CASE OF EMERGENCY
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
name: Fortuna Health
provenance_date: '2026-11-09'
provider_name: Fortuna Health
provider_slug: fortuna-health
slug: fortuna-health-eligibility
source_date: '2026-11-09'
source_filename: fortuna-health-eligibility.yml
source_heading: Eligibility
source_page: https://app.fortunahealth.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fortuna Health\naid: fortuna-health\nurl: https://app.fortunahealth.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Site and/or the Services is limited exclusively to users located in States within\n    the United States where the Services are available. Services are not available to users located outside the\n    United States.\nentity_types:\n- type: individual\n  text: Fortuna's Services are only available to individuals 18 years of age and older who are located in a jurisdiction\n    in which the Services are offered.\nrestricted_uses:\n\
  - summary: Emergency use\n  text: NOT FOR USE IN CASE OF EMERGENCY\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Fortuna's Services are only available to individuals 18 years of age and older\n"
source_yaml_url: https://artifacts.apis.io/fortuna-health/eligibility/fortuna-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Fortuna Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medicaid
- Health Insurance
- Benefits Enrollment
- Government Benefits
- Digital Health
- Health Tech
---
