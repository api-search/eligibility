---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are made available to “Providers” (as defined in 45 CFR §160.103) and to members of a Provider’s Authorized Workforce
    type: other
  - text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH COMPANY
    type: individual
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH COMPANY
    value: legal age to form a binding contract
  restricted_uses:
  - summary: PHI access limited to treatment relationships
    text: you may access only information pertaining to individuals with whom you have a treatment relationship
  - summary: No third-party access to Services
    text: Except as required by law, you will not permit any third party (other than persons who satisfy the definition of Authorized Workforce) to use or access the Services without our prior written agreement.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification of information applicable to a purchase may be required prior to our acceptance of any order.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Virgo
provenance_date: '2026-11-10'
provider_name: Virgo
provider_slug: virgo
slug: virgo-eligibility
source_date: '2026-11-10'
source_filename: virgo-eligibility.yml
source_heading: Eligibility
source_page: https://virgosvs.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Virgo\naid: virgo\nurl: https://virgosvs.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: The Services are made available to “Providers” (as defined in 45 CFR §160.103) and to members of a Provider’s\n    Authorized Workforce\n- type: individual\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH COMPANY\nrestricted_uses:\n- summary: PHI access limited to treatment relationships\n  text: you may access only information pertaining to individuals with whom you have a treatment relationship\n- summary:\
  \ No third-party access to Services\n  text: Except as required by law, you will not permit any third party (other than persons who satisfy the definition\n    of Authorized Workforce) to use or access the Services without our prior written agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification of information applicable to a purchase may be required prior to our acceptance of any order.\nminimum_age:\n  value: legal age to form a binding contract\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH COMPANY\n"
source_yaml_url: https://artifacts.apis.io/virgo/eligibility/virgo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Virgo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Healthcare
- Life Sciences
- Endoscopy
- Gastroenterology
- Clinical Trials
- Medical Imaging
- Foundation Models
---
