---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Dealer/reseller orders
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
name: STAND+
provenance_date: '2026-11-10'
provider_name: STAND+
provider_slug: stand
slug: stand-eligibility
source_date: '2026-11-10'
source_filename: stand-eligibility.yml
source_heading: Eligibility
source_page: https://www.standshoes.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: STAND+\naid: stand\nurl: https://www.standshoes.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: Dealer/reseller orders\n  text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers,\n    resellers or distributors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/stand/eligibility/stand-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from STAND+'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Footwear
- Consumer Products
- E-Commerce
- Health
- Wearables
- Recovery
- Retail
---
