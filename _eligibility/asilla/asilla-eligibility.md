---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Company and the Subscriber represent and warrant that they have not been, are not, and will not be (1) Anti-social potentials
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Investigating the Product for competitors
    text: When entering into this Agreement for the purpose of investigating the Product, such as our competitors, etc.
  - summary: Antisocial forces
    text: If a major investor, officer or employee of the Subscriber is an antisocial force
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: If, based on the information in the preceding paragraph, the Company determines that use of the Product by an Additional User is appropriate, the Company, the User, and the Additional User shall enter into an agreement
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Asilla
provenance_date: '2026-11-09'
provider_name: Asilla
provider_slug: asilla
slug: asilla-eligibility
source_date: '2026-11-09'
source_filename: asilla-eligibility.yml
source_heading: Eligibility
source_page: https://en.asilla.com/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Asilla\naid: asilla\nurl: https://en.asilla.com/termsofservice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Company and the Subscriber represent and warrant that they have not been, are not, and will not be (1)\n    Anti-social potentials\nrestricted_uses:\n- summary: Investigating the Product for competitors\n  text: When entering into this Agreement for the purpose of investigating the Product, such as our competitors,\n    etc.\n- summary: Antisocial forces\n  text: If a major investor, officer or employee of the Subscriber\
  \ is an antisocial force\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: If, based on the information in the preceding paragraph, the Company determines that use of the Product\n    by an Additional User is appropriate, the Company, the User, and the Additional User shall enter into an agreement\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/asilla/eligibility/asilla-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Asilla's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Behavior-Recognition
- Security
- Video Analytics
---
