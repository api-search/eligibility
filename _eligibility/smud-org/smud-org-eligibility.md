---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: All marketing or promotional materials and other content found on this Site are solely directed to individuals, companies or other entities located in the SMUD's service territory.
  entity_types:
  - text: In consideration for your use of the Services, you represent that you are of legal age to form a binding contract and are not a person barred from using the Services under the laws of the United States.
    type: individual
  minimum_age:
    text: you represent that you are of legal age to form a binding contract
    value: null
  restricted_uses:
  - summary: Chatbot use limited to SMUD questions
    text: You can use these features only to answer your questions about SMUD programs and services.
  - summary: No violating or unlawful content in Services
    text: Intentionally or unintentionally violate any applicable local, state, national, or international law
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
name: Sacramento Municipal Utility District (SMUD)
provenance_date: '2026-11-10'
provider_name: Sacramento Municipal Utility District (SMUD)
provider_slug: smud-org
slug: smud-org-eligibility
source_date: '2026-11-10'
source_filename: smud-org-eligibility.yml
source_heading: Eligibility
source_page: https://www.smud.org/Corporate/Privacy-policy/Terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sacramento Municipal Utility District (SMUD)\naid: smud-org\nurl: https://www.smud.org/Corporate/Privacy-policy/Terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: All marketing or promotional materials and other content found on this Site are solely directed to individuals,\n    companies or other entities located in the SMUD's service territory.\nentity_types:\n- type: individual\n  text: In consideration for your use of the Services, you represent that you are of legal age to form a binding\n    contract and are not a person barred from using the Services under\
  \ the laws of the United States.\nrestricted_uses:\n- summary: Chatbot use limited to SMUD questions\n  text: You can use these features only to answer your questions about SMUD programs and services.\n- summary: No violating or unlawful content in Services\n  text: Intentionally or unintentionally violate any applicable local, state, national, or international law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you represent that you are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/smud-org/eligibility/smud-org-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Sacramento Municipal Utility District (SMUD)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Utilities
- Electricity
---
