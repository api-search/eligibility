---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You are a resident of the United States and physically located in the United States when using the Services; You are not located in, or a resident of, a country that is subject to a U.S. Government embargo
  entity_types:
  - text: The Services are designed to provide individuals who access or register as users of the Services
    type: individual
  minimum_age:
    text: You are at least 18 years old and are otherwise legally qualified to enter into and form contracts under applicable law
    value: '18'
  restricted_uses:
  - summary: Emergencies not supported
    text: THE SERVICES CANNOT AND ARE NOT DESIGNED, INTENDED, OR APPROPRIATE TO ADDRESS SERIOUS, EMERGENT, OR LIFE-THREATENING MEDICAL CONDITIONS AND SHOULD NOT BE USED IN THOSE CIRCUMSTANCES.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You can access the services by logging in to the Platform using your phone number, date of birth, last name, and in some cases, the last four digits of your social security number.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rovi Health
provenance_date: '2026-11-10'
provider_name: Rovi Health
provider_slug: rovi-health
slug: rovi-health-eligibility
source_date: '2026-11-10'
source_filename: rovi-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.rovi.health/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rovi Health\naid: rovi-health\nurl: https://www.rovi.health/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You are a resident of the United States and physically located in the United States when using the Services;\n    You are not located in, or a resident of, a country that is subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: The Services are designed to provide individuals who access or register as users of the Services\nrestricted_uses:\n- summary: Emergencies not supported\n  text: THE SERVICES CANNOT AND ARE NOT DESIGNED,\
  \ INTENDED, OR APPROPRIATE TO ADDRESS SERIOUS, EMERGENT, OR LIFE-THREATENING\n    MEDICAL CONDITIONS AND SHOULD NOT BE USED IN THOSE CIRCUMSTANCES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You can access the services by logging in to the Platform using your phone number, date of birth, last name,\n    and in some cases, the last four digits of your social security number.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old and are otherwise legally qualified to enter into and form contracts under\n    applicable law\n"
source_yaml_url: https://artifacts.apis.io/rovi-health/eligibility/rovi-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Rovi Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Health Insurance
- Care Navigation
- Employer Benefits
- Telehealth
---
