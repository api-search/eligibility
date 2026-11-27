---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site may not be appropriate or available for use in jurisdictions outside of the United States.
  entity_types:
  - text: limited personal license to access the Site for your lawful personal and noncommercial uses
    type: individual
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO ENTER INTO THESE TERMS OR, IF YOU ARE NOT OF LEGAL AGE, YOU HAVE OBTAINED PARENTAL OR GUARDIAN CONSENT TO ENTER INTO THESE TERMS.
    value: null
  restricted_uses:
  - summary: Noncommercial use only
    text: limited personal license to access the Site for your lawful personal and noncommercial uses
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
name: Pi Health
provenance_date: '2026-11-10'
provider_name: Pi Health
provider_slug: pi-health
slug: pi-health-eligibility
source_date: '2026-11-10'
source_filename: pi-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.pihealth.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pi Health\naid: pi-health\nurl: https://www.pihealth.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site may not be appropriate or available for use in jurisdictions outside of the United States.\nentity_types:\n- type: individual\n  text: limited personal license to access the Site for your lawful personal and noncommercial uses\nrestricted_uses:\n- summary: Noncommercial use only\n  text: limited personal license to access the Site for your lawful personal and noncommercial uses\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: YOU ARE OF LEGAL AGE TO ENTER INTO THESE TERMS OR, IF YOU ARE NOT OF LEGAL AGE, YOU HAVE OBTAINED PARENTAL\n    OR GUARDIAN CONSENT TO ENTER INTO THESE TERMS.\n"
source_yaml_url: https://artifacts.apis.io/pi-health/eligibility/pi-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pi Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Clinical Trials
- Clinical Research
- Healthcare
- Life Sciences
- Oncology
- Contract Research Organization
- EDC
- CTMS
- Artificial Intelligence
---
