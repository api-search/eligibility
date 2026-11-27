---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: The ANTIX token is exclusively intended for non-U.S. persons and is strictly not available to U.S. citizens, U.S. residents, or any entities organized or domiciled in the United States.
  entity_types:
  - text: You are at least 18 years of age . The Platform is for adults only, and we ask you to confirm your age when you sign up
    type: individual
  - text: If you are accessing the Platform on behalf of a company, organization, or other legal entity, you represent that you have the authority to bind that entity to these Terms, in which case "you" refers to that entity.
    type: business
  minimum_age:
    text: You are at least 18 years of age . The Platform is for adults only
    value: '18'
  restricted_uses:
  - summary: Deepfakes and CSAM
    text: You may not use AI generation tools to produce content that violates our Acceptable Use Policy, including deepfakes of real identifiable individuals without their documented consent, synthetic child sexual abuse material (CSAM) of any kind
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AIGE
provenance_date: '2026-11-09'
provider_name: AIGE
provider_slug: aige-ws
slug: aige-ws-eligibility
source_date: '2026-11-09'
source_filename: aige-ws-eligibility.yml
source_heading: Eligibility
source_page: https://aige.ws/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIGE\naid: aige-ws\nurl: https://aige.ws/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  text: The ANTIX token is exclusively intended for non-U.S. persons and is strictly not available to U.S. citizens,\n    U.S. residents, or any entities organized or domiciled in the United States.\nentity_types:\n- type: individual\n  text: You are at least 18 years of age . The Platform is for adults only, and we ask you to confirm your age when\n    you sign up\n- type: business\n  text: If you are accessing the Platform on behalf of a company, organization, or other legal entity,\
  \ you represent\n    that you have the authority to bind that entity to these Terms, in which case \"you\" refers to that entity.\nrestricted_uses:\n- summary: Deepfakes and CSAM\n  text: You may not use AI generation tools to produce content that violates our Acceptable Use Policy, including\n    deepfakes of real identifiable individuals without their documented consent, synthetic child sexual abuse material\n    (CSAM) of any kind\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age . The Platform is for adults only\n"
source_yaml_url: https://artifacts.apis.io/aige-ws/eligibility/aige-ws-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AIGE's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Image Generation
- Video Generation
- Branding
- Platform
---
