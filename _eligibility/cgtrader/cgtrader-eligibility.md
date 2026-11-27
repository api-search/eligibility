---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual 18 years or older who can form legally binding contracts
    type: individual
  - text: you are a legal entity or an individual 18 years or older who can form legally binding contracts
    type: business
  minimum_age:
    text: an individual 18 years or older who can form legally binding contracts
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons barred
    text: This Site may not be accessed or used by any person, entity or group that have been designated for sanctions under the economic sanctions laws
  - summary: Weapon replica 3D models barred
    text: is printable 3D models, which are replicas or realistic depictions of weapons;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By signing up to this Site you agree to register using a valid email address that you are entitled to use
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cgtrader
provenance_date: '2026-11-09'
provider_name: Cgtrader
provider_slug: cgtrader
slug: cgtrader-eligibility
source_date: '2026-11-09'
source_filename: cgtrader-eligibility.yml
source_heading: Eligibility
source_page: https://www.cgtrader.com/pages/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cgtrader\naid: cgtrader\nurl: https://www.cgtrader.com/pages/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual 18 years or older who can form legally binding contracts\n- type: business\n  text: you are a legal entity or an individual 18 years or older who can form legally binding contracts\nrestricted_uses:\n- summary: Sanctioned persons barred\n  text: This Site may not be accessed or used by any person, entity or group that have been designated for sanctions\n    under the economic\
  \ sanctions laws\n- summary: Weapon replica 3D models barred\n  text: is printable 3D models, which are replicas or realistic depictions of weapons;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By signing up to this Site you agree to register using a valid email address that you are entitled to use\nminimum_age:\n  value: '18'\n  text: an individual 18 years or older who can form legally binding contracts\n"
source_yaml_url: https://artifacts.apis.io/cgtrader/eligibility/cgtrader-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Cgtrader's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- 3D Models
- Artificial Intelligence
- Community
---
