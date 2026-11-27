---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are accepting on behalf of your employer or another entity, you represent and warrant that: (i) you have full legal authority to bind your employer or such entity to these Terms'
    type: business
  - text: “You” means the entity you represent in accepting these Terms or, if that does not apply, you individually.
    type: individual
  minimum_age:
    text: The Cloud Services are not intended for, and should not be used by, anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Weapons proliferation end uses
    text: You agree not to use or provide the Cloud Services for any prohibited end use, including to support any nuclear, chemical, or biological weapons proliferation, or missile technology, without the prior permission of the United States government.
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
name: SendJim
provenance_date: '2026-11-10'
provider_name: SendJim
provider_slug: sendjim
slug: sendjim-eligibility
source_date: '2026-11-10'
source_filename: sendjim-eligibility.yml
source_heading: Eligibility
source_page: https://sendjim.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SendJim\naid: sendjim\nurl: https://sendjim.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are accepting on behalf of your employer or another entity, you represent and warrant that: (i)\n    you have full legal authority to bind your employer or such entity to these Terms'\n- type: individual\n  text: “You” means the entity you represent in accepting these Terms or, if that does not apply, you individually.\nrestricted_uses:\n- summary: Weapons proliferation end uses\n  text: You agree not to use or\
  \ provide the Cloud Services for any prohibited end use, including to support any\n    nuclear, chemical, or biological weapons proliferation, or missile technology, without the prior permission\n    of the United States government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Cloud Services are not intended for, and should not be used by, anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/sendjim/eligibility/sendjim-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SendJim's own page on 2026-11-10.
synthetic: false
tags:
- Marketing
- Direct Mail
- Home Services
- Automation
- Software-as-a-Service
---
