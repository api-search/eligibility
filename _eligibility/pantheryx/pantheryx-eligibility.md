---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    source: https://pantheryx.com/terms-and-conditions/
    text: you are a resident of the United States of America
  entity_types:
  - text: you represent that you are at least the age of majority in your state or province of residence
    type: individual
  - source: https://pantheryx.com/terms-and-conditions/
    text: you represent that you are at least eighteen (18) years old or the legal age of majority in your jurisdiction, whichever is greater
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use our products for any illegal or unauthorized purpose
  - summary: Orders by dealers or resellers
    text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers, resellers or distributors.
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
name: PanTheryx
provenance_date: '2026-11-10'
provider_name: PanTheryx
provider_slug: pantheryx
slug: pantheryx-eligibility
source_date: '2026-11-10'
source_filename: pantheryx-eligibility.yml
source_heading: Eligibility
source_page: https://www.lifesfirstnaturals.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PanTheryx\naid: pantheryx\nurl: https://www.lifesfirstnaturals.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://pantheryx.com/terms-and-conditions/\n  - https://www.lifesfirstnaturals.com/policies/terms-of-service\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you are a resident of the United States of America\n  source: https://pantheryx.com/terms-and-conditions/\nentity_types:\n- type: individual\n  text: you represent that you are at least the age of majority in your state or province of residence\n- type: individual\n  text: you represent that you are at least eighteen\
  \ (18) years old or the legal age of majority in your jurisdiction,\n    whichever is greater\n  source: https://pantheryx.com/terms-and-conditions/\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use our products for any illegal or unauthorized purpose\n- summary: Orders by dealers or resellers\n  text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers,\n    resellers or distributors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/pantheryx/eligibility/pantheryx-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from PanTheryx's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Nutrition
- Biotechnology
- Life Sciences
- Consumer Health
- Dietary Supplements
- Colostrum
- Animal Health
- E-Commerce
- Agentic Commerce
---
