---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Website for purposes relating to your trade, business or profession, any dispute relating to these Terms or to the Website shall be submitted to the exclusive jurisdiction of the competent courts of Paris, France
    type: business
  - text: If you are a consumer, this choice of law does not deprive you of the protection of the mandatory provisions of the law of your country of residence.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: use the Website for any unlawful purpose or in breach of these Terms
  - summary: Export control and sanctions
    text: You agree to comply with these laws and not to export, re-export or transfer such information in breach of them.
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
name: VSORA
provenance_date: '2026-11-10'
provider_name: VSORA
provider_slug: vsora
slug: vsora-eligibility
source_date: '2026-11-10'
source_filename: vsora-eligibility.yml
source_heading: Eligibility
source_page: https://vsora.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VSORA\naid: vsora\nurl: https://vsora.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Website for purposes relating to your trade, business or profession, any dispute relating\n    to these Terms or to the Website shall be submitted to the exclusive jurisdiction of the competent courts of\n    Paris, France\n- type: individual\n  text: If you are a consumer, this choice of law does not deprive you of the protection of the mandatory provisions\n    of the law of your country of residence.\nrestricted_uses:\n\
  - summary: Unlawful purposes\n  text: use the Website for any unlawful purpose or in breach of these Terms\n- summary: Export control and sanctions\n  text: You agree to comply with these laws and not to export, re-export or transfer such information in breach\n    of them.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vsora/eligibility/vsora-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from VSORA's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Semiconductors
- Inference
- Edge AI
- Hardware
- Data Center
---
