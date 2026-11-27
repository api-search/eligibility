---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Persons under 18 years of age may use the Services only in conjunction with and under the supervision of a parent or legal guardian.
    type: individual
  - text: If you are using the Services on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: Persons under 18 years of age may use the Services only in conjunction with and under the supervision of a parent or legal guardian.
    value: null
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
name: Ello
provenance_date: '2026-11-09'
provider_name: Ello
provider_slug: ello
slug: ello-eligibility
source_date: '2026-11-09'
source_filename: ello-eligibility.yml
source_heading: Eligibility
source_page: https://www.ello.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ello\naid: ello\nurl: https://www.ello.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Persons under 18 years of age may use the Services only in conjunction with and under the supervision of\n    a parent or legal guardian.\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent and warrant that you have the\n    authority to bind that organization to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: Persons under 18 years of age may use the Services only in conjunction with and under the supervision of\n    a parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/ello/eligibility/ello-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Ello's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Education
- EdTech
- Reading
- Literacy
- Speech Recognition
- Children
- Consumer
---
