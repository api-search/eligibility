---
api_specs:
- filename: eureka-md-openapi-generated.yml
  format: yaml
  label: Eureka Health API
  slug: eureka-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eureka-md/openapi/_ae-authored/eureka-md-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is intended only for persons located in jurisdictions where the Service and the relevant Provider's professional services may lawfully be offered.
  entity_types:
  - text: You must be at least 18 years old to access or use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to access or use the Service.
    value: '18'
  restricted_uses:
  - summary: No emergencies
    text: DO NOT USE THE SERVICE FOR MEDICAL EMERGENCIES. If you think you may have a medical emergency, call 911 immediately or go to the nearest emergency room.
  - summary: Service not offered for certain care
    text: 'the Service is not offered for: obstetric services; pediatric care; opioid prescribing; pregnancy termination services.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may verify your age, identity, authority, eligibility, and location, and may deny or suspend access for any reason, including if we cannot verify required information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Eureka Health
provenance_date: '2026-11-09'
provider_name: Eureka Health
provider_slug: eureka-md
slug: eureka-md-eligibility
source_date: '2026-11-09'
source_filename: eureka-md-eligibility.yml
source_heading: Eligibility
source_page: https://eureka.md/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eureka Health\naid: eureka-md\nurl: https://eureka.md/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is intended only for persons located in jurisdictions where the Service and the relevant Provider's\n    professional services may lawfully be offered.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to access or use the Service.\nrestricted_uses:\n- summary: No emergencies\n  text: DO NOT USE THE SERVICE FOR MEDICAL EMERGENCIES. If you think you may have a medical emergency, call 911\n    immediately or go to the nearest emergency\
  \ room.\n- summary: Service not offered for certain care\n  text: 'the Service is not offered for: obstetric services; pediatric care; opioid prescribing; pregnancy termination\n    services.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may verify your age, identity, authority, eligibility, and location, and may deny or suspend access for\n    any reason, including if we cannot verify required information.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to access or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/eureka-md/eligibility/eureka-md-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Eureka Health's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Automation
- Claims
- Prior Authorization
- Software-as-a-Service
---
