---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are intended solely for use by individuals located in the United States.
  entity_types:
  - text: By using the Services, you represent and warrant that you located in the United States, you are at least 18 years of age or the age of legal majority in your jurisdiction and have the legal capacity to enter into a binding agreement with us.
    type: individual
  minimum_age:
    text: The Services are not intended for use by persons under the age of 18 except as authorized through a parent, guardian, conservator, or custodian who has accepted these Terms.
    value: '18'
  restricted_uses:
  - summary: Not for medical emergencies
    text: YOU AGREE THAT THE SERVICES ARE NOT INTENDED TO BE USED IN A MEDICAL EMERGENCY.
  - summary: Non-commercial use only
    text: You may use the Services only for your own personal, non-commercial use.
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
name: Brightline
provenance_date: '2026-11-09'
provider_name: Brightline
provider_slug: brightline
slug: brightline-eligibility
source_date: '2026-11-09'
source_filename: brightline-eligibility.yml
source_heading: Eligibility
source_page: https://www.brightline.com/policies-and-terms/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brightline\naid: brightline\nurl: https://www.brightline.com/policies-and-terms/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are intended solely for use by individuals located in the United States.\nentity_types:\n- type: individual\n  text: By using the Services, you represent and warrant that you located in the United States, you are at least\n    18 years of age or the age of legal majority in your jurisdiction and have the legal capacity to enter into\n    a binding agreement with us.\nrestricted_uses:\n- summary: Not for medical emergencies\n\
  \  text: YOU AGREE THAT THE SERVICES ARE NOT INTENDED TO BE USED IN A MEDICAL EMERGENCY.\n- summary: Non-commercial use only\n  text: You may use the Services only for your own personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not intended for use by persons under the age of 18 except as authorized through a parent,\n    guardian, conservator, or custodian who has accepted these Terms.\n"
source_yaml_url: https://artifacts.apis.io/brightline/eligibility/brightline-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Brightline's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Life Sciences
- Health
- Mental Health
- Pediatrics
- Telehealth
- Behavioral Health
- Healthcare
---
