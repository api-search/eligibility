---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Consumers with a habitual residence in the EU, EEA or the UK have a legal right to withdraw within 14 days of purchase.
  entity_types:
  - text: the Services are directed at business customers (Unternehmer) within the meaning of Sec. 14 German Civil Code
    type: business
  - text: consumers within the meaning of Sec. 13 German Civil Code (the “Consumer”), provided that they are at least 18 years of age or the age of legal majority at their place of domicile.
    type: individual
  minimum_age:
    text: at least 18 years of age or the age of legal majority at their place of domicile
    value: '18'
  restricted_uses:
  - summary: Compliance with law and AUP
    text: Your use of the Services, in particular with regard to your Input and the generation of Content, must comply with applicable law and the AUP
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require you to provide sufficient proof of your status as a Business Customer prior to conclusion of the agreement.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mirelo
provenance_date: '2026-11-10'
provider_name: Mirelo
provider_slug: mirelo
slug: mirelo-eligibility
source_date: '2026-11-10'
source_filename: mirelo-eligibility.yml
source_heading: Eligibility
source_page: https://mirelo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mirelo\naid: mirelo\nurl: https://mirelo.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Consumers with a habitual residence in the EU, EEA or the UK have a legal right to withdraw within 14 days\n    of purchase.\nentity_types:\n- type: business\n  text: the Services are directed at business customers (Unternehmer) within the meaning of Sec. 14 German Civil\n    Code\n- type: individual\n  text: consumers within the meaning of Sec. 13 German Civil Code (the “Consumer”), provided that they are at least\n    18 years of age or the age of legal majority at their place of domicile.\n\
  restricted_uses:\n- summary: Compliance with law and AUP\n  text: Your use of the Services, in particular with regard to your Input and the generation of Content, must comply\n    with applicable law and the AUP\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require you to provide sufficient proof of your status as a Business Customer prior to conclusion\n    of the agreement.\nminimum_age:\n  value: '18'\n  text: at least 18 years of age or the age of legal majority at their place of domicile\n"
source_yaml_url: https://artifacts.apis.io/mirelo/eligibility/mirelo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Mirelo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Audio
- Sound Effects
- Generative AI
- Video
- Text to Audio
- Audio to MIDI
- Machine Learning
---
