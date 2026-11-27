---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are a customer in the US, you are contracting with BlueSnap, Inc. based in the US
  entity_types:
  - text: By using this Site or the Services found at this Site, you represent and warrant that you are (i) at least eighteen (18) years of age and/or (ii) otherwise recognized as being able to form legally binding contracts under applicable law.
    type: individual
  - text: If you are entering into this Agreement on behalf of a corporate entity, you represent and warrant that you have the legal authority to bind such corporate entity to the terms and conditions contained in this Agreement.
    type: business
  minimum_age:
    text: you are (i) at least eighteen (18) years of age and/or (ii) otherwise recognized as being able to form legally binding contracts under applicable law.
    value: '18'
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
name: BlueSnap
provenance_date: '2026-11-09'
provider_name: BlueSnap
provider_slug: bluesnap
slug: bluesnap-eligibility
source_date: '2026-11-09'
source_filename: bluesnap-eligibility.yml
source_heading: Eligibility
source_page: https://www.bluesnap.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlueSnap\naid: bluesnap\nurl: https://www.bluesnap.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are a customer in the US, you are contracting with BlueSnap, Inc. based in the US\nentity_types:\n- type: individual\n  text: By using this Site or the Services found at this Site, you represent and warrant that you are (i) at least\n    eighteen (18) years of age and/or (ii) otherwise recognized as being able to form legally binding contracts\n    under applicable law.\n- type: business\n  text: If you are entering into this Agreement on behalf of a\
  \ corporate entity, you represent and warrant that\n    you have the legal authority to bind such corporate entity to the terms and conditions contained in this Agreement.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are (i) at least eighteen (18) years of age and/or (ii) otherwise recognized as being able to form legally\n    binding contracts under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/bluesnap/eligibility/bluesnap-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from BlueSnap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Global Payments
---
