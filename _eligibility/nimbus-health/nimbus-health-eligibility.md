---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you reside in the United States, these Terms are governed by the laws of the State of Georgia
  entity_types:
  - text: You can create the Account by providing us with, at minimum, your email address and a password.
    type: individual
  - text: “Healthcare Professional” means a healthcare provider or a healthcare practitioner including, without limitation a clinician, principal investigator, investigator, general practitioner, pharmacist, nurse, respiratory therapist, caregiver, healthcare educator, clinical research organization, research institution.
    type: individual
  minimum_age:
    text: You represent that you are at least the age of majority in your place of residence and that all information you submit is accurate.
    value: age of majority in place of residence
  restricted_uses:
  - summary: Designated Purpose only
    text: You must use the Services for their Designated Purpose only
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
name: Nimbus Health
provenance_date: '2026-11-10'
provider_name: Nimbus Health
provider_slug: nimbus-health
slug: nimbus-health-eligibility
source_date: '2026-11-10'
source_filename: nimbus-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.nimbushealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nimbus Health\naid: nimbus-health\nurl: https://www.nimbushealth.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you reside in the United States, these Terms are governed by the laws of the State of Georgia\nentity_types:\n- type: individual\n  text: You can create the Account by providing us with, at minimum, your email address and a password.\n- type: individual\n  text: “Healthcare Professional” means a healthcare provider or a healthcare practitioner including, without limitation\n    a clinician, principal investigator, investigator, general practitioner, pharmacist,\
  \ nurse, respiratory therapist,\n    caregiver, healthcare educator, clinical research organization, research institution.\nrestricted_uses:\n- summary: Designated Purpose only\n  text: You must use the Services for their Designated Purpose only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in place of residence\n  text: You represent that you are at least the age of majority in your place of residence and that all information\n    you submit is accurate.\n"
source_yaml_url: https://artifacts.apis.io/nimbus-health/eligibility/nimbus-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Nimbus Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Pulmonary Care
- Respiratory
- Clinics
- Health Tech
---
