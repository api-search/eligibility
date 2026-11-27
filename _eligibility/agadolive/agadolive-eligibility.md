---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Participants may use the Service for their individual and personal use.
    type: individual
  - text: Practitioners may use the Service for their individual and commercial use.
    type: business
  minimum_age:
    text: The Service is intended and permitted only for Practitioners and Participants 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: No commercial use by Participants
    text: Participants may not use the Service for commercial or business purposes or for any purpose which was not explicitly permitted by these Terms.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may only use the Service if you were assigned user credentials by us or by a Practitioner and as per the access permission granted to you or to the Practitioner.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AgadoLive
provenance_date: '2026-11-09'
provider_name: AgadoLive
provider_slug: agadolive
slug: agadolive-eligibility
source_date: '2026-11-09'
source_filename: agadolive-eligibility.yml
source_heading: Eligibility
source_page: https://www.agadolive.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgadoLive\naid: agadolive\nurl: https://www.agadolive.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Participants may use the Service for their individual and personal use.\n- type: business\n  text: Practitioners may use the Service for their individual and commercial use.\nrestricted_uses:\n- summary: No commercial use by Participants\n  text: Participants may not use the Service for commercial or business purposes or for any purpose which was not\n    explicitly permitted by these Terms.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: You may only use the Service if you were assigned user credentials by us or by a Practitioner and as per\n    the access permission granted to you or to the Practitioner.\nminimum_age:\n  value: '18'\n  text: The Service is intended and permitted only for Practitioners and Participants 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/agadolive/eligibility/agadolive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from AgadoLive's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Health
- Telehealth
- Rehabilitation
- Physical Therapy
- Computer Vision
- Artificial Intelligence
- Healthcare
---
