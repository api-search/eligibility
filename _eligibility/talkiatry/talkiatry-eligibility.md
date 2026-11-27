---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Use of this Platform is limited to users located in states within the United States where the Platform is available. Services are not available for users located outside of the United States.
  entity_types:
  - text: You must be 18 years or older or have obtained permission from your parent or legal guardian prior to using our Platform.
    type: individual
  minimum_age:
    text: You must be 18 years or older or have obtained permission from your parent or legal guardian prior to using our Platform.
    value: '18'
  restricted_uses:
  - summary: Commercial exploitation
    text: Accessing or using any part of the Platform, services, or materials for outsourcing, service bureau purposes, commercial exploitation, or for the benefit of unaffiliated third parties who pay directly for such benefit is not permitted without explicit written consent from Talkiatry.
  - summary: Sanctioned jurisdictions
    text: By using the Services, you confirm that you are not in a U.S.-sanctioned country or on any U.S. Government restricted list.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may request additional verification or information before confirming any appointment.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Talkiatry
provenance_date: '2026-11-10'
provider_name: Talkiatry
provider_slug: talkiatry
slug: talkiatry-eligibility
source_date: '2026-11-10'
source_filename: talkiatry-eligibility.yml
source_heading: Eligibility
source_page: https://www.talkiatry.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Talkiatry\naid: talkiatry\nurl: https://www.talkiatry.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Use of this Platform is limited to users located in states within the United States where the Platform is\n    available. Services are not available for users located outside of the United States.\nentity_types:\n- type: individual\n  text: You must be 18 years or older or have obtained permission from your parent or legal guardian prior to using\n    our Platform.\nrestricted_uses:\n- summary: Commercial exploitation\n  text: Accessing or using any part of\
  \ the Platform, services, or materials for outsourcing, service bureau purposes,\n    commercial exploitation, or for the benefit of unaffiliated third parties who pay directly for such benefit\n    is not permitted without explicit written consent from Talkiatry.\n- summary: Sanctioned jurisdictions\n  text: By using the Services, you confirm that you are not in a U.S.-sanctioned country or on any U.S. Government\n    restricted list.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may request additional verification or information before confirming any appointment.\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older or have obtained permission from your parent or legal guardian prior to using\n    our Platform.\n"
source_yaml_url: https://artifacts.apis.io/talkiatry/eligibility/talkiatry-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Talkiatry's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Mental Health
- Telehealth
- Telepsychiatry
- Psychiatry
- Behavioral Health
- Digital Health
---
