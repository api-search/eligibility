---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Your use of Services is restricted to... (no country list stated; China PoPs subject to Chinese regulations per Section 9)
  entity_types:
  - text: You, as an individual or business entity/organization that legally operates in your jurisdiction, have the right to use the Services provided by the Company.
    type: individual
  - text: If you are signing for and/or are a representative for a business entity, you represent and warrant that you are duly authorized by the business entity to accept these terms and conditions
    type: business
  minimum_age:
    text: Services are available only to those individuals or business entities who can form legally binding contracts under the laws applicable.
    value: null
  restricted_uses:
  - summary: China PoP content restrictions
    text: You hereby represent and warrant not to produce, copy, publish and transmit information having the contents as follows by using telecommunication networks
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
name: CDNetworks
provenance_date: '2026-11-09'
provider_name: CDNetworks
provider_slug: cdnetworks
slug: cdnetworks-eligibility
source_date: '2026-11-09'
source_filename: cdnetworks-eligibility.yml
source_heading: Eligibility
source_page: https://docs.cdnetworks.com/en/legal/docs/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CDNetworks\naid: cdnetworks\nurl: https://docs.cdnetworks.com/en/legal/docs/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Your use of Services is restricted to... (no country list stated; China PoPs subject to Chinese regulations\n    per Section 9)\nentity_types:\n- type: individual\n  text: You, as an individual or business entity/organization that legally operates in your jurisdiction, have the\n    right to use the Services provided by the Company.\n- type: business\n  text: If you are signing for and/or are a representative for a business entity, you represent\
  \ and warrant that\n    you are duly authorized by the business entity to accept these terms and conditions\nrestricted_uses:\n- summary: China PoP content restrictions\n  text: You hereby represent and warrant not to produce, copy, publish and transmit information having the contents\n    as follows by using telecommunication networks\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Services are available only to those individuals or business entities who can form legally binding contracts\n    under the laws applicable.\n"
source_yaml_url: https://artifacts.apis.io/cdnetworks/eligibility/cdnetworks-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from CDNetworks's own page on 2026-11-09.
synthetic: false
tags:
- CDN
- Cloud Services
- Web Acceleration
- DDoS Protection
- Edge Computing
---
