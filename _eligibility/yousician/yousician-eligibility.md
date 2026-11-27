---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are the age of majority in your country of residence or are otherwise authorized to enter into binding agreements
    type: individual
  minimum_age:
    text: you represent that you are the age of majority in your country of residence
    value: null
  restricted_uses:
  - summary: Commercial activities prohibited
    text: use the Services for any commercial activities, including, without limitation, any attempt to raise money for anyone or advertising or promoting a product, service, pyramid scheme or other multi-tiered marketing scheme
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Yousician reserves the right to refuse or limit the registration for any legitimate reason, such as, but not limited to, non-compliance with eligibility requirements or prior violation of these Terms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Yousician
provenance_date: '2026-11-10'
provider_name: Yousician
provider_slug: yousician
slug: yousician-eligibility
source_date: '2026-11-10'
source_filename: yousician-eligibility.yml
source_heading: Eligibility
source_page: https://yousician.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yousician\naid: yousician\nurl: https://yousician.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are the age of majority in your country of residence or are otherwise authorized to enter into binding\n    agreements\nrestricted_uses:\n- summary: Commercial activities prohibited\n  text: use the Services for any commercial activities, including, without limitation, any attempt to raise money\n    for anyone or advertising or promoting a product, service, pyramid scheme or other multi-tiered marketing scheme\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Yousician reserves the right to refuse or limit the registration for any legitimate reason, such as, but\n    not limited to, non-compliance with eligibility requirements or prior violation of these Terms.\nminimum_age:\n  value: null\n  text: you represent that you are the age of majority in your country of residence\n"
source_yaml_url: https://artifacts.apis.io/yousician/eligibility/yousician-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Yousician's own page on 2026-11-10.
synthetic: false
tags:
- Music
- Education
- Learning
- Gaming
- Platform
- Company
---
