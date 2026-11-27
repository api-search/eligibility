---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To register an account on the Services, you must be at least 18 years of age (or the age of legal majority in your jurisdiction).
    type: individual
  - text: If you use the Services on behalf of a company, organization, clinician network, or other entity
    type: business
  minimum_age:
    text: To register an account on the Services, you must be at least 18 years of age (or the age of legal majority in your jurisdiction).
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: you will only use the Services for lawful purposes
  - summary: Prescriptions must be medically necessary
    text: you may only submit prescriptions for healthcare products and equipment through the Services that you believe are medically necessary for the applicable patient
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must be a licensed Clinician in the United States (or authorized clinician staff of such Clinician) or you must be an authorized member of a supplier registered with Parachute in order to use the Portal.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Parachute Health
provenance_date: '2026-11-10'
provider_name: Parachute Health
provider_slug: parachute-health
slug: parachute-health-eligibility
source_date: '2026-11-10'
source_filename: parachute-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.parachutehealth.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Parachute Health\naid: parachute-health\nurl: https://www.parachutehealth.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To register an account on the Services, you must be at least 18 years of age (or the age of legal majority\n    in your jurisdiction).\n- type: business\n  text: If you use the Services on behalf of a company, organization, clinician network, or other entity\nrestricted_uses:\n- summary: Lawful use only\n  text: you will only use the Services for lawful purposes\n- summary: Prescriptions must\
  \ be medically necessary\n  text: you may only submit prescriptions for healthcare products and equipment through the Services that you believe\n    are medically necessary for the applicable patient\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must be a licensed Clinician in the United States (or authorized clinician staff of such Clinician)\n    or you must be an authorized member of a supplier registered with Parachute in order to use the Portal.\nminimum_age:\n  value: '18'\n  text: To register an account on the Services, you must be at least 18 years of age (or the age of legal majority\n    in your jurisdiction).\n"
source_yaml_url: https://artifacts.apis.io/parachute-health/eligibility/parachute-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Parachute Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- DME
- e-Prescribing
- Medical Equipment
- Health IT
- Interoperability
- FHIR
- HL7
- Prior Authorization
---
