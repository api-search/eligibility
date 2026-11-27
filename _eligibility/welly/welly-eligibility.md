---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We control and operate this Site from within the United States of America. While you may access the Site from anywhere within the United States of America, ... this Service is intended to promote only those Welly products that are sold generally by Welly in the United States and its territories and possessions
  entity_types:
  - text: You are of legal age to form a binding contract with Welly
    type: individual
  - text: If you are an individual using the Site on behalf of, or for the benefit of, any corporation, partnership, or other entity with which you are associated (an “Organization”), then you are agreeing to these Terms of Service on behalf of yourself and such Organization
    type: business
  minimum_age:
    text: You are of legal age to form a binding contract with Welly
    value: null
  restricted_uses:
  - summary: Commercial/reseller orders limited
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
name: Welly
provenance_date: '2026-11-10'
provider_name: Welly
provider_slug: welly
slug: welly-eligibility
source_date: '2026-11-10'
source_filename: welly-eligibility.yml
source_heading: Eligibility
source_page: https://www.getwelly.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Welly\naid: welly\nurl: https://www.getwelly.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We control and operate this Site from within the United States of America. While you may access the Site\n    from anywhere within the United States of America, ... this Service is intended to promote only those Welly\n    products that are sold generally by Welly in the United States and its territories and possessions\nentity_types:\n- type: individual\n  text: You are of legal age to form a binding contract with Welly\n- type: business\n  text: If you\
  \ are an individual using the Site on behalf of, or for the benefit of, any corporation, partnership,\n    or other entity with which you are associated (an “Organization”), then you are agreeing to these Terms of Service\n    on behalf of yourself and such Organization\nrestricted_uses:\n- summary: Commercial/reseller orders limited\n  text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers,\n    resellers or distributors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You are of legal age to form a binding contract with Welly\n"
source_yaml_url: https://artifacts.apis.io/welly/eligibility/welly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Welly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Wellness
- Consumer Packaged Goods
- First Aid
- Personal Care
- E-Commerce
- B Corporation
- Retail
---
