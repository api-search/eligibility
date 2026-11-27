---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is offered and controlled by its facilities in the Netherlands.
  entity_types:
  - text: The Service is made available to you for your personal use only.
    type: individual
  - text: An organization that has entered into an agreement with Drillster for a fixed term or with an agreed end date may not terminate that agreement for convenience before the agreed end date.
    type: other
  minimum_age:
    text: In any case, you affirm that you are over the age of 13, as the Service is not intended for children under 13.
    value: '13'
  restricted_uses:
  - summary: Commercial solicitation
    text: nor to use the communication systems provided by the Service (chat functionality) for any commercial solicitation purposes.
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
name: Drillster
provenance_date: '2026-11-09'
provider_name: Drillster
provider_slug: drillster
slug: drillster-eligibility
source_date: '2026-11-09'
source_filename: drillster-eligibility.yml
source_heading: Eligibility
source_page: https://drillster.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Drillster\naid: drillster\nurl: https://drillster.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is offered and controlled by its facilities in the Netherlands.\nentity_types:\n- type: individual\n  text: The Service is made available to you for your personal use only.\n- type: other\n  text: An organization that has entered into an agreement with Drillster for a fixed term or with an agreed end\n    date may not terminate that agreement for convenience before the agreed end date.\nrestricted_uses:\n- summary: Commercial solicitation\n  text: nor to use\
  \ the communication systems provided by the Service (chat functionality) for any commercial solicitation\n    purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: In any case, you affirm that you are over the age of 13, as the Service is not intended for children under\n    13.\n"
source_yaml_url: https://artifacts.apis.io/drillster/eligibility/drillster-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Drillster's own page on 2026-11-09.
synthetic: false
tags:
- Assessment
- Education
- Learning
- Quizzes
- Training
- LMS
- Adaptive Learning
- Compliance Training
- Webhook
---
