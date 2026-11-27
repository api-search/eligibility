---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Site and/or the Services is limited exclusively to users located in States within the United States where the Services are available. Services are not available to users located outside the United States.
  entity_types:
  - text: This Site is offered and available to users who are 18 years of age or older and reside in the United States or any of its territories or possessions.
    type: individual
  minimum_age:
    text: This Site is offered and available to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No emergencies
    text: Meru Health’s Site and Services are not for medical emergencies or urgent situations.
  - summary: No controlled substances prescribed
    text: Providers do not provide or prescribe medications or pharmacological products, including any DEA controlled substances or scheduled medications
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
name: Meru Health
provenance_date: '2026-11-10'
provider_name: Meru Health
provider_slug: meru-health
slug: meru-health-eligibility
source_date: '2026-11-10'
source_filename: meru-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.meruhealth.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meru Health\naid: meru-health\nurl: https://www.meruhealth.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Site and/or the Services is limited exclusively to users located in States within\n    the United States where the Services are available. Services are not available to users located outside the\n    United States.\nentity_types:\n- type: individual\n  text: This Site is offered and available to users who are 18 years of age or older and reside in the United States\n    or any of its territories or possessions.\nrestricted_uses:\n\
  - summary: No emergencies\n  text: Meru Health’s Site and Services are not for medical emergencies or urgent situations.\n- summary: No controlled substances prescribed\n  text: Providers do not provide or prescribe medications or pharmacological products, including any DEA controlled\n    substances or scheduled medications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Site is offered and available to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/meru-health/eligibility/meru-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Meru Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Tech
- Mental Health
- Digital Health
- Telehealth
- Behavioral Health
- Wellness
---
