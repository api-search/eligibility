---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The user is responsible for ensuring that he/she is a resident of a country where PayPal is available for sending and accepting payments
  entity_types:
  - text: a Sourcing User is a person or party managing a brand
    type: other
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration is required for both Audiodraft users seeking to license or acquire audio, and Audiodraft users that wish to submit their Audio Productions for such opportunities
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Audiodraft
provenance_date: '2026-11-09'
provider_name: Audiodraft
provider_slug: audiodraft
slug: audiodraft-eligibility
source_date: '2026-11-09'
source_filename: audiodraft-eligibility.yml
source_heading: Eligibility
source_page: https://www.audiodraft.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Audiodraft\naid: audiodraft\nurl: https://www.audiodraft.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The user is responsible for ensuring that he/she is a resident of a country where PayPal is available for\n    sending and accepting payments\nentity_types:\n- type: other\n  text: a Sourcing User is a person or party managing a brand\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registration is required for both Audiodraft users seeking to license or acquire audio, and Audiodraft users\n    that wish to submit\
  \ their Audio Productions for such opportunities\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/audiodraft/eligibility/audiodraft-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Audiodraft's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Audio Branding
- Sound Design
- Music Production
- Voiceover
- Crowdsourcing
- Creative Services
- Audio
---
