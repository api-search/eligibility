---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'User: the natural person who has created an Account on the Application, whereby the User declares and guarantees that they are at least 18 years of age.'
    type: individual
  minimum_age:
    text: If the User is younger than 18 years of age, creating an Account and/or using the Services is not permitted.
    value: '18'
  restricted_uses:
  - summary: No use contrary to law, public order or morality
    text: The User is not permitted to use Calmido's Services for purposes that are contrary to legal provisions, public order, or morality.
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
name: Calmido
provenance_date: '2026-11-09'
provider_name: Calmido
provider_slug: calmido-com
slug: calmido-com-eligibility
source_date: '2026-11-09'
source_filename: calmido-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.calmido.com/nl-en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calmido\naid: calmido-com\nurl: https://www.calmido.com/nl-en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'User: the natural person who has created an Account on the Application, whereby the User declares and guarantees\n    that they are at least 18 years of age.'\nrestricted_uses:\n- summary: No use contrary to law, public order or morality\n  text: The User is not permitted to use Calmido's Services for purposes that are contrary to legal provisions,\n    public order, or morality.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If the User is younger than 18 years of age, creating an Account and/or using the Services is not permitted.\n"
source_yaml_url: https://artifacts.apis.io/calmido-com/eligibility/calmido-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Calmido's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice
- Security
- Privacy
---
