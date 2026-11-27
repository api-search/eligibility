---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our service is intended for use by individuals who are at least eighteen (18) years of age or such older age as may be required by applicable state laws in the jurisdiction in which an individual accesses the Site.
    type: individual
  minimum_age:
    text: Our service is intended for use by individuals who are at least eighteen (18) years of age or such older age as may be required by applicable state laws
    value: '18'
  restricted_uses:
  - summary: No medical emergencies or diagnosis reliance
    text: IF YOU HAVE A MEDICAL EMERGENCY, IMMEDIATELY CALL YOUR DOCTOR OR DIAL 911.
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
name: Oula Health
provenance_date: '2026-11-10'
provider_name: Oula Health
provider_slug: oula-health
slug: oula-health-eligibility
source_date: '2026-11-10'
source_filename: oula-health-eligibility.yml
source_heading: Eligibility
source_page: https://oulahealth.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oula Health\naid: oula-health\nurl: https://oulahealth.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Our service is intended for use by individuals who are at least eighteen (18) years of age or such older\n    age as may be required by applicable state laws in the jurisdiction in which an individual accesses the Site.\nrestricted_uses:\n- summary: No medical emergencies or diagnosis reliance\n  text: IF YOU HAVE A MEDICAL EMERGENCY, IMMEDIATELY CALL YOUR DOCTOR OR DIAL 911.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our service is intended for use by individuals who are at least eighteen (18) years of age or such older\n    age as may be required by applicable state laws\n"
source_yaml_url: https://artifacts.apis.io/oula-health/eligibility/oula-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Oula Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Maternity Care
- Women's Health
- Healthcare Provider
- Pregnancy
- Digital Health
---
